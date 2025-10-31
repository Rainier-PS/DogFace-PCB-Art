# DogFace PCB Art Keychain

DogFace is a custom dog-shaped PCB art keychain that lights up, vibrates, and reacts to button presses. This project is built around fun, interactivity, and portability — all packed into a single board you can hang on your bag, keys, or lanyard.

---

## Features

- 2 LEDs as glowing eyes
- 3 buttons:
  - Left eye control
  - Right eye control
  - Mouth "bark" via vibration motor
- 1 potentiometer to control LED brightness
- 1 capacitor to protect the motor circuit
- 5.3 mm keychain hole for easy attachment

---

## Bill of Materials (BoM)

| Component                      | Quantity         | Notes                                       |
|-------------------------------|------------------|---------------------------------------------|
| 5mm LED                       | 2                | Eyes                                        |
| Tactile Pushbutton (THT)      | 3                | Left eye, right eye, motor trigger          |
| Vibration Motor               | 1                | Tongue effect / "bark" vibration            |
| Potentiometer                 | 1                | LED brightness control                      |
| Capacitor                     | 1                | Motor protection (flyback damping)          |
| Resistors                     | 2                | Current limiting                            |
| Custom-shaped PCB             | 1                | Fabricated from this repo’s Gerber files    |
| Breadboard (for testing)      | 1                | For final circuit checks before soldering   |
| Jumper wires (male–male)      | 10               | For temporary connections on breadboard     |

---

## Note on Breadboard and Jumper Wires

Although this is a custom PCB project, I would like to include 1 breadboard and 10 male-to-male jumper wires in the kit to:

- Validate the full circuit functionality before soldering
- Test component behavior such as the motor, potentiometer, and transistor
- Ensure everything works as expected before committing to assembly

This is especially helpful since this is my first PCB project using KiCad.

---

## Screenshots

### Schematic  
![Schematic](images/Schematics.avif)
![Schematic](images/Simulation.avif)

### PCB Layout  
![PCB Layout](images/PCB.avif)

### 3D View  
![3D View](images/3D%20Model.avif)
![3D View](images/3D%20Model-Back.avif)

---

## Files Included

- `/images/`: Schematic, layout, and 3D preview images
- `/production/`: Gerber and drill files ready for manufacturing
- `/PCB/`: KiCad Schematics and PCB Design
- This `README.md`

---

## Slack Username

`@Rainier P.S.`

---

## Reflections

This is my first-ever PCB project, and I built it completely in KiCad. I challenged myself to combine functionality with personality by making a usable and fun keychain circuit.

### What I Learned

- Creating expressive PCB art using DXF outlines
- Designing within tight space constraints

### Challenges

- Fitting all components onto the face without breaking the aesthetic
- Creating custom PCB designs using DXF outlines

