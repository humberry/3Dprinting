## 3D printing


**Hardware:**

* Controller / Board (e.g. MKS 1.x, Ramps, smoothieboard, ...)
* Stepper motors (e.g. 0.9 or 1.8 degrees / NEMA 17 => holding torque per phase)
* Extruder (e.g. bowden or direct => fast printing vs. flexible filament)
* Hot end (nozzle size, filament size, full metal => max. temperature)
* Heatbed (voltage 12V/24V/110V/230V => time to heat / max. temperature)
* Power supply (w/o heat bed)
* Temperature sensor


**Build guide:**

* [D-Bot Core-XY 3D Printer](https://www.thingiverse.com/thing:1001065)


**Software:**

* tinkercad, sketchup, blender, freecad, ...
* Repetier (control your printer)
* Slic3r (convert your 3d model into printer g-code)


**Tips/Hints:**

* With a bigger nozzle you have to increase the temperature (e.g. +30°C) and/or slow down the print speed (e.g. -10mm/s).
* PETG settings: 250°C, 80°C, 50mm/s, Retraction 2mm + 40mm/s, Extrusion Multiplier <1.0 and >0.9
* Meshmixer has tree supports
* Use Slic3r skirt option as a shield while printing with several hot ends (loops min. 3 recommended)
* A brim ist always a good choice for better adhesion and hairspray makes it perfect


**Calibration:**

* [Stepper motor current (motor/driver) / movement](https://www.prusaprinters.org/calculator/)
* [PID tuning](https://www.youtube.com/watch?v=APzJfYAgFkQ)
* [Bed leveling](https://www.youtube.com/watch?v=_BuuGswqWWE)


**Blender Settings:**

* Properties => Scene => Units => Length: Metric, Angle: Degrees, Unit Scale: 0.001
* File => User Preferences => 
  Interface: "Rotate Around Selection", "Zoom To Mouse Position"
  Add-ons: "3D View: Measureit", "Mesh: 3D Print Toolbox", "Mesh: LoopTools"
  System: Cycles Compute Device: CUDA if available, Memory Cache Limit: 2048 (64bit)
  => Save User Settings
 
