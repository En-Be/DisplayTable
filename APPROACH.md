# Approach

Total time on project = ?

## Session 001

Minutes: 180

DONE
- Set up project
- Set up a progress board in notion
![](WIP/wip_003.png)
- Gather reference
![](DesignDocs/reference.png)
- Sketch main characters
![](DesignDocs/sketches_001.png)
![](DesignDocs/sketches_002.png)
- Sculpt humanoid character and set up basic scene in Blender
![](WIP/wip_002.png)
![](WIP/wip_001.png)

---

## Session 002

Minutes: 90

DONE
- Improved human sculpt
![](WIP/wip_004.png)

---

## Session 003

Minutes: 70

DONE
- Dog sculpt
![](WIP/wip_005.png)

---

## Session 004

Minutes: 30

DONE
- Robot sculpt
![](WIP/wip_006.png)

---

## Session 005

Minutes: 100

DONE
- Clay material setup
![](WIP/wip_007.png)
![](WIP/wip_008.png)

---

## Session 006

Minutes: 240

DONE
- Tried remeshing tools to make lighter mesh, couldn't get good results
- Manual retopology of human character, using shrinkwrap modifier and snapping to 'face nearest' of sculpt
![](WIP/wip_009.png)

---

## Session 007

Minutes: 60

DONE

- Manual retopology of dog character, using snapping to 'face nearest' of sculpt
![](WIP/wip_010.png)

---

## Session 008

Minutes: 30

DONE

- Manual retopology of robot character, only of main shape as the rest is box modelled
![](WIP/wip_011.png)

---

## Session 009

Minutes: 90

DONE

- Rigging of characters. Rigify for the human and dog, simple bones for the robot.
![](WIP/wip_012.gif)
![](WIP/wip_013.gif)
![](WIP/wip_014.gif)

---

## Session 010

Minutes: 65

DONE

- Human character idle and run animations
![](WIP/wip_016.gif)
![](WIP/wip_015.gif)

---

## Session 011

Minutes: 75

DONE

- Dog character idle and run animations
![](WIP/wip_017.gif)
![](WIP/wip_018.gif)

---

## Session 012

Minutes: 50

DONE

- Robot character idle and run animations
![](WIP/wip_019.gif)
![](WIP/wip_020.gif)


---

## Session 013

Minutes: 45

DONE

- Started a new Unreal project
- Changed third person camera to not inherit any rotations and be above player
- Changed the default player character to an orb with an updated motion blueprint that rolls based on speed
![](WIP/wip_022.png)
- Added a possess node to the level blueprint that changes the player to the mannequin character when '1' is pressed on the keyboard
![](WIP/wip_023.png)
![](WIP/wip_021.gif)

---

## Session 014

Minutes: 120

DONE
- Changed to orb character to have movement based on physics instead, so as to ignore the rotation/normal of the ball and apply force in directions consistent with the input
![](WIP/wip_024.png)
- Made a material with animated noise displacement
![](WIP/wip_026.png)
![](WIP/wip_025.gif)

---

## Session 015

Minutes: 60

DONE
- Modelled a detailed orb
- Imported orb
- Added to orb charecter, made sphere mesh invisible
- Turned off all collisions and physics for orb
![](WIP/wip_027.gif)

---

## Session 016

Minutes: 30

DONE
- Baked biped character diffuse and normal textures
- Applied textures in Unreal
![](WIP/wip_028.gif)

---

## Session 017

Minutes: 45

DONE
- Used Game Rig tools in Blender to generate a deform rig and bake animations to it
- Exported biped and imported in Unreal, set up as third person character with one animation looping
![](WIP/wip_029.gif)

---

## Session 018

Minutes: 30

DONE
- Set a bool in the character controller that is checked by the animation graph for transitions between states
![](WIP/wip_31.png)
![](WIP/wip_32.png)
![](WIP/wip_33.png)
![](WIP/wip_030.gif)

---

## Session 019

Minutes: 60

DONE
- Simple jump animation transitions
![](WIP/wip_034.gif)
![](WIP/wip_035.png)
![](WIP/wip_036.png)

---