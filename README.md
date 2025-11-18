Final project for the Game Development specialization of Open Education in Computer Science from [Open Source Society University](https://github.com/edcedcedcedc/computer-science).

--- 

#### Topics Covered

- Character Creation and Movement
- Input for PC and Console Controllers
- Extensive Use of Animation Blueprints
  - Anim Instances and their C++ parents
  - 1D and 2D Blendspaces
  - Strafing, Turn-in-Place, Aim Offsets
  - Inverse Kinematics and Animation Curves
  - Character lean while running
  - Crouching (with dynamic capsule resizing)
  - Turn hips while running

- **Weapon Handling and Animations**
  - Weapon fire with recoil animations
  - Reloading
  - Weapon blast and impact particles
  - Weapon beam particles (smoke trails)
  - Bullet shell eject particles
  - Sound effects
  - Blending animations per bone, by bool, and by enum
  - Attach and equip different weapons (pistols, SMGs, assault rifles)
  - Automatic and semi-automatic gunfire
  - Move gun parts (clip/magazine, pistol slide) during animations
  - Camera zoom while aiming

- **Dynamic Crosshairs**
  - Spread in reaction to:
    - Character speed
    - Weapon fire
    - Aiming
    - Jumping
  - Different crosshairs per weapon

- **HUD and Widgets**
  - Widget components showing:
    - Item names, types, ammo counts, rarity
    - HUD animations
  - Full item inventory system

- **Data Management**
  - Data tables in Blueprints and C++
  - Curves to control:
    - Item movement during pickup
    - Color and brightness pulse for material effects
  - Numerous gameplay algorithms
  - Data structures including: structs, enums, arrays, maps, and more

- **Material and Visual Effects**
  - Material creation:
    - Post-process materials
    - Dynamic material instances
    - Setting material properties from C++
    - Driving material properties with curves
    - Material functions
    - Blending materials together
  - Outline effects, Glow/Pulse effects

- **Animations and Retargeting**
  - Retargeting animations and whole Animation Blueprints
  - Animation Montages
  - Anim Notifies for sounds, weapon trails, and custom events
  - Sync markers for footsteps and sync groups

- **Assets Provided in the Course**
  - Sounds, textures, particle effects, meshes
  - Delegates, interfaces
  - Dynamic footsteps depending on surface type
  - Physical materials and surface types
  - Niagara particle systems
  - Line traces

- **Enemy AI**
  - Behavior Trees and Blackboard Components
  - Multiple enemy types with varying health, damage, size, and speed
  - Headshot damage with:
    - Higher damage for headshots
    - Animated number widgets for bullet hits
    - Different colored numbers for headshots
  - Character and enemy health bars
  - Enemy patrol, agro, chase, and attack player
  - Death mechanics and stun mechanics
  - Melee attacks with weapon trails
  - Explosives causing damage and death

- **Level Prototyping and Development**
  - Creating full levels from prototypes using professional assets
  - Light baking
  - Post-process effects

--- 

#### Log
*(See `/log`)*

---

#### Resources 
link to course https://www.udemy.com/course/unreal-engine-the-ultimate-shooter-course/