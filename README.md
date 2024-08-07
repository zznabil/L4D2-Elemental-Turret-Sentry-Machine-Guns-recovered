recovered a lost plugin of some kind of elemental turret sentry machine guns systems from sourcemods & github repos.
the guns shoots automatically like a sentry turret, using minigun models.

6 Turret sentry types:
TESLA shoot lightning bullets and disintegrates common zombies
FLAME short range flamethrower, best used in narrow tight corners places
LASER shoot red lasers to zombies
FREEZE slow down or freeze zombies
NAUSEATING vomitjar bile jar bomb the zombies hit
NORMAL/SIMPLE turret with normal machine gun bullets with no elementals effects





i edited the .sp file to disable some LMC and DLR requirements for the code to successfully run.
i edited the .sp file, some ray tracing targeting system to minimize target switching delays of the turret (maybe just placebo).

maybe i edited some other things i forgot...

ORIGINAL(s): 
https://github.com/janiluuk/L4D2_Machine   <<< i used this one for the scripting/compile/smx file/translations file


https://forums.alliedmods.net/showthread.php?t=330721

https://forums.alliedmods.net/showthread.php?t=164543

https://github.com/dvander/sourcepawn-corpus/blob/186cd02e236b90fd43b23898f0ed7e2e5e2165ee/forums/E/r/n/Ernecio/l4d_machine_gun_system_2737334.sp#L232

https://github.com/apples1949/sourcepawn-corpus/blob/7fd6bb17337693f951c6e1baae46644e11fc9bea/forums/E/r/n/Ernecio/l4d_machine_gun_system_2737334.sp#L232


machine 1 is L4D1 minigun model

machine 2 is L4D2 minigun 50cal model

HOW TO USE:
whats known to KINDA WORK:

Turret menu (type " sm_machinemenu " in the console)

Remove all turrets machines (sometimes works. (type "!removemachine" in chat)

Reset reload turret cfg file ("type " !resetmachine " in chat)

long range TESLA Turret (type " !machine 2 tesla " in chat )

long range LASER Turret (type "!machine 2 laser " in chat )

short range flamethrower Turret (type "!machine 2 flame " in chat )









whats known to NOT WORK as expected:

long range FREEZE Turret (type "!machine 2 freeze " in chat ) does not slow down or freeze commons/specials at all?

long range NAUSEATING Turret (type "!machine 2 nauseating " in chat ) does not vomit on commons/specials at all?

long range normal Turret (type "!machine 2 " in chat ) turret does not spawn or does not shoot, i forgot.

gatling gun L4D1 turret model (machine 1) turret does not shoot, but tracks the zombies?
sometimes !removemachine does not work.

If you used the turret like a normal machine gun and then unused it, the turret is now broken and just a normal minigun forever.

If you used the turret like a normal machine gun and then unused it, the !removemachine command will not work.

if you set the manual use inside the cfg file, the turret still can be manually used as a normal machine gun. (meaning the manual use cfg option is broken or useless currently.)
