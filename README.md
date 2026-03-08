# CCF Compat Guide by alakay



In this guide, I will show you how to get Community Cutscene Fixes working with Proper Fixes and basically any other mod. I'm currently running around 400-500+ mods in my game with it, all of the extras are installed and I'm even using Proper Shaders alpha. If you need further help/explanation add my Discord: alakay\_x



Side Note: Give CCF priority over every mod in modloader.ini unless explicitly told not to. (Every mod is at 50 by default, so there is no need to list every mod.)



---



## Quick Navigation



- [Jump to Proper Fixes compatibility guide](#proper-fixes-compatibility)
- [Jump to Urbanize compatibility guide](#urbanize-compatibility)
- [Jump to Uncompressed SFX/Original Radio Extended compatibility guide](#uncompressed-sfx/original-radio-extended-compatibility)
- [Jump to RVP compatibility guide](#revamped-vehicles-project-compatibility)
- [Jump to side notes](#side-notes)





## Proper Fixes Compatibility



1. Install CCF as usual into your modloader, you can also install the CCF extras as well. (I personally did have a crash with the `Rydsmk.cs` script but I actually couldn't even figure out what it did as it didn't affect his cutscenes, so I would recommend removing that)



2. Navigate to `GTASA LOCATION\modloader\CommunityCutsceneFixes\data\maps` and delete the `binary` and `LA` folders.



3. Download this file [Download int_LA.ide](https://drive.google.com/file/d/1Txz20XzwA6TcxlCp9HRsRFhmLMDJpJDz/view?usp=sharing) (provided by user Blu3print from Cleoude's Community Discord server)



4. Replace the `int_LA.ide` in `GTASA LOCATION\modloader\CommunityCutsceneFixes\data\maps\interior` with the one you just downloaded.



5. Increase CCF's priority over Proper Fixes in modloader. (example: CommunityCutsceneFixes = 52 Proper Fixes = 51)



6. Done! Launch the game! If you have any issues it's definitely another mod that I haven't used, but I can try to help you through Discord (username above).





## Urbanize Compatibility



I haven't fully tested all of this, but better safe than sorry, and you can always test it yourself and let me know!



I've heard that CCF can have some issues with Urbanize, so here's what you should do. This will remove the objects around the map that Urbanize places, but it should not affect the objects used by pedestrians and pedestrians interactions, etc. only objects!



Navigate to `GTASA LOCATION\modloader\Urbanize\map` and open `Loader.txt`, comment out (put a # or ; at the beginning of the line) every IPL line except for `Urbanize.IPL`, better safe than sorry and like I said before if anyone wants to test these that would be great. I use Project Props 4.0 and other map/prop mods, so it doesn't really bother me.





## Uncompressed SFX/Original Radio Extended Compatibility


Literally just don't install the CCF Audio, seems to work fine for me and I assume this just fixes/adds some sounds, not a huge deal. Maybe there's a way to get this to work but I haven't messed with it yet. Also increase their priority in modloader over CCF. I no longer use Uncompressed SFX though.





## Revamped Vehicles Project Compatibility



I believe I had a conflict with RVP (I used the original non-meshsmoothed version) I fixed this by just increasing RVP's priority over CCF's in modloader. I also no longer use RVP.





## Side notes



I'm not sure if this is the same without LLP's Characters and outfits, but I had an issue where the default character models didn't have Mobile Hands after installing the character extras from CCF-Extras. Mobile Hands for default characters work, but you need to install the one from here [Download Mobile Hands from mixmods](https://www.mixmods.com.br/2015/07/personagens-de-cutscene-com-dedos-separados-mobile/) and insert it into your modloader and give it priority.

