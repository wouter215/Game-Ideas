# Text-mode hacking game

> **This page is still under construction, please come back later.**

A Text-mode User interface based hacking game, entirely run from the terminal, using only 256 color XTERM if possible.

***

## Intro:

### Goals:

### Look & feel

Have you ever used `nano` on linux , or `edit` on Ms-DOS? Those are Text-mode interfaces, now imagine a desktop: You got your taskbar(s), your desktop icons, your little clock widget, and dragable & resizable windows. All of that, but as a text-mode user interface. (with mouse support...)

A desktop manager like [TWIN](https://github.com/cosmos72/twin) fits nicely.  
![Source: https://inconsolation.wordpress.com/2013/01/24/bonus-twin-bigger-and-better-than-ever/](TWIN-Desktop.png "The Twin Desktop.")
Another cool one is [VTM](https://github.com/netxs-group/vtm), It makes full use of the 256 colors, working in things like gradients. They even have a live demo on ssh! Check it out on: `ssh vtm@netxs.online`

There are also some great applications that show off in this style:  
[Midnight Commander](http://midnight-commander.org/) (`mc`), [Spotify TUI](https://github.com/Rigellute/spotify-tui)(`spt`), [MapSCII](https://github.com/rastapasta/mapscii)(`mapscii`), [timg](https://github.com/hzeller/timg/)(`timg`), [VisiData](https://github.com/saulpw/visidata)(`vd`), and many more applications found [here](https://github.com/rothgar/awesome-tuis).


### Gameplay

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

### Programs

***

### Other hacking games

There are various games I drew inspiration from, such as these:

* [Hacknet](https://hacknet-os.com/) - Mostly for the command line usage.
* [Uplink](https://store.steampowered.com/app/1510/Uplink/) - For the "hacking as a job" aspect and mission style.
* [HackMUD](https://www.hackmud.com/) - For the command line scripting and "real time" aspects of hacking.
* [Exapunks](https://www.zachtronics.com/exapunks/) - for writing small programs that make the robots do stuff.



### Comparisons to real "hacking" software

## Links:

Here are some various links to other Github places that I used for inspiration:  
Rothgars list of [awsome TUIs](https://github.com/rothgar/awesome-tuis).  
Cosmos72s Text mode windows enviroment - [TWIN](https://github.com/cosmos72/twin)  
Netxs-groups [VTM](https://github.com/netxs-group/vtm)

And some sources for the images:  
TWIN desktop from [here](https://inconsolation.wordpress.com/2013/01/24/bonus-twin-bigger-and-better-than-ever/).  
