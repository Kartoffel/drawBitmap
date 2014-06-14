drawBitmap
==========

OpenSCAD bitmap drawing module

### parameters
  - bits (array): Bitmap array
  - cubeSpacing (decimal)
  - cubeSize (decimal)

### Example usage
```
include <drawBitmap.scad>;
bits=[
  [1,0,0],
  [1,0,0],
  [1,1,1],
  [1,0,1],
  [1,1,1]
];

cubeSize = 4;
cubeSpacing = 5;

drawBitmap(bits, cubeSpacing, cubeSize);
```
