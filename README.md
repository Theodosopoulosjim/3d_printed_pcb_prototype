Workflow for creating prototype PCBs using 3D printing and copper tape.
Step 1: PCB Design (Sprint Layout)
Use Sprint Layout 6. Design PCB and export Gerber files (tested with single-layer).
Step 2: Import Gerber via ULP
In the PCB software environment:
- Go to Utilities (ULP) inside the PCB editor.
- Run the command: import-gerber.
- Double click the ULP script that appears.
- Select your Gerber files (or .kicad_pcb files).
- Click 'Import'.
The tool reloads and shows the imported layer.
Step 3: 3D Visualization
Switch to 3D PCB view using the board icon.
The PCB appears as geometry.
Step 4: Export 3D Model
Go to File → Export → Export as STL.
Export the PCB as STL.
Step 5: External Editing
Import STL into Blender, TinkerCAD, or similar.
Create a base slightly larger than PCB (e.g., 10x10 → 13x13).
Place traces on top and set height to ~3mm.
Step 6: 3D Printing
Slice and print.
~10% infill is sufficient.
Materials: PLA works, PETG/ABS preferred.
Step 7: Copper Tape Application
Apply adhesive copper tape.
Cut along trace outlines and remove excess.
Step 8: Drilling & Testing
Drill holes for components.
Better results on larger circuits; small traces risk shorts.
Notes:
- Best for prototyping before manufacturing.
- Larger boards improve reliability and probing access.
