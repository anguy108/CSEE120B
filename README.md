Final Project Repository

Alan Nguyen

Summer 2017

University of California, Riverside

Description:

My custom project for my embedded systems class is a jukebox that was programmed using the ATMEGA1284 Microcontroller and Atmel Studio 7.0 in C. The jukebox plays 3 pre-programmed songs from 3 assigned buttons (Zelda, Star Wars, and Pac-Man), displays them on a 16x2 LCD display, and stops any playing song once a separate stop button is pressed. In addition, 7 green LEDs are an added feature that reacts to each note played through the speaker. 

YOUTUBE DEMO VIDEO URL: https://youtu.be/KT8hCAkkNOo

CONTROLS: 

(1)  To play a song, press Buttons A0, A1, or A2.

(2)  To stop playing the song, press Button A3.

PARTS:

(1)  ATMEGA1284-PU Microcontroller (running at 5V)

(1)  16x2 LED Display (to display start menu and songs being played)

(1)  Speaker (to play the sounds of each song)

(2)  10kOhm Potentiometers (to adjust LCD pixel brightness, LED )

(4)  Push-Buttons (3 for song selection, 1 to stop songs)

(7)  5mm LED GREEN (bonus feature that reacts to music playing)

BUILD/PINOUT:

Inputs: Pin A0 and Button A0 plays Pac-Man, Pin A1 and Button A1 plays Zelda, Pin A2 and Button A2 plays Star Wars. Pin A3 and Button A3 stops any song currently playing.

Outputs: PORT B, Pin B6 sends pulses to the speaker to play the sounds and light up the LEDs. PORTS C0-C7 and D6-D7 are used for LCD display power, control, and data lines.
