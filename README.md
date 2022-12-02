# OdessaBuilds

Contains builds for the Odessa Tree game

### Latest Build Configuration: ``Shipping``

## Cloning using Git CLI

- Install [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [Git LFS](https://git-lfs.github.com/).
- ```git clone``` command can be used for cloning the entire repo including LFS files.
- To ignore cloning LFS files (Builds in the zip folders) use the command below:
  
        export GIT_LFS_SKIP_SMUDGE=1
        git clone --filter=blob:none https://github.com/MishDivy/OdessaBuilds

## Running the build

Double click on OdesaTest.exe to run the build. The .exe is located inside the Windows.zip compressed directory.

## Player Characters

**```Robot Guy```** -> White Medium Height Character -> Takes away light from one area and redirects it

**```Mushroom Guy```** -> White Small Height Character -> Acts as a Bounce Pad

**```Plant Guy```** -> Green Character -> Pulls other characters

## General Rules

1) Robot Guy and Plant Guy cannot use ability when not in light.
2) Mushroom Guy cannot use ability when in light.

## General Controls

 |            | Keyboard | XBOX One Controller |
 |:----------:|:--------:|:-------------------:|
 | **Movement** | W,A,S,D | Left Stick |
 | **Camera** | Mouse | Right Stick |
 | **Switch to Plant Guy** | 1 | Y |
 | **Switch to Mushroom Guy** | 2 | B |
 | **Switch to Robot Guy** | 3 | X |
 | **Toggle Main Ability** | Q | Right Trigger |
 | **Main Ability Aim*** | Right Mouse | Left trigger |
 | **Pause Menu** | P or Escape | Right Special Option Button |

*Controls may vary for each build. To know build specific controls, please refer to the README.md stored in the same folder as the build.

## Developer Controls

**Note:** Developer controls are only available for keyboard devices.

 |            | Keyboard |
 |:----------:|:--------:|
 | **Toggle RagDoll** | T |

## Feedback

Please take screenshots or screen-recordings if you encounter any bugs. Any other information which can help in reproducing the bug is greatly appreciated.
You can email any bug/feedback related information to dm3473@drexel.edu
