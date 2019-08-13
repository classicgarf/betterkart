# BetterKart

This is the documentation for the config. I made this to be a quality way to play Garfield Kart with a controller until the devs add true support. Made because the top config used to shut off your computer.

## How to get it

This config is only available through Steam at the moment.

1. Enter Steam [Big Picture mode](https://support.steampowered.com/kb_article.php?ref=5006-ASLN-3202)
2. Go to your library, and find Garfield Kart
3. Choose the "Manage Game" option on the left side
4. Make sure that "Steam Input Per-Game Setting" is set to "Forced On" in the Controller Options menu
5. Select Controller Configuration at the very top
6. "BROWSE CONFIGS" with the button at the bottom
7. In the community section, find BetterKart by Commenter and click it
8. Apply configuration!

## How to use it

There are two modes for BetterKart, which you can switch between using the select button.

### Gameplay mode

Gameplay mode simply acts like a normal controller. When in this mode, the cursor will be placed in the bottom right corner automatically to keep it out of the way. The controls should be the same as shown in the tutorial, unless you changed them in the launcher when you start the game.

#### Default controls

This config is intended to be used with the default controls, but you can set it to whatever you want if you choose. If you changed the controls in the Unity launcher before and wish to reset them, this section will show how.

If you're on Windows, you can follow these steps to reset the controls. I don't know how to do this for Mac or Linux.

1. Press the Windows key and R at the same time
2. Type "regedit.exe" and run it
3. In the bar at the top, paste `Computer\HKEY_CURRENT_USER\Software\Anuman Interactive\Garfield Kart` in and press enter
4. Click the first result that starts with "__Input Key", then scroll down to the last one and click it while holding shift
5. If all of the Input results are selected, then right click and delete them.
6. Restart Garfield Kart, and the controls should be default.

If you don't use Windows, or simply need it, here's a list of the default controls copied from the game.

| Control                  | Primary            | Secondary         |
| ------------------------ | ------------------ | ----------------- |
| Turn right (Digital)     | right              |                   |
| Turn left (Digital) (+)  |                    |                   |
| Turn left (Digital) (-)  | left               |                   |
| Turn Right (Analog)      | Joystick 0 axis 0  |                   |
| Turn Left (Analog)       | Joystick 0 axis 0  |                   |
| Accelerate (Digital)     | up                 |                   |
| Brake (Digital)          | down               |                   |
| Accelerate (Analog)      | Joystick 0 axis 2  |                   |
| Brake (Analog)           | Joystick 0 axis 2  |                   |
| Drift (Digital)          | space              | joystick button 0 |
| Shoot forward (Digital)  | x                  | joystick button 2 |
| Shoot backward (Digital) | left alt           | joystick button 1 |
| Pause (Digital)          | escape             | joystick button 7 |
| Respawn (debug)          | r                  | joystick button 6 |

### Menus mode

Menus mode disables driving controls, and allows mouse movement. The two joysticks control the mouse, with the left going faster than the right. As a bonus, you can control volume with the D-pad. Here's a table of the controls.

| Control                  | Primary             | Secondary            |
| ------------------------ | ------------------- | -------------------- |
| Left mouse click         | Right trigger       | A button             |
| Right mouse click        | Left trigger        |                      |
| Escape key/go back       | B button            | Start button         |
| Mouse movement           | Left joystick       | Right joystick       |
| Keyboard typing          | Left joystick click | Right joystick click |
| Volume control w/ D-pad  | Up & down buttons   | Side buttons to mute |
