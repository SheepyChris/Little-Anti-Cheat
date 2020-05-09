# Little Anti-Cheat - Development Notes:

Alright, so there is one "small" problem I've created with this project.
In the past... And actually, since always, I've used Github to host developmental code.
I never intended for my github code to be seen as the stable release of anything.
Especially not this project.

Sadly, I never made that clear.
And up until now, I never used any other branch than "master"...
Meaning there have been a lot of server owners (Especially Russians) now who have relied on my developmental, unofficial and unstable code to protect their servers against cheaters.

This... Is just a really unprofessional and terrible way of managing a project...
And it has also made a mess of things. Because of this, the version 1.5.0 in the master branch isn't actually stable... Well, it is, but it isn't officially so.
Not to forget, the precompiled binary isn't even updated to the latest official stable release, version 1.3.0.

Going forward, this development branch is where I'll host recent, untested and suggestions.
Once version 1.5.0 is done and has been tested, the master branch will be updated.
I appologize for my mess, I should have known better.

Just so it's said, version 1.5.0 in the master branch **IS** stable and won't cause problems, but a new update will come with the same version number, so that may be confusing.

### Current developmental stuff:
1. *"MaterialAdmin"* was added in version 1.4.0, and should work for everyone.
2. I've added a new command *"lilac_set_ban_length"*, which lets you set ban lengths for specific cheat features, as Panikajo asked for.
3. I've added a new ConVar *"lilac_aimbot_autoshoot"* that lets you disable autoshoot detections, as Pandaman09 asked for.


### Todo:
1. Aimlock\
Aimlock detections have been a problem for some server owners now, somehow...\
I'm not sure what causes the issues for others, as I've never had them.\
That said, I **"""""FIXED"""""** the issue by nerfing Aimlock detections to the abyss and byond...\
Meaning I never actually solved the underlying problem, only made it less sensitive to actual aimlocking...\
So yeah, I should update Aimlock to be more sensitive again and actually look into why some people in CS:GO are having problems.

2. Left 4 Dead (1) Support\
Currently in version 1.5.0, L4D is supported, but the only confirmation I've had that it works is from one server owner.\
Because of this, and because of the next problem I'm about to list, L4D support is not official as of now.

3. NoLerp\
Oddly enough, two server owners are having issues with NoLerp detections detecting legit players.\
Sadly, I have not been able to reproduce any false positives at all, and these server owners haven't really responded to my questions regarding their server settings.\
I suspect the problem lies with the interp settings the server allows... But not sure.\
It is something I will look more into.

4. Code cleanup\
Currently, the code isn't a mess, but some parts are inconsistently formatted.\
I should go over my code and make it more consistent.

5. SourceTV support\
I am working on a second plugin that will make use of the forwards Lilac provides, so that SourceTV can automatically start recording when a cheater is detected.\
The code itself is short and simple, but I haven't tested it much as of late.

6. Auto Update\
This is something I haven't looked into, but I've been asked twice now to add support for auto updates.
