# BotMan
A small animatronic desktop robot based on [YouTube Video](https://www.youtube.com/watch?v=FmKTiH5Lca4) found on the 稚晖君 channel.

![The inspiration for this project](https://raw.githubusercontent.com/BampyBampy/BotMan/main/Images/Inspiration.jpg)

Although the channel provides some CAD drawings and a quick build video in Mandarin, it is incomplete or some elements may have been lost during the automated translations. So I will be designing and building my version from scratch (using their design as a template). There are other reasons for doing this including;

1. The main reason is this is a learning experience for me. I have never designed a robot before, I have never used CAD and I have limited experience with Arduino and 3D printing.
2. The components I have available to me will be different to theirs, so most of the dimensions and design would need tweaking anyway.
3. I don't have the facilities to produce my own circuit boards, so my design will need to be based on Arduino (or similar)
4. I intend to swap the static base for a wheeled base to allow my bot to move around the desk. This will need incorporating into the main design.

## The Design Build Order
1. **The arms** - I have chosen to develop these first because they are the most complex part of the physical design. They need 2 DOF in the same shoulder joint. (See The Specs below)
2. **The body** - This cant be designed until I have completed arm mechanisms to house. The interface to the head and base will need to be incorporated into the design of the body.
3. **The head**
4. **The base**
5. **The software** - As a VBA and Python developer, this part worries me the least and will be developed last.

## The Specs (Outline)
1. **The arms**
   - 2 Degrees of movement (1) Rotating from pointing down to pointing straight up. (2) Flapping in and out
   - Act as an input device. i.e. Physically moving the right arm up could increase the sound volume
   - Will not be able to pick anything up. Arms are animatronic only
3. **The body**
   - Will house the arm mechanisms
   - Will house the servo that will turn the body left and right relative to the stand
   - May house the voice recognition microphone
   - May house touch sensors on the belly and back to act as inputs
   - May have LEDs to make the belly glow
5. **The head**
   - Will have 2 degrees of movement (1) Up and down, i.e. nodding (2) Left and right, i.e. head shaking
   - Will house the display screen
   - May house the voice recognition microphone
   - May house touch sensors on the top to act as inputs
7. **The base**
   - Temporary static base while the software is developed
   - May contain a speaker, LED indicators, and various ports to connect to the outside world
9. **The software**
   - All joints to have smooth servo controls (remove jerkiness)
   - Voice recognition
   - Voice synthesis 
   - Interface with other computers in the room over wifi so it can send and receive instructions
   - Needs a low-battery detector
11. **Alternative bases**
    - Investigate different wheeled designs
    - Needs to be able to stop before falling off the edge of the desk
