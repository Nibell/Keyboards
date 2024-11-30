
# Micropad 4x4 Keyboard

![Micropad 4x4](https://raw.githubusercontent.com/Nibell/Keyboards/refs/heads/main/micropad4x4/images/micorpad4x4.jpg)

Welcome to the **Micropad 4x4 Keyboard** repository! This project features a compact, customizable 4x4 micropad designed for enthusiasts who love experimenting with custom keyboards. Whether you're a productivity junkie, a gamer, or just someone who wants a personalized input device, this macropad is perfect for you.

---

## Features

- **Compact Design**: A 4x4 grid for 16 keys, perfect for shortcuts, macros, or gaming inputs.
- **Customizable Firmware**: Fully programmable using popular firmware like [QMK](https://qmk.fm/) or [VIA](https://usevia.app/).
- **Ease of Assembly**: Designed with hobbyists in mind; the build process is straightforward.
- **Versatile Use Cases**: Ideal for productivity software, video editing, music production, or gaming.
- **Open Source Hardware**: Modify the design to suit your specific needs.

---

## Repository Structure

- **`~`**: Contains the PCB design files for the Micropad 4x4.
- **`Production`**: Gerber and production files.
- **`Images`**: Renderings and photos of the completed macropad.

---

## Getting Started

### 1. Clone the Repository

To get started, clone the repository to your local machine:

```bash
git clone https://github.com/Nibell/Keyboards.git
cd Keyboards/micropad4x4
```

### 2. Gather Components

You’ll need:

- **PCB**: Fabricate the PCB using the provided Gerber files.
- **Microcontroller**: Raspberry Pi Pico.
- **Switches**: 16 mechanical switches of your choice.
- **Keycaps**: A 4x4 set.

### 3. Flash Firmware

- Install [QMK Firmware](https://docs.qmk.fm/#/newbs).
- Build and flash the firmware for your microcontroller:

  ```bash
  qmk compile -kb nibell/micropad4x4 -km default
  qmk flash -kb nibell/micropad4x4 -km default
  ```
