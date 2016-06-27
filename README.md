# TouchDesignerComponents
Collection of .tox components

## TimeMachine.tox
Simple wrapper for doing slit scan effects with the TimeMachine TOP.

## AutoPresetUI.tox
Reworked version of Keith Lostracco's great little preset UI component that auto populates based on a page of custom parameters. Slightly bodgy, but currently supports int, float, toggle and menu parameters.

Instructions:
- Point the Targetop parameter at whichever op you want presets for.
- Select which page of parameters to use
- Right click preset buttons to store preset
- Left click preset buttons to recall preset
- Right click title bar to edit preset names


Keith's original component:

http://www.derivative.ca/Forum/viewtopic.php?f=22&t=6582


## CornerPinUI.tox
An easy to use UI for extracting a subsection of an image. Useful for aligning simple kinect/camera tracking with a projection area.
- Left click to move corner points
- Middle click to store current state as preset
- Right click to recall preset

When finished, you can toggle Allowdestroy on and press Destroy UI to replace the component with a single Corner Pin TOP (not reversible)
