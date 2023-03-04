## 3D printing

**Hardware:**

For a start I would recommend a fully assembled device or at least a partially assembled 3d printer.
- What filaments you like to print? => hotend / heated bed temperature
- How big/small you like to print? => built area / printer type
- Do you need more than one color/filament? => amount of extruders
- Do you like to remove your print easy? => removable coated steel plate
- Do you like to see your printing process? => camera

****
**Software:**

* Blender 3D, OpenSCAD, ...
* Slicer (convert STL to G-Code)

****
**Tips/Hints:**

* Meshmixer has tree supports
* A good leveling and a heated bed with a coated steel plate are the most important things
* With no heated bed and/or a smooth plate a brim ist always a good choice for better adhesion and hairspray makes it even better

****
**Blender 2.8x (will be updated soon) Settings:**

* Scene Properties => Units => Unit System: Metric, Unit Scale: 0.001, Rotation: Degrees, Length: Millimeters
* Edit => Preferences... => 
  - Interface: "Splash Screen"
  - Add-ons: "3D View: Measureit", "Mesh: 3D Print Toolbox", "Mesh: LoopTools"
  - Navigation: "Orbit Around Selection", "Zoom To Mouse Position"
  - System: Cycles Render Device: CUDA if available
  - 3 Lines => Save Preferences
  - Vertices: Global


