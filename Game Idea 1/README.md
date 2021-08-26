# Text-mode hacking game

> **This page is still under construction, please come back later.**

A Text-mode User interface based hacking game, entirely run from the terminal, using only 256 color XTERM if possible.

***

## Intro

Imagine a city-state, the likes of Singapore, Hong Kong SAR, Monaco, and San Marino. Where the local government wants to create a police state and where the big corporations want to monopolize everything. Where everything is connected to the state owned & controlled "internet".

In this world everything has a chip in it & is connected to the internet in some way. And thusly can be hacked. But the electronics in this world never enjoyed fancy things like "ray-traced graphics" & "HD-video", no... What this world has is Text-mode user interfaces & terminals. Imagine your current UI but rendered in 256-color Box-drawing characters and  mono-spaced fonts.



### Goals

Procedurally generate a City, it's networks, people, systems, corporations, and missions.  
Make a usable Text-mode User Interface (TUI) for almost all devices.  
An engaging, hackable world that "lives".  
No immediate time pressure toward an ultimate failure state.  

### Look & feel

Have you ever used `nano` on linux , or `edit` on Ms-DOS? Those are Text-mode interfaces, now imagine a desktop: You got your taskbar(s), your desktop icons, your little clock widget, and dragable & resizable windows. All of that, but as a text-mode user interface. (with mouse support...)

A desktop manager like [TWIN](https://github.com/cosmos72/twin) fits nicely.  
![Source: https://inconsolation.wordpress.com/2013/01/24/bonus-twin-bigger-and-better-than-ever/](TWIN-Desktop.png "The Twin Desktop.")
Another cool one is [VTM](https://github.com/netxs-group/vtm), It makes full use of the 256 colors, working in things like gradients. They even have a live demo on ssh! Check it out on: `ssh vtm@netxs.online`

There are also some great applications that show off in this style:  
[Midnight Commander](http://midnight-commander.org/) (`mc`), [Spotify TUI](https://github.com/Rigellute/spotify-tui)(`spt`), [MapSCII](https://github.com/rastapasta/mapscii)(`mapscii`), [timg](https://github.com/hzeller/timg/)(`timg`), [VisiData](https://github.com/saulpw/visidata)(`vd`), and many more applications found [here](https://github.com/rothgar/awesome-tuis).


### Gameplay

Hacking for fun, as a job, to gain reputation, and to "save" the Net in the city from the monopolistic corporations & oppressive government.

### Hacking

#### Traversing the networks

**Chaining access**  
In order to gain access to a PC in an apartment, you must first find it by having either an ip address:port or know the address and apt number of the building it's in.
Building router -> apartment router -> scan LAN -> connect to pc.

#### Tracing & being traced

**Logs**  

**Active connections**  

**Warning programs/scripts**  

**Disconnect**  

**Fake logs & framing them**  

#### Remote desktop, web-management, and terminal access

**Remote desktop**  

**web-management**  

**terminal access**  

### Networks

Almost all electronic devices are in some fashion networked. That is Computers, Smart fridges, TVs, Printers, Coffee makers, implants, etc.  
They are all connected to the City Net. This is the central network of The City.

#### Network topology & networking nodes

**Network Topology**

* Wide Area Network(WAN):  
These are the DNS servers, major routers, and servers that manage the entire city state.
* Metropolitan Area Network (MAN):  
These are the routers that connect to city infrastructure systems like traffic lights. These are public WiFi routers. This is what Building routers connect to.
* Backbone Network (BB):  
This is the network of an apartment or office building. Control systems of the building are connected to this network. this network connects all apartment/office LANs to the MAN via the building router.
* Local area Network (LAN):  
This is the network of each individual apartment/office in a building. All devices inside a single apartment or office are connected to/via them. They each have a router that connects the LAN to the BB. (regardless of the amount of devices connected in a LAN, like 100s of PCs in a single office, it still is a single LAN)
* WiFi:  
WiFi is its own network at the MAN level, it provides connectivity to the internet for wireless devices. Only a single WiFi service is available in the city: City Net WiFi.

**Networking Nodes**

* Router  
A router manages the traffic between two or more networks.
* Switch  
A switch forwards traffic from one port to multiple, allowing multiple connections to come together on one connection.
* Firewall  
A firewall blockades unwanted network traffic.
* Access Point  
An access point provides routing for wireless systems over WiFi.

### Devices

There are many kinds of devices in the City, almost all of them have a connection to the City Net in some way. Those that do always have a hackable management system.

#### Networking nodes

**The router**  
**The switch**  
**The firewall**  
**The access point**  

#### Computers & servers

**Computer**  
**Server**  
**Network Attached Storage (NAS)**  
**Printer**  
**Office printer**  

#### "Smart" devices

**TV**  
**Doorbell**  
**Kitchen appliance**  
**Sound system**  
**Game system**  
**Lighting system**  


#### Wireless devices

**Wireless PC**  
**Cellphone**  
**Personal digital assistant (PDA)**  


#### Other systems

**Control sytems**  
**Security systems**  
**Public kiosks**  
**Advertisement screens**  

### World simulation

#### Procedural generation

**Generating the city and its contents**

**Generating the NPCs**  
What I expect is, you simply create some lists (.json files?) with names, brands, jobs, street names, network addresses, etc and have the simulator choose from those lists a random item to create in the world, then keep track of that thing while it simulates.

So to create Jane Doe, who lives in apt.5 on streetname, a type 3 apartment, with a PC model: z123.  
The generator would choose from the table Firstnames, "Jane", from Lastnames, "Doe", select a street from the streets list, choose an available apartment number on that street name, check what type of apartment that would be, and finally choose a PC from the computers list.

### Programs & files

Programs do things on the computer, whereas files only contain data. A program can be in the form of a file or a running script. Some programs need files to function, as input, or as output, or as any combination of those.

Programs (that are files) and files can be moved or copied between systems. Files have a size to them, that size corresponds to its contents of data.

File systems will not be considered beyond simple `format c:` commands or secure erase vs. deleted file recovery. 

#### Directory structure

Filesystems will be based on drives like the `c:` drive or `$q:` drive for "remote" drives. Each hardware "disk" or data storage medium will be its own "drive".

Most PCs wil have a directory structure like this:  
c:\ - root.  
c:\Users - users folder, this contains all user folders on the system.  
c:\Users\JohnDoe - User folder for JohnDoe user account, by default this user can only create & edit files here.  
c:\Users\JohnDoe\Documents|Music|Downloads|Images|Contacts|Mail - JohnDoes user folders.  
c:\OS - Operating system files, by default most of these can't be accessed. This can have different names based on the brand of OS.  
c:\Settings - Contains settings files for the OS, the Desktop, and all programs. Settings for each program are in sub-folders with the same program name. By default, users cannot access these, but Andmin users can.  
c:\Programs - Contains executable programs and Libraries. Each program is in its own sub-folder.  
c:\Programs\OS|Main|Default - default programs that come with the system.  
c:\Logs - Contains logging files. By default inaccessible by users except Admin users.

Other drives will have different drive letters like: `a:` & `b:` for the floppy drives, `d:` for an extra hard drive, and `e:` for the plugged in USB stick. users will have access to these drives, and programs can run off these. However, these drives can be marked as read-only.

#### Files & file formats

There are many different kinds of files. Some files are user created and some are created by the programs.

User files like documents, spreadsheets, presentations, text files, music, etc. Are created by using programs. A word processing program, for example, would save a document in the `.doc` format and only a word processing program can open this `.doc` file.

A `.doc` can be edited by other programs, like the note taking app, but it would in some ways garble the contents. Think more old school Microsoft Office files and less modern open-document formats.

![Source: https://ostechnix.com/how-to-display-images-in-the-terminal/](viu-1.png "An Image as text.")

Image files are rendered as ANSI text. When viewed in a text editor, one would see something like this:
> [K [10;34H [1K(0 [0;1m [37m  
> [34m [47m(0 [0;1m [37m [47m  
> [44m [K [11;34H [1K(0 [0;1m  
> 47m [48X [11;84H (0 [0m [30  

("video" files, I think, would just have to be animated gifs rendered in text.)


#### Databases & mass storage

Databases contain vast amounts of data in records, or rows like in a spreadsheet. Data in such databases can be connected to other data. For example: A drivers license database is connected to the identities database.

Databases often have a system to query data. For example: Searching the drivers Lisence database for the name John Doe.  
These systems can also edit, add or remove records. This however will be logged.

There are also mass storage systems of files, usually in the for of network attached storage (NAS) systems. these usually contain a very large amount of files, or just very big files.

#### Applications (apps), libraries, scripts.

Applications (apps) are the programs a user utilizes to do stuff on a computer. Documents are processed by the word processing app, web browsing is done on the Internet app, and playing music is done by the tunes-player app, etc.

Some programs require extra data in the form of libraries. These library files contain data or embedded files that the program can use in certain situation to preserve memory while it's running. A clock app won't need the data on all timezones in the whole world if it's only displaying the local time.

Scripts are bits of text, lists of terminal commands, that act like a program. these scrips can also be input to the command line as a single command, therefore running in memory and never being a "file".

#### Coding scripts & programs

**Code blocks**  

(Reference [google blockly](https://blockly-demo.appspot.com/static/demos/code/index.html) & [Scratch](https://scratch.mit.edu/) in this part)

***

### Other hacking games

There are various games I drew inspiration from, such as these:

* [Hacknet](https://hacknet-os.com/) - Mostly for the command line usage.
* [Uplink](https://store.steampowered.com/app/1510/Uplink/) - For the "hacking as a job" aspect and mission style.
* [HackMUD](https://www.hackmud.com/) - For the command line scripting and "real time" aspects of hacking.
* [Exapunks](https://www.zachtronics.com/exapunks/) - for writing small programs that make the robots do stuff.



### Comparisons to real "hacking" software

(Add comparisons to tools listed [here](https://tools.kali.org/tools-listing) on the kali linux tools page.)

## Links:

Here are some various links to other Github places that I used for inspiration:  
Rothgars list of [awsome TUIs](https://github.com/rothgar/awesome-tuis).  
Cosmos72s Text mode windows enviroment - [TWIN](https://github.com/cosmos72/twin)  
Netxs-groups [VTM](https://github.com/netxs-group/vtm)

And some sources for the images:  
TWIN desktop from [here](https://inconsolation.wordpress.com/2013/01/24/bonus-twin-bigger-and-better-than-ever/).  
Image as text from [here](https://ostechnix.com/how-to-display-images-in-the-terminal/).  
