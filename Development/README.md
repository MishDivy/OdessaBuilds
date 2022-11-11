# Odessa Build

## Date: November 10, 2022

### Configuration: Development

### Platform: Windows

### Build Version: 1.2

***

## Running the build

Double click on OdesaTest.exe to run the build. The .exe is located inside the Windows.zip compressed directory.

## Player Characters

**```Robot Guy```** -> Red Character -> Takes away light from one area and redirects it

**```Mushroom Guy```** -> Blue Glowing Character -> Acts as a Bounce Pad

**```Plant Guy```** -> Green Character -> Pulls other characters

## General Rules

1) Robot Guy and Plant Guy cannot use ability when not in light.
2) Mushroom Guy cannot use ability when in light.

***

## Known Issues

- When switching characters while in motion or in air maintains the last state of the Character.
  
  ```WIP FIX:``` Characters should turn into ragdoll when switched in mid-air. They should blend into idle animation when switched in motion on ground.

- Robot Guy's Light doesn't move smoothly when moving in ability.

  ```WIP FIX:``` Adding a stabalization function on the Robot light or reparenting it to a stable joint.  

- Robot Guy's ability doesn't work properly under directional light.
  
  ```WIP FIX:``` There will be two types of lights: ability triggering lights and normal lights. Directional lights won't trigger ability, once we have a more concrete way to distinguish between these two types of lights.

- Incomplete Puzzle Room
  
  ```WIP FIX:``` The puzzle room is currently under development.

## Other Planned Tasks

- Add some type of basic mesh vine grabbing animation to showcase Plant Guy's ability.
- Create Ability triggering Rectangle Lights (currently we only fully support Spot and Point Lights)
- Replace the third person Unreal Robot Character with our custom draft mesh Robot Guy with draft animations.
- Ideate and test different camera movements when switching between different characters.
- Add controller navigation in main menu and pause menu.

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

## Feedback

Please take screenshots or screen-recordings if you encounter any bugs. Any other information which can help in reproducing the bug is greatly appreciated.
You can email any bug/feedback related information to dm3473@drexel.edu
