# dash-editor

12v power is required for all operations including layout update!


[Download DashEditor57d.rar](https://github.com/rusefi/chicago-dash-docs/raw/refs/heads/main/dash-editor/DashEditor57d.rar)

Main screen of editor shows screen layout. 
Screen layout consists of up to 10 different pages.
Each page consists any reasonable count of 10 types of visual primitives. Visual primitives are controlled according to "Logic" formulas. We also have amazing "debug" window allowing to set virtual inputs while we are playing with editor.


Let's start from default project which comes as part of editor distribution file.
"File->Open Project" DashEditor\System\scr.txt


Here we have some groups and top level primitives.

![image](https://github.com/user-attachments/assets/fcfb8bf1-04d6-4ecf-99b9-2ae983324e34)


Double-click on left column icon to edit primitive or open group.

Second column (for instance HI/LO on the screenshot) shows current value as rendered on the right according to current state of DEBUG.



Click top bar menu "Add" to add additional visual primitive.

## Visual Primitives

### Text

Static text

### Digt

Text control displaying live numeric value


### Rectangle

Invisible when disabled/display rectangle of selected style when enabled.

### Pictogram

Single color. Two states: visible or not visible.


### Fundamental Logic Concepts 

Do not ask why, but "HI" means "Always logical High"

### Digital Input

DI

## Logic

Open LogicEdit

hit 'CAN1_RX'

hit 'Add'

Channel name always start with '@' that would make it a variable



## Upload new layout

* 12v power
* USB
* copy "System" folder
* IMPORTANT: in windows use "Safely Remove"
* five finger tap to enter menu 
* Engineering
* tap and hold 'Update project' for three seconds
* power cycle once process is complete

