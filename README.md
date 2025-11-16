# GAME_PROGRAM-EX--3

# AIM
To replace the default third person character mesh with a custom skeletal mesh and apply new animations using an animation blueprint.

# Procedure

# 1.Import New Character Mesh and Animations:

  . In the Content Browser, import a new Skeletal Mesh along with its Animations (FBX files).
  .  Ensure the mesh is rigged correctly (ideally to the UE4 Mannequin Skeleton or compatible with it).

# 2. Replace Character Mesh:

. Open the ThirdPersonCharacter Blueprint (usually found in ThirdPersonBP/Blueprints).
. Select the Mesh component.
. In the Details Panel, change the Skeletal Mesh to the newly imported mesh.

# 3. Set Animation Blueprint:

 . If available, assign a matching Animation Blueprint in the Details Panel under the Animation section.
.If not available, create one:
.Right-click in the Content Browser → Animation → Animation Blueprint.
.Choose the correct skeleton.
.In the AnimGraph, set up state machines or direct animation nodes.
.Compile and save.

# 4. Preview and Test:

.Place the character in the level.
.Press Play to test idle, walk, and run animations based on character movement.

# OUTPUT:

<img width="843" height="577" alt="441632573-da92e5cf-9199-4e45-90e3-697916a28716" src="https://github.com/user-attachments/assets/07df02ce-0170-4da3-a81f-56e7cb2f3986" />

<img width="476" height="420" alt="441632759-98c10596-d453-4b40-b1c9-6fd5630b63ac" src="https://github.com/user-attachments/assets/826795e7-9683-4602-b32f-24a553079f7c" />

<img width="1541" height="912" alt="441633417-b8b2a3ec-eab5-44a2-9213-097a6d7f7845" src="https://github.com/user-attachments/assets/6c2a28cd-3da5-483a-b259-bb792aef9080" />

# RESULT:
The default Third Person C.

