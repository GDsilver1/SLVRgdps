SLVR GDPS — Web Port of Geometry Dash
SLVR GDPS (short for Silver Geometry Dash Private Server) is a browser‑based port of Geometry Dash built on top of BreadMod, with additional modifications, fixes, and features.
The goal is simple: a lightweight, fully client‑side GDPS that runs in basically any browser without plugins or installs.

This project is a modification of the public Geometry Dash web version (geometrydash.com) and adapts it into a customizable private‑server‑style environment.

What This Project Is
A web port of Geometry Dash

A modded version of BreadMod

A GDPS‑style client that runs entirely in HTML + JavaScript

A project meant for tinkering, learning, and experimenting

What This Project Is NOT
Not an official GD product

Not affiliated with RobTop

Not a full server backend (you can connect it to one, but it doesn’t ship with one)

Features
Works on all major browsers (Chrome, Firefox, Edge, Safari, etc.)

Uses only standard web tech (HTML, JS, Canvas)

BreadMod‑based, but with SLVR‑specific tweaks and improvements

Customizable assets, UI, and logic

Can be hosted anywhere (GitHub Pages, Netlify, local server, etc.)

Lightweight — no Unity, no Cocos2d, no external engine

Running the Project
Clone the repo
bash
git clone https://github.com/yourusername/slvr-gdps
cd slvr-gdps
Local testing
You can open index.html directly, but some browsers block local file access.
Using a tiny local server is easier:

bash
npx http-server .
Then open:

Code
http://localhost:8080
Project Layout
Code
/assets        → textures, icons, sounds
/scripts       → game logic, rendering, UI
/levels        → optional custom level data
index.html     → main entry point
config.js      → server URLs + settings
Customization
You can modify:

config.js — server endpoints, version strings, toggles

assets/ — swap textures, icons, SFX

scripts/ — gameplay logic, UI, menus, etc.

BreadMod’s structure is mostly preserved, so if you’ve modded that before, this will feel familiar.

Contributing
If you want to help improve SLVR GDPS:

Fork the repo

Make your changes

Submit a pull request

Bug reports and suggestions are welcome.

Credits
SLVR GDPS — modifications and web‑port adjustments

BreadMod — original web port foundation

RobTop Games — Geometry Dash

Community contributors

Disclaimer
This is an unofficial fan‑made project.
All Geometry Dash assets belong to their respective owners.
This project is for educational and experimental use.
