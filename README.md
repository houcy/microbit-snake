# Micro:bit Snake game

This repository contains the code for the [Build snake on the BBC micro:bit tutorial](https://www.cameronmacleod.com/blog/microbit-snake). The structure of the repository is as follows:

### skeleton.py

This is the starter code for the tutorial and contains the basic structure of the game.

### snake.py

This file contains the completed tutorial code. This can be flashed directly onto your micro:bit to play the game.

## Running the file on the micro:bit

You will need `python3` and `pip`.

Run the following in this directory with a micro:bit connected and mounted.

```
pip install uflash
uflash snake.py
```

Your micro:bit will then flash an orange LED for some time and reboot into the snake game code.

---

Alternatively, copy the code into the [Python micro:bit editor](https://python.microbit.org/v/2.0) and click "Download". You can then drag the downloaded `.hex` file to the micro:bit as if it was a USB flash drive.

## Running this as a workshop

Slides from this workshop as the Embedded and Robotics Society run it are available [here](https://docs.google.com/presentation/d/1d5NM7Sf5eOalQJ1Otfe1fJ4gtUMj3hgkXyFJPTEyZik/edit?usp=sharing).

The original [ears-edi repository is here](https://github.com/ears-edi/microbit-snake/).
