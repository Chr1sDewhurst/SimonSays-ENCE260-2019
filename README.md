# Embedded Systems Project - 2019

### Authors

- Christopher Dewhurst
- Alyssa Josephs

## Project Brief

The goal of this project was to create a 2-player game for the UC Fun Kit v4 (UCFK4), designed by Philipp Hof and Michael Hayes.

> The UCFK4 has an ATmega32u2 microcontroller, a reset push button, a general-purpose pushbutton, a five-way navigation switch, a green LED that indicates if power is on, a user switchable blue LED, a seven by five dot-matrix display, an infrared LED, a 36 kHz infrared receiver, and a USB connector. The USB connector provides 5 V to run the microcontroller and to allow programs to be up-loaded.

![UCFK4](https://github.com/Chr1sDewhurst/SimonSays-ENCE260-2019/blob/master/UCFK4.jpg)

A game is intitiated when a player pushes the black navigation button.
They become the active player and the other player becomes the non-active player.

After a short pause the active player is shown a direction:
U: Up
D: Down
L: Left
R: Right
P: Push

The active player must move the navigation button in the matching direction
before the character disappears. The player will be flashed five directions,
they must respond in time to all five correctly before the game play is
passed to player 2., the non-active player.

Play continues until an incorrect action is made. The active player will
be shown a losing screen and the non-active player to be shown winning screen.

Game can be restarted through the white button on the opposite side of
the LED matrix to the navigation button.
