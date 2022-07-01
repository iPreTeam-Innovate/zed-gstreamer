# Changes Made
- New Stream Type Added
  - stream-type=5 => It will give RGBD
  - stream-type=6 => It will give RGBDM, that is RGBD with Meta Data)

# Run
To get the 3D points forming a polygon bounds corresponding to the current visible limits of the plane, use the following tags
```
zedsrc stream-type=6 enable-positional-tracking=true measure3D-reference-frame=1
```
