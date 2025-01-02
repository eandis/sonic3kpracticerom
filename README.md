# s3k speedrun practice hack
speedrun practice hack for sonic 3 &amp; knuckles

another rewrite of this project. it has some stuff it didnt before and some stuff is missing

# features:
- music toggle
- time bonus toggle
- speedrun hud (see image below)
- frame advance toggle (press c in pause)
- level restart toggle (press a in pause)
- custom hud (you can set an address to watch and display a word from it on hud)
- custom restart bind (set any keycombo to restart the level)
- rgb menu (you cant turn it off haha)
- no saving options to sram :( (someday..)

  # known issues:
  - options are not saved to sram so every hard reset it will wipe your settings
  - exit doesnt work in custom bind menu
  - setting address in custom hud is janky
  - some minor debugging stuff is left in the release
  - fast hud is janky
  - some strings in menu are unfinished
 
  # to do
  - add a toggle to turn off rgb color cycling
  - save options to sram
  - polish up menus
  - bring back all features from old practice hack

# screenshots:
![image](https://github.com/user-attachments/assets/9ab39a0f-6c82-433d-b3ca-24bf75833d24)
![image](https://github.com/user-attachments/assets/9517f795-e15e-44b0-8b91-4d963e7ef3dc)
![image](https://github.com/user-attachments/assets/bf958005-88b7-4066-b753-209c0a9051a6)
![image](https://github.com/user-attachments/assets/b524da22-4625-4279-8e47-1dac24a251d6)

![image](https://github.com/user-attachments/assets/bbc02f87-bb4c-4aaa-8bff-25f41c3a38b6)

# Building:
get sk source from https://github.com/sonicretro/skdisasm 
put the files from this repo into the root folder and run buildS3Complete.bat


  
