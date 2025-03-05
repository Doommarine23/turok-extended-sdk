# turok-extended-sdk
Collection of scripts and assets intended for use in Nightdive Studios' Turok Remaster.

#FEATURES

TBD

#LICENSE
Scripts are GPL V3.0 to match the scripts included in the remaster. I don't care what you do, just make cool stuff.
Assets are case-by-case. Anything I've made by myself entirely is CC0, and will be denoted as such.
Many assets are modifications of Turok's existing assets, which have no clear license but I would only use for Turok mods if I was you.

#HOW TO USE

I suggest two use cases, a preferred, and acceptable.

**PREFERRED:**
Similar to other games such as Skyrim where modders use frameworks and SDKs from other modders, you should link to this download page and instruct your players to download it and enable it with your mod.

Your player should load mods in this order to ensure that your mod takes priority and overwrites anything from the SDK where necessary.

1. This SDK
2. Your Mod (Takes Priority)

UPSIDES: Clean separation of your project and my SDK. Less mess for you, and easier to update one or the other because they're individual units.
DOWNSIDES: Users may get confused about mod load order, and if you need to alter something from my SDK, you will need to duplicate those SDK files in your mod.

**ACCEPTABLE:**
If that is not possible, you can extract the root of my SDK's KPF and include it inside your own KPF.

UPSIDES: All together in one package, which eliminates load order issues. Makes it easier for you to modify my SDK code if necessary.
DOWNSIDES: If there is a bug in my SDK, you or players will have to manually fix / merge it.
