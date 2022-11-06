# OdessaBuilds

Contains builds for the Odessa Tree game

## Cloning using Git CLI

- Install [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [Git LFS](https://git-lfs.github.com/).
- ```git clone``` command can be used for cloning the entire repo including LFS files.
- To ignore cloning LFS files (Builds in the zip folders) use the command below:
  
        export GIT_LFS_SKIP_SMUDGE=1
        git clone --filter=blob:none https://github.com/MishDivy/OdessaBuilds

## Running the build

Double click on OdesaTest.exe to run the build. The .exe is located inside the Windows.zip compressed directory.

## Player Characters

**```Robot Guy```** -> Red Character -> Takes away light from one area and redirects it

**```Mushroom Guy```** -> Blue Glowing Character -> Acts as a Bounce Pad

**```Plant Guy```** -> Green Character -> Pulls other characters

## General Rules

1) Robot Guy and Plant Guy cannot use ability when not in light.
2) Mushroom Guy cannot use ability when in light.

## General Controls

### Keyboard

 ```Movement``` -> W,A,S,D

 ```Camera``` -> Mouse

 ```Switch to Mushroom Guy``` -> 2

 ```Switch to Robot Guy``` -> 3

 ```Switch to Plant Guy``` -> 1

 ```Toggle Main Ability``` -> Q

 ```Main Ability Aim```* -> Right Mouse Click

### XBOX One Controller

 ```Movement``` -> Left Stick

 ```Camera``` -> Right Stick

 ```Switch to Mushroom Guy``` -> X

 ```Switch to Robot Guy``` -> B

 ```Switch to Plant Guy``` -> Y

 ```Toggle Main Ability``` -> Right Trigger

 ```Main Ability Aim``` -> Left Trigger

*Controls may vary for each build. To know build specific controls, please refer to the README.md stored in the same folder as the build.

## Feedback

Please take screenshots or screen-recordings if you encounter any bugs. Any other information which can help in reproducing the bug is greatly appreciated.
You can email any bug/feedback related information to dm3473@drexel.edu
