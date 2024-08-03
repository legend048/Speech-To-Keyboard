# SpeechToKeyboard Command List

This file provides a list of valid commands for SpeechToKeyboard along with instructions on how to use them.

## Understanding the Coordinate System

SpeechToKeyboard uses a pixel coordinate system to represent locations on your screen. The origin, (0, 0), is located at the top-left corner. The bottom-right corner has coordinates that match your screen's resolution, for example, (1920, 1080) or (1600, 900).

When using mouse commands with coordinates exceeding your screen's resolution, the movement will simply stop at the maximum allowed x or y value. Supplying negative integers as coordinates is not permitted.

## List of Commands

The following list details the available commands.

* #(...): Represents a non-negative integer to be provided by the user.
* (K#): Represents the name of a keyboard key to be entered by the user.
* [T]: Represents a list of words to be typed by the program.

### Mouse Commands

* **move to (#) (#)**: Moves the mouse to the point on the screen with coordinates (x, y).  
   Example: 'move to 400 600'
* **move up (#)**: Moves the mouse up by # pixels.
   Example: 'move up 400'
* **move down (#)**: Moves the mouse down by # pixels.
   Example: 'move down 400'
* **move left (#)**: Moves the mouse left by # pixels.
   Example: 'move left 400'
* **move right (#)**: Moves the mouse right by # pixels.
   Example: 'move right 400'
* **left click**: Clicks the left mouse button once at the current cursor location.
* **double click**: Clicks the left mouse button twice at the current cursor location.
* **right click**: Clicks the right mouse button once at the current cursor location.
* **middle click**: Clicks the middle mouse button once at the current cursor location.
* **hold left**: Holds down the left mouse button at the current cursor location.
* **hold right**: Holds down the right mouse button at the current cursor location.
* **hold middle**: Holds down the middle mouse button at the current cursor location.
* **release left**: Releases the left mouse button at the current cursor location.
* **release right**: Releases the right mouse button at the current cursor location.
* **release middle**: Releases the middle mouse button at the current cursor location.
* **scroll up (#)**: Scrolls the mouse up by # units (not pixels). The number of units scrolled may vary depending on your operating system.
   Example: 'scroll up 300'
* **scroll down (#)**: Scrolls the mouse down by # units (not pixels). The number of units scrolled may vary depending on your operating system.
   Example: 'scroll down 300'

### Keyboard Commands

* **press key (K#)**: Presses and releases the keyboard key (K#).
   Example: 'press key d'
* **hold key (K#)**: Holds down the keyboard key (K#).
   Example: 'hold key space'
* **release key (K#)**: Releases the keyboard key (K#).
   Example: 'release key backspace'
* **use shortcut (K1) (K2) (K3) ... (K#)**: Presses and holds keyboard keys (K1) through (K#) in order, then releases them in reverse order (simulates a keyboard shortcut).
   Example: 'use shortcut control c'
* **type this [T]** : Types the list of words [T].
   Example: 'type this hello world'

### Other Commands

* **quit program**: Terminates the SpeechToKeyboard program.
