## Hacky Bird - Made for Hackference 2017
### NB: I don't own the cats, dogs or trolls images

### Controls
- **W/S** Move Blue player Up/down
- **Up/Down** Move Red player Up/down
- **P** Pause (kind of - it stops walls being produced

Blue team simulated text inputs:
- **4** SLOW
- **5** FAST
- **6** FLASH
- **7** CATS
- **8** DOGS
- **9** TROLL

Red team simulated text inputs:
- **R** SLOW
- **T** FAST
- **Y** FLASH
- **U** CATS
- **I** DOGS
- **O** TROLL

### Description

At Hackference 2017 I made this game with @MohammedAlaboud and Matei Copot.
At the start of the game, we get everyone to text a number, then send texts back assigning them to the blue or red team and assigning one player of each team as captain. The captains come up to control the players in a simple game and the rest of the team can interfere by texting in key words. Every four seconds the most popular keyword is taken from each team's texts and the relevant action is applied to the game. The keywords are
- SLOW - slow down your walls
- FAST - speed up the opposite team's walls
- FLASH - distract the other team's player
- CATS/DOGS - change your player's background
- TROLL - distract your *own* team

This version of the game simulates incoming texts with keypresses so it can be played without the full text setup. The most popular is still taken each 4 seconds. In the text version we use nexmo as a text service.

Full code is here https://github.com/MohammedAlaboud/HackferenceProject (it is as messy as you woulld expect something made in 24 hours to be).
I had a lot of fun on this and very pleased with how it turned out :)
