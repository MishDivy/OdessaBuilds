# Odessa Build

## Date: February 10, 2023

### Configuration: Development

### Platform: Windows

### Build Version: 1.6

***

## Running the build

Double click on OdessaTest.exe to run the build. The .exe is located inside the Windows.zip compressed directory.

## Survey

After playing the build, please fill out this [survey form](https://drexel.qualtrics.com/jfe/form/SV_3UG2s1qiRmoEFMO).

We value your feedback and make crucial decisions based on it.

## Player Characters

**```Robot Guy```** -> Medium Height -> Takes away light from one area and redirects it

**```Mushroom Guy```**  -> Short Height -> Acts as a Bounce Pad

**```Plant Guy```** -> Tall Height -> Pulls other characters

## General Rules

1) Robot Guy and Plant Guy cannot use ability when not in light.
2) Mushroom Guy cannot use ability when in light.
3) Foliage and Natural vegetation does not trigger abilities.
4) Ignore white colored lights in the big level. They do not trigger ability.

***

## General Controls

 |            | Keyboard | XBOX One Controller |
 |:----------:|:--------:|:-------------------:|
 | **Movement** | W,A,S,D | Left Stick |
 | **Camera** | Mouse | Right Stick |
 | **Switch to Plant Guy** | 1 | Y |
 | **Switch to Mushroom Guy** | 2 | B |
 | **Switch to Robot Guy** | 3 | X |
 | **Combine** | 4 | Down D-Pad |
 | **Toggle Main Ability** | Mouse Left Click | Right Trigger |
 | **Pause Menu** | P or Escape | Right Special Option Button |
 | **Interact** | E | Right Bumper |

 ***

## Known Issues

- Ignoring white lights is annoying, and gets confusing sometimes.

  ```WIP FIX``` We are building two different types of lights, artifical (Electric bulbs, tube lights etc.) and natural lights (Glowing plants and mushrooms). Only artificial lights will trigger ability.

- Some of the rooms are too dark.

  ```WIP FIX:``` We are currently working on setting up lights throughout the level.

- No collision on many assets.
  
  ```WIP FIX:``` We are working on adding relaible collisions on all of our assets.

- Mushroom glitches near the edge of light.
  
  ```WIP FIX:``` Experimenting with double colliders on Odessa Lights.

- Robot Guy's ability doesn't work properly under directional light.
  
  ```WIP FIX:``` There will be two types of lights: ability triggering lights and normal lights. Directional lights won't trigger ability, once we have a more concrete way to distinguish between these two types of lights.

- In Ragdoll mode the characters glitches through surfaces.
  
  ```WIP FIX:``` We are builing a bug avoidance system for ragdoll mode.

## Other Planned Tasks

- Add Environment assets and lighting in the puzzle room.
- Change icons and compass design on the HUD for finding the other two unpossesed characters anytime during the game.
- Ideate and test different camera movements when switching between different characters.
- Add controller navigation in main menu and pause menu.
- Add more sound effects.

***

## Developer Controls

**Note:** Developer controls are only available for keyboard devices.

 |            | Keyboard |
 |:----------:|:--------:|
 | **Toggle RagDoll** | T |
 | **Force Combine** | Ctrl + 4 |

 ***

## Feedback

Please take screenshots or screen-recordings if you encounter any bugs. Any other information which can help in reproducing the bug is greatly appreciated.
You can email any bug/feedback related information to dm3473@drexel.edu
