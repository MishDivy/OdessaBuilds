# Build Version: 1.5

## Date: February 04, 2023

### Character Mechanics

- Added custom draft meshes and animations for the robot and mushroom characters.
- Added Plant pull mesh system.
- Added Plant pull prediction system. Players can see a decal on the floor about where the other character will be pulled.
- Added morph target/ blendshape for when mushroom goes in and out of ability.
- **Removed Plant Guy's Aim Mode**. Plant Guy will now be indicated of grabbable actors in range, when in light automatically
- **Redesigned Robot Guy's Aim Mode**. Now player doesn't need to hold left rigger to go in aim. Pressing the right trigger in Light will automatically put the Robot Guy in Aim mode
- **Reimplemented Mushroom Bounce system**. Switched it from a velocity based system to a height based system.
- **Optimized Light Detection Event system**. Now players will experience constant frame rates thoughout level with any character.
- **Added Light Edge Notification Event**. This allows us to warn the player when they are near the edge of a light.
- **Added First Iteration of Procedural Plant Vine Mesh**. When pulling other characters with plant the player can see the new vine mesh.
- Added ability to combine the three characters into one unit for easy traversal.

### User Interface & Persistence Management

- Implemented fully **navigable UI**, with Main Menu and Pause Screens
- Added settings, invert Y axis (yes for Rob), and volume controls added and working
- Settings saved and serialized
- Added HUD to showcase currently possessed character
- Added a compass on the top. In the future, it will showcase the location of the other two unpossesed characters.
- Added text renderer to show hints/tips to the player in form of text on screen.

### Level Design & Implementation

- Added pressure plate, doors and elevator
- Added Demo Puzzle Room (WIP)
- Added Solar panels and horizontal elevators
- Made Demo Puzzle Room Playable
- Added a new easier puzzle room
- Added a spline based Gondola
- Redesigned the puzzle area.
- Added a mini tutorial puzzle area.
- Added Robot Panel.
- Added moving fan that periodically blocks light.

### Sound Effects & Music

- Added footstep and landing sounds using MetaSounds
- Added sounds when using ability or bouncing for mushroom and robot guy.
- Added Haptic/force feedback for controllers when bouncing or pulling.

### Bug Fixes

- Fixed bugs related to plant and light getting stuck in place after using ability.
- Fixed pressure plate bug which stopped it from not updating when mushroom gets in light or not.
- Stablized Robot light when moving in ability.
- Fixed multiple plant pull realted bugs.
- Fixed bugs related to mushroom glowing/not glowing.
- Fixed characters moving with the Plant Character after being grabbed bug.
- Fixed issues of characters getting pulled in the wrong direction by the plant guy.
- Ragdoll mode doesn't get trigger on small jumps anymore.
- Performance bug fixed: fps drop at some spots of the map when Robot is using the ability.
- HUD doesn't show up on menu screens.
- Fixed pressure plate not detecting change of state of mushroom.
- Gondola now carry the attached objects properly.
- Button cannot be pressed by unpossesed character anymore.
- Chain bouncing on environment mushrooms is now possible.
- Gondola rails doesn't interfere with Odessa lights.
