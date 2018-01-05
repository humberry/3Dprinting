3D printing
===========

Hardware:<br />
<br />
* Controller / Board (e.g. MKS 1.x, Ramps, smoothieboard, ...)<br />
* Stepper motors (e.g. 0.9 or 1.8 degrees / NEMA 17 => holding torque per phase)<br />
* Extruder (e.g. bowden or direct => fast printing vs. flexible filament)<br />
* Hot end (nozzle size, filament size, full metal => max. temperature)<br />
* Heatbed (voltage 12V/24V/110V/230V => time to heat / max. temperature)<br />
* Power supply (w/o heat bed)<br />
* Temperature sensor<br />
* ...
<br />
Build guide:<br />
<br />
D-Bot Core-XY 3D Printer https://www.thingiverse.com/thing:1001065<br />
<br />
<br />
Software:<br />
<br />
* tinkercad, sketchup, blender, freecad, ...<br />
* Repetier (control your printer)<br />
* Slic3r (convert your 3d model into printer g-code)<br />
* ...<br />
<br />
Tips/Hints:<br />
<br />
* With a bigger nozzle you have to increase the temperature (e.g. +30°C) and/or slow down the print speed (e.g. -10mm/s).<br />
* PETG settings: 250°C, 80°C, 50mm/s, Retraction 2mm + 40mm/s, Extrusion Multiplier <1.0 and >0.9<br />
* Meshmixer has tree supports<br />
* Use Slic3r skirt option as a shield while printing with several hot ends (loops min. 3 recommended)<br />
* A brim ist always a good choice for better adhesion and hairspray makes it perfect<br />
<br />
Calibration:<br />
<br />
* Stepper motor current (motor/driver) / movement (https://www.prusaprinters.org/calculator/)<br />
* PID tuning (https://www.youtube.com/watch?v=APzJfYAgFkQ)<br />
* Bed leveling (https://www.youtube.com/watch?v=_BuuGswqWWE)<br />
<br />
Blender Settings:<br />
<br />
* Properties => Scene => Units => Length: Metric, Angle: Degrees, Unit Scale: 0.001<br />
* File => User Preferences => <br />
  Interface: "Rotate Around Selection", "Zoom To Mouse Position"<br />
  Add-ons: "3D View: Measureit", "Mesh: 3D Print Toolbox", "Mesh: LoopTools"<br />
  System: Cycles Compute Device: CUDA if available, Memory Cache Limit: 2048 (64bit)<br />
  => Save User Settings<br />
 <br />
