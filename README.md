# Joystick PCB


Plan:

- [ ] EasyEDA sign up
- [ ] Add components and connect them in Schematics mode
- [ ] Convert Shematics to PCB (Design > Convert Shematic to PCB)
- [ ] Autotrace
- [ ] Fix traces manually: chamfer right angles, delete unused Arduino pins to free more space for traces
- [ ] Convert to 
- [ ] Set trace width: ~0.6-0.9 mm
- [ ] Add text labels
- [ ] Screenshot 2D and 3D view (PCB mode: View > 3D view) 
- [ ] Download .dxf
- [ ] Clean vectors in CorelDraw/Rhino
- [ ] Draw joystick contour (vector)
- [ ] Add holes
- [ ] ArtCAM .gcode

Tools:

- V-bit 20/45 deg (trace isolation); 
- 0.8 mm (holes, cutout).


Software:

1. EasyEDA -> Gerber (or DXF).
2. FlatCAM -> G-code (or ArtCAM).


BOM:

- sensor;
- led;
- attiny;
- resistor;
- battery holder CR2032;
- switch.

Scematics:

![shematics](https://github.com/m112521/pcb/assets/85460283/fb95922a-a370-47f8-9642-5dcb0475bc85)


2D PCB view:

![shematics](https://github.com/m112521/pcb/assets/85460283/1436aeb1-3427-4f6b-8a84-397dc872172c)


3D PCB view:

![3d view](https://github.com/m112521/pcb/assets/85460283/ae97b797-5cba-45ce-8df0-d77fc477756e)


FlatCAM:

![FlatCAM PCB Routes](https://user-images.githubusercontent.com/85460283/205966377-132faa76-0e25-4de6-9859-f1142f044101.PNG)
