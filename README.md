# DogFace PCB Art Keychain

This is a custom PCB art project shaped like a dog's face! It’s not just cute — it’s interactive too. The keychain lights up, vibrates, and responds to button presses.

## Features
- 2 LEDs as glowing eyes
- 3 buttons:
  - Left eye control
  - Right eye control
  - Vibration motor trigger (tongue effect)
- 1 potentiometer (brightness control for eyes)
- 1 NPN transistor for safely switching the motor
- 1 capacitor for motor protection
- 1 keychain hole (5.3mm) for attaching to bags or lanyards

---

## Bill of Materials (BoM)

| Component                      | Quantity | Notes                                       |
|-------------------------------|----------|---------------------------------------------|
| 5mm Red LED                   | 2        | Eyes                                        |
| Tactile Pushbutton (THT)      | 3        | Left eye, right eye, motor trigger          |
| Vibration Motor (3V)          | 1        | Mouth/tongue effect                         |
| Potentiometer – Bourns 3362P  | 1        | Controls brightness of LEDs                 |
| Capacitor (Electrolytic, 100µF)| 1       | Protects motor circuit (flyback damping)    |
| **NPN Transistor (e.g., 2N2222)** | 1     | Switches the vibration motor                |
| Resistors                     | 3–4      | Current limiters & transistor base resistor |
| PCB with custom dog shape     | 1        | Fabricated from this repo’s Gerbers         |

---

## Screenshots

### Schematic  
![Schematic](./screenshots/schematic.png)

### PCB Layout  
![PCB Layout](./screenshots/pcb_layout.png)

### 3D View  
![3D View](./screenshots/3d_view.png)

---

## Files Included

- **`/screenshots`**: Contains schematic, layout, and 3D view images.
- **`/gerbers`**: Includes all Gerber and drill files for PCB fabrication.
- **`.kicad_pcb` and `.kicad_sch`**: KiCad design files for editing or viewing the board.

---

## Slack Username  
`@your-slack-username`

---

## Reflections

This is my first PCB project using KiCad!  
I learned a lot about:
- Using a transistor to control motors
- Making PCBs both functional *and* fun
- Creating a custom shape with DXF + Edge.Cuts
- Handling motor protection and power safely

### Challenges
- Exporting a custom layout to the KiCad PCB editor
- Fitting components without ruining the dog’s facial layout
 
### Advice
Start with a sketch, then plan your circuit around the art — not the other way around!  
And always check your clearances before placing mounting/keychain holes.
