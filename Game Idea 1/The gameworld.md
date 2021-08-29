# The Gameworld
> **This is still under construction, please come back later.**

## ToDo

- [ ] Add vision for game world
    - [x] The world
        - [x] Technology differences
        - [x] Time & the progression of time
        - [x] Everything is interconnected
        - [x] Looming loss of freedoms
    - [x] The City
        - [x] City state
            - [x] comparisons to current city states
        - [x] Decline into corruption
            - [x] monopolization by corporations
            - [x] Increasing control drive of the government over the people
        - [x] Politics
            - [x] Corruption
        - [x] State Control
    - [x] The factions
        - [x] The corporations
            - [x] Corporate enforcement
        - [x] The government
            - [x] The Police
            - [x] Other government institutions
        - [x] The public
        - [x] The Press
        - [x] The Public services
        - [x] The Unions
        - [x] The criminal organizations
            - [x] Criminal gangs
            - [x] Vigilante groups
        - [x] The Other hackers
            - [x] Explain hats
                - [x] White hat
                - [x] Black hat
                - [x] Gray hat
            - [x] Player tutorial group
            - [x] Hobbyist group
            - [x] Protest group
            - [x] Activist group
        - [x] Economic classes
    - [ ] The People
        - [ ] Person simulation
            - [ ] Stats
            - [ ] Routines
            - [ ] Minds
            - [ ] Intercommunication
            - [ ] Interaction
        - [ ] Adding & removing people
    - [ ] The network/internet
        - [ ] Websites
        - [ ] Services
        - [ ] Hidden services & websites
    - [ ] (Alternate) History of the wold
        - [ ] The how and why of TUI use
        - [ ] Why everything is connected
    - [ ] Look and feel of the world and The City
        - [ ] Representation to the player
        - [ ] Buildings
            - [ ] Towers
        - [ ] Streets

## The World

This game takes place within a small city state. Located in Random-place, this small nation sits isolated between two superpowers. (Superpowers relative to this city state that is...)

Simply called "The City", this nation has great ties with almost all nations of the world, housing many large office buildings and high tech industry. The City does not, however, get along well with its jealous neighbors. This has caused its government to take a more freedoms restricting pose.

The technology in this world didn't quite go the same way as it did ours. while networking and internet are ubiquitous, fancy graphics are not, resulting is almost all displays to show only in text mode. (or at least, that's how its shown to the player.)

Software wise the world is dominated by a single monolithic company, MegaHard (or evil corp, etc). The operating system people, and the government use is made exclusively by this company. It also makes office applications.  
This corporation wishes to monopolize all computer use, but is thwarted by its last real competitor: Other-company (like how Apple is vs Microsoft)  
There's also a open source alternative (i.e. Linux), but it's not very usable to the average user and is therefore used mostly by hobbyists and hackers.

### Differences in technology

So mostly all systems, computers, devices, are all interconnected to the network. The Internet in The City is controlled by the government, but mostly in a hands-off kind of way. They only only slowly beginning to exercise control, mainly trough the big evil corporations.

This interconnectedness makes it so that any device can, with a little effort, be found on the internet. A lot of these systems can also be interfaced with, mainly through remote desktop, web-interfaces, or terminal interfaces. This is how the player gets to hack all the things.

All computers still use text mode interfaces or a dos prompt. This means all software is like the old dos programs, like edit on ms-dos, or Lotus-123 etc.  
While the PCs do have mouse support, a lot is still done via command line.

The player will view this world purely as text mode. even images will be rendered as colored text. The mode I've tried is 8 by 16 pixel blocks with sigle symbols in them. (open up your command prompt and see its glorious mono-spaced text)  
So everything is rendered as 8 by 16 pixel blocks with symbols in them. These can each have a color. so you can have a block be "green" and the symbol inside it be "red". The color palette would be something like 256-color XTerm.

Not all things inside the gameworld are text mode, just like you can make great looking typeset documents on the command line using something like LaTeX. When the player looks at the world its through this text mode "filter", while the NPC's computers are made up of text mode displays, they can perceive things like advert billboards, typeset documents, and office plants as "normal" as we do. The player will not.

### Time & the progression of time

So in games like [Uplink](https://store.steampowered.com/app/1510/Uplink/) and [Hacknet](https://hacknet-os.com/), time progresses even when the player does nothing. In the Uplink example the player only has a limited amount of time to "stop" the big bad, or else it's game over. This is not what i've got in mind for this game idea. While days go by as normal, I think major story beats should only occur at major mission milestones, or reputation milestones. This isn't to say there's no time pressure, there should be. For example: when you take a mission, you only have two days to complete it. Another example: the evil corp won't launch its master plan until the player gains enough notoriety. 

Local time in game I thing should progress a little faster than IRL, like double the speed.

### Everything is interconnected

In this world all devices have a connection to the internet, whether it's through the LAN or WiFi. All connected devices also have a way to interface with it over the network. These will take the forms of things like remote desktop, where you'll have a window on your screen showing the remote screen, web-interface, where you load up a management website for the device in your browser, and terminal, where you log in to it on the command line like with ssh.

This means that all devices can be hacked, if you have enough skill. The interconnection is managed loosely by the City government. If you compare it to IP addresses, it would be something like 127.20.30.40, "127" would be The City, "20" would be the city block, "30" would be the Tower on the block, and "40" would be the apartment router. While routers may have something like [NAT](https://en.wikipedia.org/wiki/Network_address_translation), this would require a hacker to first break into the router, then navigate the routers internal LAN.

I don't envision private WiFi in this world, public WiFi is provided by the City on the streets, parks, and public spaces. but not internally in buildings. The City government/police plans to use this WiFi to track people. That means hackers can track people too, giving more mission possibilities.

### Looming loss of freedoms

Story wise, the people of The City are looking at oncoming restrictions of freedoms, both from the The City government & the corporations. The City government is "concerned" about the press looking into official corruption (this corruption is steadily increasing as the corporations gain more power) and about possible enemy action from its larger neighbors. The corporations want to monopolize peoples lives, the evil corp wants all the users to use its OS, the advertisement company wants everyone looking at its ads (and legally ban adblock for example).

The Press Is facing increasing legal action against it, first from the corrupt politicians, then also from the corporations. There are some public interest groups (think [EFF](https://www.eff.org/)) that wish to push back against this trend, but in this world they are hopelessly out-funded by the corporate lobbyists.

The big fear is that The City will slowly turn into a corporate controlled Police State.

As for the computer users, the OS supplied by the big evil corp is increasingly more locked down with each "upgrade". This means that the OS won't let its users first have thing like "admin" privileges, second only allow big evil corp apps to run, and third have backdoor access for the government/police (and criminals).

## The City

The City, a city state between two superpowers (again, relative to it the might as well be), consists of a grid of streets making city blocks. The City has a big park in the center, a coastline with a port, and is packed to the brim with high-rise apartment buildings and offices. Underneath the city runs a subway network. Its industry is high tech, mostly web-services, data centers, and chip making.

This city is quite wealthy for its size, average income is high, but the pay-gap between rich and poor is growing (also thanks to official corruption). Many international banks have a HQ in The City.

### City State

As its own independent nation, The City has a seat at the [UN](https://www.un.org/), and is considered the crown jewel of the region (Where in the world is it? who knows, somewhere between Wakanda and Sokovia).

Its tourism business is not very big, most hotels only server traveling business people.

The City has a currency, both in cash and "digital" form, although not in the crypto-coin kind of way. The currency is called the City [Stater](https://en.wikipedia.org/wiki/Stater) with the symbol "`¤`". 1,00 Stater buys you one loaf of bread.

The Food supply to its population goes through its port, though there are some efforts going on indoor farming in one or two of its towers.

#### Comparisons to current city states

Currently there are several [city states](https://en.wikipedia.org/wiki/City-state#Modern_city-states) in the world: [Monaco](https://en.wikipedia.org/wiki/Monaco), [Singapore](https://en.wikipedia.org/wiki/Singapore), the [Vatican](https://en.wikipedia.org/wiki/Vatican_City), [San Marino](https://en.wikipedia.org/wiki/San_Marino), [Hong Kong SAR](https://en.wikipedia.org/wiki/Hong_Kong), and [Macau SAR](https://en.wikipedia.org/wiki/Macau).

Many of these are oriented toward tourism, business or religion (tax avoidance). I'd say The City has about the surface area of Macao. But the wealth of Monaco with a GDP (ppp) total of about $20 billion.

Unlike Hong Kong or Macao, The City has no political overlord, it is fully independent.

### Decline into corruption

Once a bastion of democratic process & press freedom. The City government is slowly losing its way, politicians are increasingly more corrupt, giving in to bribes and corporate lobbying. While the Press freedoms keep decreasing, Corporations, politicians, and the very rich increasingly launching lawsuits at the press for uncovering their corrupt activities.

"Fearing" hostile action by its neighbors, The City increasingly employs "covert" action against its own population to "root out" spies, officially that is. On the more corrupt end, they use the police to silence critics and press.

#### Monopolization by corporations

The people currently still have a "free" choice of OS for their PCs. They have the choice between the ubiquitous OS by the big evil corp, A competitor to it (again like MacOS to Windows), or an open source alternative (Linux something). The big evil corp is trying to change that. Restricting what kind of PCs its OS can install on & providing [Lock In](https://en.wikipedia.org/wiki/Vendor_lock-in) to almost all business users of the OS. They also make PCs themselves and are locking down its hardware to its own OS.

Other software is being restricted by the big evil corps OS, as newer versions of the OS no longer allow for "admin" access to install non-big evil corp software. The big evil corps OS is of course also continuously more loaded with popup ads and back-doors for the State.

The Bigger corporations are paying off government official for monopolizing contracts and increasingly running [FUD](https://en.wikipedia.org/wiki/Fear,_uncertainty,_and_doubt) against open source software.

#### Increasing control drive of the government over the people

To stave off the "external threats", the government of The City increasingly deploys surveillance against its citizens. This includes wiretapping phone calls, intercepting emails, and other communications. But also tracking people through the public WiFi.

While officially this is used against "spies", the politicians and government bureaucrats increasingly see to its use against the free press and activists.

Internet wise, the government wants to "protect the children" by censoring "adult websites", but they are also beginning to block other sites, like the download page for the free open source OS to "protect" against "hackers".

The Police wishes to make its work easier by adding more cameras to the City, and using government back-doors in operating systems to read info. Increasingly doing so without a warrant.

### Politics

The City is run by a small congress of elected officials, and its head of state is the Chief Executive.

While elections are free, many of the elected politicians were "sponsored" by big corporations.

Each residential block has its own community commission, they receive and handle the concerns of their blocks residents over to the government.

Many industries have unionized workers, for example the port workers, public sector workers, and the chip factories workers. although these are increasingly clamped down on.

#### Corruption

[Political corruption](https://en.wikipedia.org/wiki/Political_corruption) ranges from taking bribes to embezzlement to cronyism. There are still un-corrupt and un-corruptible politicians, but they are aging out of politics.


### State Control

The City government controls the City Net, all public services, the subway system, and many public housing buildings.

Where it comes to lawmaking, the congress is failing to push back against the corporate lobbying.

## The factions

There are various "factions" for the game in The City, these are: The Corporations, The Government, The Public, The Press, The Public services, The Unions, The Criminal organizations, The Hackers, and the economic classes.

NPCs can be part of multiple of these factions at once.

### The Corporations

The Corporations are mostly in it for the money, specifically, to insure that the share holders (the rich) get the most returns an their investments.

#### Corporate enforcement

Some corporations, like Big evil corp, have their own "enforcement" groups. These are like private security groups or corporate IT hackers.

Their goal is corporate security, protecting against hackers, and rooting out industrial spies from The Cities neighbors.

If they find hackers (you the player), then they mostly just report it to the police, or they send their IT after them.

### The Government

The govenment concerns itself with lawmaking, tax collection, and city management.

#### The Police

The Police serve to reduce crime, including cyber-crime. They also hand out parking tickets.

#### Other government institutions

Public utilities, Hospitals, Fire Departments, Libraries, Parks, and stuff.

### The Public

The citizenship of The City just wants to live and have a job. They may have opinions on the goings on of The City. Including the players activities.

### The Press

The City enjoys several Press outlets in multiple forms of media. News on TV, Radio, and News Websites comes from press outlets of different categories. You have the corporate media (Main stream media), Independent media (Blogs, smaller news sites and outlets), and the state press (mostly announcing new laws and stuff).

Press journalists search for new stories by talking to people on the street, or by getting tips.

### The Public services

These are the public service workers.

### The Unions

The unions are gatherings of specific worker groups per work sector. Unions provide a way for workers of a company to collectively demand better worker conditions and salary.

(Corrupt influence in The City government is increasingly driving laws criminalizing union action and even membership.)

### The Criminal organizations

The City has various criminal organizations, mostly in the illegal narcotics trade.

The Gangs are crime groups consisting of small groups of people. they usually have a "hideout" location or a base of operations. apart from petty vandalism, they're increasingly leaning toward cyber-crime.

Vigilante groups are "hard core" activists that sabotage Corporate processes or "go after" corrupt politicians reputation.

### The Hackers

The "hackers" are people with the knowledge to use computer systems in a more liberated way. Most hackers use their knowlede of cyber systems to make money, or create some change in the world.

#### The Hats

The hacker group is somewhat divided in hats.

**White hat**
White hat hackers work in the open, usually hired by others to "test" their systems security.

**Black hat**
Black hat hackers work in the shadows, mostly to earn money or to collect secrets to sell.

**Gray hat**
Gray hat hackers work for corporations like big evil corp to influence politicians, perform cyber attacks on compeditors, and "go after" other hackers.


#### Player tutorial group

When the player first leans about the possibility of hacking, this tutorial goup helps them along in a sting of increasingly difficult lessons. They disband/Are eliminated/Loose relevance/ etc. after the player finishes the tutorial.

####  Hobbyist group

These are mostly singular or small groups of hackers that type away at their keyboards about a single small subject. Like the new OS by big evil corp.

When the player hacks into a random apartment to find weird electronics and source code documents, they've probably found a hobbyist hacker.

#### Protest group

These are groups of hackers spreading protest material of some public grievance. Like hacking a billboard to show how big evil corp is bad yo.

#### Activist group

Activist hackers employ their knowledge to enact some kind of social change. Like demonstrating the back-door in big evil corps latest OS release.

### Economic classes

The people of the City can be divided along economic lines, you have: the unemployed, the lower class, middle class, upper class, and the rich. Above the rich are also the 1% and above them the 0.1%.

## The People