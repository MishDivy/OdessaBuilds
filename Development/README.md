# Odessa Build

## Date: February 04, 2023

### Configuration: Development

### Platform: Windows

### Build Version: 1.5

***

## Running the build

Double click on OdesaTest.exe to run the build. The .exe is located inside the Windows.zip compressed directory.

## Player Characters

**```Robot Guy```** -> Medium Height -> Takes away light from one area and redirects it

**```Mushroom Guy```**  -> Short Height -> Acts as a Bounce Pad

**```Plant Guy```** -> Tall Height -> Pulls other characters

## General Rules

1) Robot Guy and Plant Guy cannot use ability when not in light.
2) Mushroom Guy cannot use ability when in light.
3) Ignore white colored lights. They do not trigger ability. Only pink-ish and yellow-ish lights trigger abilities of the characters.

***

## Known Issues

- HUD appears in Main Main screen.

- Mushroom does not shrink and grow reliably in and out of light. It also glitches near the edge of light.
  
  ```WIP FIX:``` Experimenting with double colliders on Odessa Lights.

- Robot Guy's ability doesn't work properly under directional light.
  
  ```WIP FIX:``` There will be two types of lights: ability triggering lights and normal lights. Directional lights won't trigger ability, once we have a more concrete way to distinguish between these two types of lights.

- Platforming in puzzle room is not fun.
  
  ```WIP FIX:``` The puzzle room is currently under development.

- In Ragdoll mode the characters glitches through surfaces.
  
  ```WIP FIX:``` We are builing a bug avoidance system for ragdoll mode.

## Other Planned Tasks

- Add Environment assets and lighting in the puzzle room.
- Add a feature to combine the three characters in one character.
- Add a compass on the HUD for finding the other two unpossesed characters anytime during the game.
- Ideate and test different camera movements when switching between different characters.
- Add controller navigation in main menu and pause menu.
- Add a Dialog or hint/tips system.

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
 | **Interact** | E | Right Bumper |

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
