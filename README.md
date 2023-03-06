# StarTraveler
Micropython "game" for micro:bit


* StarTravel.py - main code for Star Traveler
* universe.py - support code for Star Traveler
* StarTravel.hex - loadable hex code for micro:bit

Sort of a "fidget spinner" - to travel around a simulated cosmos.

* tilt left, up, down, right to make starfield scroll in different directions.
* A+B to stop motion (or "shake" in the simulator)
* A moves the starship indicator to the right, loops around when it hits right-most edge
* B moves the starship indicator down, loops around to the top when it hit bottom

When motion is stopped A+B (or "shake" in the simulator) displays name of the star system ship is on (IF there is a star there) and then pronounces it.
