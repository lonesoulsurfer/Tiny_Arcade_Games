# Tiny Arcade: classic games on an ATtiny85

Tiny Arcade is a small handheld game console. It uses an ATtiny85 microcontroller and a small OLED screen. It plays classic arcade games, for example Frogger, Space Attack, Breakout and Snake.

![Tiny Arcade](https://github.com/user-attachments/assets/f0eabf16-461b-4714-9e4c-7d9401167a77)

This project is for beginners. You need basic soldering skills and a computer. All parts are through-hole and easy to buy.

## Build guide and video

- Step-by-step build guide on Instructables, with the parts list: [Tiny Arcade Game - ATtiny85](https://www.instructables.com/Tiny-Arcade-Game-Attiny85/)
- How to program an ATtiny85: the [ATtiny_85_Programmer](https://github.com/lonesoulsurfer/ATtiny_85_Programmer) repository
- Video on YouTube: [Tiny Arcade](https://www.youtube.com/watch?v=dKiPz_Yv8tA)

## The games

Each game is a separate sketch in `Tiny Arcade - Games/`. An ATtiny85 holds one game at a time.

| Sketch | Game | Author |
|--------|------|--------|
| `Bat_Bonanza_Tiny_Arcade` | Bat Bonanza (a Pong game) | Andy Jackson |
| `Breakout_Tiny_Arcade` | Breakout | Ilya Titov |
| `Frogger_Tiny_Arcade` | Frogger | Andy Jackson |
| `Run_Dude_Run_Tiny_Arcade` | Run Dude Run | Ilya Titov |
| `Snake_Tiny_Arcade` | Snake (UFO Escape) | Ilya Titov |
| `Space_Attack_Tiny_Arcade` | Space Attack | Andy Jackson |
| `UFO_Stacker_Tiny_Arcade` | UFO Stacker | Andy Jackson, Ilya Titov |

## What you need

### Hardware

- The parts list is in the [Instructables guide](https://www.instructables.com/Tiny-Arcade-Game-Attiny85/).
- The schematic is [Tiny Arcade - Schematic.png](Tiny%20Arcade%20-%20Schematic.png).
- The Gerber files for the PCB are in [Gerber File](Gerber%20File/). You can send them to a PCB maker.

### Software

- Arduino IDE, with ATtiny85 support
- A programmer for the ATtiny85

You do not need to install libraries.

## Program a game

The Instructables guide shows each step, with photos. In short:

1. Open the sketch of one game in the Arduino IDE.
2. Put the ATtiny85 in your programmer.
3. Set the board and programmer settings that the guide tells you.
4. Click **Sketch → Upload Using Programmer**.

> **Note:** Some games are almost too large for the ATtiny85. If the upload fails because the sketch is too big, see the note at the top of the sketch.

## Files in this repository

| Folder or file | Contents |
|----------------|----------|
| `Tiny Arcade - Games/` | One sketch for each game |
| `Eagle Files/` | Eagle files for the PCB |
| `Gerber File/` | Gerber files for the PCB, ready to order |
| `Tiny Arcade - Schematic.png` | Schematic |

![Tiny Arcade games](https://github.com/user-attachments/assets/271e3cb7-481f-4c2b-8820-7230813d4e10)

## Credits

- Games by Andy Jackson ([@andyhighnumber](https://twitter.com/andyhighnumber)) and Ilya Titov ([webboggles.com](http://webboggles.com/)).
- Screen and font code by Neven Boyanov, from the [Tinusaur](http://tinusaur.wordpress.com/) project.
- Sleep code based on a blog post by Matthew Little.
- PCB and build: Marcus ([lonesoulsurfer](https://github.com/lonesoulsurfer)).

## Support

Do you like this project? You can support my work on [GitHub Sponsors](https://github.com/sponsors/lonesoulsurfer).

## Licence

- **Hardware** (PCB, Gerber files and schematic): [CERN Open Hardware Licence v2, Strongly Reciprocal](LICENSE).
- **Game code:** the terms of the original authors. You may use it for **non-commercial** purposes only, and you must name the authors.
- [LICENSING.md](LICENSING.md) gives the details.
