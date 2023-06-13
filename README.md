# Joystick PCB

PCB Joystick for your nrf Arduino robot

![IMG_20230426_170745](https://github.com/m112521/pcb/assets/85460283/826f48f7-1a43-4177-9969-16ad2d988945)


Plan:

- [ ] EasyEDA sign up
- [ ] Add components and connect them in Schematics mode
- [ ] Convert Shematics to PCB (Design > Convert Shematic to PCB)
- [ ] Autotrace
- [ ] Fix traces manually: chamfer right angles, delete unused Arduino pins to free more space for traces
- [ ] Hole diameter: 1mm - 
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

![pcb](https://github.com/m112521/pcb/assets/85460283/a745d556-1e42-4107-becb-5a0002518586)


2D PCB view:

![shematics](https://github.com/m112521/pcb/assets/85460283/1436aeb1-3427-4f6b-8a84-397dc872172c)


3D PCB view:

![3d view](https://github.com/m112521/pcb/assets/85460283/ae97b797-5cba-45ce-8df0-d77fc477756e)


FlatCAM:

![FlatCAM PCB Routes](https://user-images.githubusercontent.com/85460283/205966377-132faa76-0e25-4de6-9859-f1142f044101.PNG)

Button PCB:

![pcb](https://github.com/m112521/pcb/assets/85460283/a768cf65-500e-4603-92ea-43ca51a2827b)

