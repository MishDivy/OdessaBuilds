# Odessa Build

## Date: December 02, 2022

### Configuration: Shipping

### Platform: Windows

### Build Version: 1.3

***

## Running the build

Double click on OdesaTest.exe to run the build. The .exe is located inside the Windows.zip compressed directory.

## Player Characters

**```Robot Guy```** -> White Medium Height Character -> Takes away light from one area and redirects it

**```Mushroom Guy```** -> White Small Height Character -> Acts as a Bounce Pad

**```Plant Guy```** -> Green Character -> Pulls other characters

## General Rules

1) Robot Guy and Plant Guy cannot use ability when not in light.
2) Mushroom Guy cannot use ability when in light.

***

## Known Issues

- Characters sometimes clips through floor or walls in the level.
  
  ```WIP FIX:``` Convert BSP to Static Meshes.

- In the Odessa Test Room (the metric room) sometimes the exterior directional light glitches through walls and can be seen from inside.
  
  ```WIP FIX:``` Convert BSP levels to Static Meshes

- Robot Guy's ability doesn't work properly under directional light.
  
  ```WIP FIX:``` There will be two types of lights: ability triggering lights and normal lights. Directional lights won't trigger ability, once we have a more concrete way to distinguish between these two types of lights.

- When jumping on purple bounce pads the bounce sound gets triggered twice
  
  ```WIP FIX:``` Collision and hit events are being debugged to find out the cause.

- When pulling other characters while jumping doesn't keep the spline mesh attached to the plant guy.
  
  ```WIP FIX:``` Spline mesh system needs to go through further polishing iterations. This was just the first iteration.

## Other Planned Tasks

- Added IK controls to rigs of custom character for feet snapping.
- Ideate and test different camera movements when switching between different characters.
- Add controller navigation in main menu and pause menu.
- Refine the light detection system.

***

## General Controls

 |            | Keyboard | XBOX One Controller |
 |:----------:|:--------:|:-------------------:|
 | **Movement** | W,A,S,D | Left Stick |
 | **Camera** | Mouse | Right Stick |
 | **Switch to Plant Guy** | 1 | Y |
 | **Switch to Mushroom Guy** | 2 | B |
 | **Switch to Robot Guy** | 3 | X |
 | **Toggle Main Ability** | Q | Right Trigger |
 | **Pause Menu** | P or Escape | Right Special Option Button |

 ***

## Developer Controls

**Note:** Developer controls are only available for keyboard devices.

 |            | Keyboard |
 |:----------:|:--------:|
 | **Toggle RagDoll** | T |

 ***

## Feedback

Please take screenshots or screen-recordings if you encounter any bugs. Any other information which can help in reproducing the bug is greatly appreciated.
You can email any bug/feedback related information to dm3473@drexel.edu
