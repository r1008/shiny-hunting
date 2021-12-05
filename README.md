# Pokemon Brilliant Diamond Shiny Starter Hunter

Automatically soft resets for a starter Pokemon, using an Arduino UNO R3 to emulate a controller.

---

LUFA has been included as a git submodule, so cloning the repo like this:

```
git clone --recursive https://github.com/r1008/shiny-hunting.git
```

will put LUFA in the right directory.

1. In the `shiny-hunting` directory, type `make` to compile.

2. Flash `Joystick.hex` onto your Arduino UNO R3. Instructions on how to do this can be found here: https://www.arduino.cc/en/Hacking/DFUProgramming8U2

#### Notes

- The steps begin from the controller - change Grip/Order page
- After the battle begins, there is a ~10s pause for the home button to be manually triggered
