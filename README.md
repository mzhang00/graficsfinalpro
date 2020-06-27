# graficsfinalpro

Michael Zhang (Period 5)

## features
### Existing, MDL Commands/Features
- Mesh ``` mesh filename ```
  - Use an external .obj file for polygons
  - Make sure you deal with .obj files that list quadrilateral faces instead of triangles in some way
- Save Coordinate System ``` save_coord_system name ```
  - Save a copy of the top of the stack to the symbol table
  - Use this coordinate system when drawing shapes (extra argument required)

### New Primitive Shapes
- Cone ``` cone x y z radius height ```
- Pyramid ``` pyramid x y z side-length height ```
- Cylinder ``` cylinder x y z radius height ```
- Triangular Prism ``` triangularprism x0 y0 z0 x1 y1 z1 ```
