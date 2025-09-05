# fnaf-ControlPanel
The multiplayer companion to the FNAF: Task Terminal. As a second player, use this control panel to trigger real-time ads and jumpscares on the main player's screen. This fan-made project uses HTML, CSS, and Socket.IO to create a live, interactive.
FNAF: Multiplayer Animatronic Control Panel
The official companion web app to the FNAF: Task Terminal simulation, allowing a second player to act as the animatronic and trigger real-time events.

This project is the multiplayer component for the FNAF Task Terminal. It provides a simple, retro-themed interface for another player to send commands—like pop-up ads and jumpscares—to the terminal user, creating a dynamic and interactive experience between two players over the internet.

About The Project
This control panel was built to turn the FNAF: Task Terminal simulation into a live, two-player game. The goal was to create a simple but effective interface for an "antagonist" player, using WebSockets (via Socket.IO) to send real-time commands and directly impact the terminal user's gameplay.

Features
Real-Time Multiplayer: Connects to a central server to send live commands to the main Task Terminal.

Event Triggers: Buttons to activate specific in-game events, such as annoying ad pop-ups and jumpscares.

Retro Interface: Styled with a matching CRT aesthetic using the 'VT323' font to feel like part of the same universe as the terminal.

Simple & Effective: A clean, straightforward control panel focused entirely on player interaction.

Built With
HTML5

CSS3

JavaScript (Vanilla)

Socket.IO Client

(Connects to a Node.js / Express / Socket.IO server)

How To Use
To use this control panel, the full game setup is required:

Ensure the companion server is running online (e.g., on Replit).

The first player must have the FNAF: Task Terminal open in their browser.

The second player opens this animatronics.html file in a separate browser (this can be on a different computer anywhere in the world).

Click the buttons on the control panel to trigger events on the first player's screen in real-time.

Acknowledgements
This is a fan-made project and a companion to the FNAF: Task Terminal simulation.

Based on the game Five Nights at Freddy's: Pizzeria Simulator by Scott Cawthon.

Font: 'VT323' from Google Fonts.
