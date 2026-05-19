# Moving from v2 to v3

## Whats changed?

### Actor tab

- Actor List
    - This is now housed in the workspace window which is where almost all actions take place in.
    - Adding an actor can be done by using the + symbol on the bottom left hand side of the Ktisis Workspace and selecting 'Create new actor'.
- Animation Control and Appearance Editing
    - You can access animation control, appearance and equipment editing by middle clicking on an actor or right clicking on an actor and hitting 'Edit Appearance'.
- Gaze Control
    - The gaze controls have been expanded and added to the object editor, which you can get to by right clicking on the actor you want to edit, and under the dropdown 'Advanced (Gaze/IK)'.
- Import & Export
    - These controls have moved also to the right click context menu, select the actor you want to modify, right click, then you can import a 'Character (.chara)' or NPC, and via the export menu a 'Character (.chara)' file.

### Pose tab

- Transform editor
    - This can now be found in the object editor, right click on the actor you wish to manipulate to get there.
- Bone Categories & Bone List
    - These have been combined and put in to the Ktisis Workspace.
    - To see the overlay for a particular character, expand the tree and click the eye to the left of pose.
    - You can then optionally toggle particular bone categories on and off.
    - Expanding a given tree will show you the children of that particular node allowing you to see the relations of the bones.
- Import & Export
    - You can Import or export a pose by the right click context menu mentioned above for 'Character (.chara)' importing, or in the object editor under the 'Pose' dropdown.
- Advanced (Debug)
    - Most of these features have been carried over under the Object editors Pose dropdown.

### Camera tab

- Add Camera, Work Camera, and Camera Select
    - These can now be accessed in the main Ktisis workspace below the top row of buttons.
- Camera Editor
    - Beside the add new camera and work camera buttons is the :fontawesome-solid-pencil: button to open the camera editor.

### World tab

The World tab has been replaced with the much more robust Environment Editor, accessible by the :fontawesome-solid-sun: button.

### Options

Keep in mind not all options will have a direct recplacement, since we rebuilt v3 from the ground up not all of them were needed.

- Interface
    - Open Ktisis: Ktisis now automatically opens when you open Gpose
    - Hide character name: is now under General :fontawesome-solid-arrow-right: Incognito Mode
    - Censor NSFW: the default is to censor NSFW bones, and can be toggled under General :fontawesome-solid-arrow-right: Display NSFW bones
- Overlay
    - Skeleton Lines and dots has moved to Personalize :fontawesome-solid-arrow-right: Overlay
    - Bone colors is under Personalize
    - Edit bone positions moved to Personalize :fontawesome-solid-arrow-right: Bone Offsets
- Input
    - Now called Inputs
- Camera
    - All settings are now under Inputs :fontawesome-solid-arrow-right: Camera
- AutoSave
    - Now under General :fontawesome-solid-arrow-right: Auto Save
- References
    - Reference images can now be added through the workspace spawn menu, instead of the settings screen.

## Whats new?

### Ktisis Toolbar
If you're migrating from v2 (otherwise why would you be reading this?), you may find the Ktisis toolbar more comfortable for your workflow, it condenses multiple windows in to one central window reminescent of v2's layout.

### Environment Editor
The Environment editor has been expanded significantly to include more in depth Sky editing, Lights, Fog, Rain, numerous particle effects, Stars, Wind, Water, and Housing light control.

### Advanced Lighting controls
Gpose lights can now be made and edited in far more detail than was possible in v2.

### Inverse Kinematics
Ktisis v3 has added Inverse Kinematics for controlling your arms, legs, tail (if applicable), and male genitals (if applicable), letting you have much more natural control over your characters movements while posing.

