# Text-mode hacking game

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

### Networks

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
