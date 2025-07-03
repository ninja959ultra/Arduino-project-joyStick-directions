# Arduino-project-joyStick-directions

# Description:
This project is a pattern-based challenge using an Arduino, a joystick module, two LEDs (red and blue), and a buzzer.

The user must enter a specific sequence of joystick movements to "unlock" the system. Each joystick direction is assigned a number:

Up → 1

Right → 2

Down → 3

Left → 4


Example target pattern stored in the code:

Right, Right, Left, Left → which translates to: 2, 2, 4, 4

---

If the entered pattern is correct:

The blue LED turns ON

The buzzer plays a short success tone

The system indicates a successful unlock

---

If the pattern is incorrect:

The red LED turns ON

The buzzer plays an error tone

The system indicates failure

---

This project demonstrates how to use a joystick as an input method to create a pattern-recognition system. It’s perfect for practicing input sequencing, logic validation, and user feedback mechanisms using basic Arduino components.


# Pictures:
![img1]()
