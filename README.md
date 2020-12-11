# Stranger, [over here](https://github.com/RivenSkaye/RivenSkaye.github.io "The git repo").
Welcome to my Github Pages! I regret to inform you that this is still under construction, however.

## The basic idea
Well, since the whole Github Pages concept is to be a description of or a form of documentation for your work...
This will be some documentation on my open source and availlable work.
This will also be used for me to develop my own licenses; an open-source license and a source-availlable license.

Any work I forked, brnached or contributed to will be linked to from here. Both my branch/fork and the master of the repo.
That works both ways. If you'd like to be mentioned or want to contribute, I'll credit where it's due.
So feel free to fork, add issues or contribute! Ofcourse, there'll be guidelines for that. All in due time...

## My work and what I've forked
### [Prysm](https://github.com/RivenSkaye/PrysmBot "The repo")
This is my very own Discord bot. Written purely in Python with the discord.py library for interfacing with the service. It's a utility bot I created because I notice a lot of free bots don't offer many of the things I plan to put in.
Not to mention it's a great way to get started on learning a new language.

With the bot up and running locally, I can't offer a single instane to the public. I can, however, offer code and instructions for anyone to host it themselves.
Currently the average uptime varies with how long my system is running, but it has a `restart` function that pulls in the most recent code through git before restarting itself using `os.execv`. ~~This seems to be broken on Windows hosts though~~

### [DeLorean Dark](https://github.com/RivenSkaye/DeLorean-Dark-3.18 "My version")
I've done some work to make [DeLorean Dark](https://github.com/killhellokitty/DeLorean-Dark-3.18 "The original") compatible with GNOME Shell/GTK+ 3.22.
And although it's pretty much a hackjob, it looks decent and it functions.
I tried to apply the theme and got plenty errors to send me on my way. Fixing these allowed for more and more components to be themed.

As I went, I started noticing deprecation errors and warnings.
Figuring code like this can be volatile and warnings might break any update, I fixed those as well.
It's actually a great way to start learning GTK+! I can still recall some of the stuff I did and read through the rest.
