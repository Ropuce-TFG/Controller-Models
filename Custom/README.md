File paths are as follows:

FCStd files, to be opened with FreeCAD 1.1 or later:
- `/Custom/ModuleParts.FCStd` contains the individual module parts
- `/Custom/ControllerModules.FCStd` contains the assembled module shells
- `/Custom/ControllerShell.FCStd` contains the controller's shell, along with a separate model for handles

Folders containing ready-to-print STL files are for each of the modules and the main shell, as the name indicates.
`/Custom/Trigger Module v1/` contains a design error and was only kept for reference
`/Custom/Joystick Module v1/` is functional, difference being the orientation of the joystick and an extra hole on one of its sides allowing the use of unmodified joysticks (using it this way will prevent insertion into the controller's shell)
The `/Custom/Reference/` folder contains reference models for components used within custom models


These files have been printed with a Bambu Lab H2D printer, using PETG filament with a 0.4mm extruder.
Smaller pieces were printed with a 2mm outer and inner brim set to 0mm brim-object gap.
For supports, all supports were printed from the build plate using tree(auto) type and no small overhangs.
For sparse infill, Gyroid was used on most pieces, while triangles or rectilinear were used on various reprints of the buttons, yielding similar results
