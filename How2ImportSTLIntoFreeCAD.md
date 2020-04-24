# Simple How-To to import STL files from OpenScad into FreeCad

1. open freecad and create new empty document *File -> "New"* or **CTRL+N**
2. import stl with *File -> "Import"* or **CTRL+I**
3. switch to workbench *"Part"* from the central pulldown window
4. mark imported stl in the *"Labels & Attributes"* side window
5. Open *Part* and select *"Create shape from mesh"* and press OK with the preset
6. Delete the imported mesh; mark the stl in *"Labels & Attributes"* and press the DEL key
7. mark the new part and open the shape builder with *Part -> "shape builder"*
8. select in the pop-up-window *"Solid from shell"* and select the model. Press *Create*. Press *Close*.
9. Delete the old part which is **not** named solid.

