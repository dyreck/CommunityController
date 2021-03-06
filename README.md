# What even is this?

Glad you asked! Community Controller aims to bring a 24/7 interactive stream to your favorite platforms! So kick back, relax, and take control! Starting with Twitch Plays Nintendo Switch!

## Controls

All of the main switch buttons can be typed out in chat and work as a control.
```
A / B/ X / Y
UP / DOWN / LEFT / RIGHT
Move forward / back / left / right
Adjust Forward / Backward / Left / Right
L3 (left stick click)
R3 (right stick click)
LT (left trigger)
LB (left bumper)
RT (right trigger)
RB (right bumper)
Look Left / right / up / down
```

### Custom commands

Thanks to the work of one of our community members(fazzfadf), we now support the use of custom commands in chat, that should allow you to circumvent any/all situations that the main controls make difficult!



```
Syntaxes :
    custom(button)
    custom(button; duration)
    custom([button; button2; ...])
    custom([button; button2; ...]; duration

    Please note that in these custom commands you use a semicolon(;) as a separator and not the usual comma(,)

Duration :
decimals between 0 (strictly greater) and 1
when duration is not specified or invalid, it lasts 0.02 second

Examples:
  custom(lup; 1.0) #holds up on left stick for 1 second
  custom([lup; x]) #presses up on left stick and X at the same time
  custom([lup; x]; 0.5) #holds up on left stick and X for half a second

Available Buttons:
A, B, X, Y

l, lb #L on joycon

r, rb #R on joycon

zl, lt #zl/left trigger on joycon

zr, rt #zr/right trigger on joycon

lclick, l3 #presses left stick

rclick, r3 #presses right stick

lup, ldown, lleft, lright #left stick movement

rup, rdown, rleft, rright #right stick movement

dup, ddown, dleft, dright, #dpad

wait #does nothing for the specified time

```

# Game Specific Commands

* **Super Mario Odyssey**
    * Capture (Throws Cappy)
    * Ground Pound
    * Crouch
    * Backflip
    * Long jump
    * Swim
    * Dive
    * Flick up
* **Kirby Star Allies**
    * Attack
    * BFF
    * Dash Kick
    * Drop Ability
    * Suck
        * Succ
    * Swallow
* **Skyrim**
    * Activate
    * Sneak
    * Shout
    * Character Menu
    * Menu
    * Wait
    * Rear
    * Ready
* **The legend of Zelda: Breath of the wild**
    * Onward (Allows Link to walk forever until you tell him to stop)
        * Stop  (Stops link from walking)
        * Still (stops Link from walking)
    * Run (Makes Link run)
    * Hop
        * Hop left
        * Hop right
        * Hop down
        * Hop up
        * Hop back
        * Hop backward
    * Attack
        * Bash (quick attack for when Link is catching his breath)
    * Climb
    * Focus
    * Sheikah slate
    * Previous rune
    * Last rune
    * Previous shield
    * Last shield
    * Previous arrow
    * Last arrow
    * Previous weapon
    * Last weapon
    * Next rune
    * Next shield
    * Next arrow
    * Next weapon
    * Shoot arrow
    * Draw arrow
    * Use rune
    * Shield
    * Block
    * Crouch
    * Glide
* **Donkey Kong: Tropical Freeze**
    * Kong Pow
        * Pow
        * KP
    * Grab
    * Throw
    * Pluck
    * Combine
    * Dismount
    * Roll attack
    * Attack
    * Corkscrew
    * Swim
    * Keep Hold ZL (holds ZL forever)
    * Release ZL   (undos aforementioned hold ZL command)
* **Splatoon 2**
    * Keep Hold ZL (holds ZL forever)
    * Release ZL   (undos aforementioned hold ZL command)
* **A Link to the past**
    * Walk Direction (Makes link walk in the specified direction until told to stop)
    * Look Direction (Makes link turn without moving)
    * Stand Still (makes link stop walking)
    * Stop walking (makes link stop walking)
    * Stop (makes link stop walking)
    * Still (makes link stop walking)
    * Spin Attack
* **Xenoblade Chronicles 2**
    * Toggle map (toggles teh minimap zoom)
    * Zoom map (same as above)
    * target (locks onto the enemy)
    * engage (locks onto the enemy and also initiates combat)
    * menu (pauses the game)
    * system (brings up the system menu to allow for game saving and setting adjustment)
    * travel (Brings up the skip travel menu which lets you fast travel)
