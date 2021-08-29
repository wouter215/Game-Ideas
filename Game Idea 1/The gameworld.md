# The Gameworld
> **This is still under construction, please come back later.**

## ToDo

- [ ] Add vision for game world
    - [ ] The world
        - [x] Technology differences
        - [x] Time & the progression of time
        - [x] Everything is interconnected
        - [x] Looming loss of freedoms
    - [ ] The City
        - [ ] City state
            - [ ] comparisons to current city states
        - [ ] Decline into corruption
            - [ ] monopolization by corporations
            - [ ] Increasing control drive of the government over the people
        - [ ] Politics
            - [ ] Corruption
        - [ ] State Control
        - [ ] Corporate control
    - [ ] The factions
        - [ ] The corporations
            - [ ] Corporate enforcement
        - [ ] The government
            - [ ] The Police
            - [ ] Other government institutions
        - [ ] The public
        - [ ] The Press
            - [ ] News
            - [ ] Newspapers
            - [ ] Journalism
        - [ ] The Public services
            - [ ] Utilities
        - [ ] The criminal organizations
            - [ ] Explain hats
                - [ ] White hat
                - [ ] Black hat
                - [ ] Gray hat
            - [ ] Criminal gangs
            - [ ] Vigilante groups
        - [ ] The Other hackers
            - [ ] Player tutorial group
            - [ ] Hobbyist group
            - [ ] Protest group
            - [ ] Activist group
        - [ ] Economic classes
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