
## AutoPresetUI.tox

![](https://i.imgur.com/Lalf4Pj.png)

Reworked version of Keith Lostracco's great little preset UI component that auto populates based on a page of custom parameters. Slightly bodgy, but currently supports int, float, toggle and menu parameters.

Instructions:
- Point the Targetop parameter at whichever op you want presets for.
- Select which page of parameters to use
- Right click preset buttons to store preset
- Left click preset buttons to recall preset
- Right click title bar to edit preset names


Keith's original component:

http://www.derivative.ca/Forum/viewtopic.php?f=22&t=6582

## CHOPMapper

![](http://i.imgur.com/KAoYP1s.png)
Simple table driven component for quickly renaming and remapping ranges of CHOP channels. Optimised for efficiency (doesn't use exports and only cooks channels that are changing)

Handy for things like audio reactive systems where you have some  frequency values that you want to map to various different parameters of your network.

- Plug CHOP you want to map into in2
- Click "Create From CHOP"
- Click "Open Mapping Table" to set mapping values

Can also create from a DAT table if you want, just copy default mapping from inside, edit values, plug into in1 and click "Create From DAT"


## TimeMachine.tox
![](https://i.imgur.com/VVeDFN8.png)

Simple wrapper for doing slit scan effects with the TimeMachine TOP.





## CornerPinUI.tox

![](https://i.imgur.com/4gR7JYa.png)

An easy to use UI for extracting a subsection of an image. Useful for aligning simple kinect/camera tracking with a projection area.
- Left click to move corner points
- Middle click to store current state as preset
- Right click to recall preset

When finished, you can toggle Allowdestroy on and press Destroy UI to replace the component with a single Corner Pin TOP (not reversible)
