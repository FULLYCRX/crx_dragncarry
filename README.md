# crx_dragncarry
A simple standalone FiveM script developed by I_AM_FULLYCRX that allows players to seamlessly drag or shoulder-carry other players via target interaction. Built with anti-glitch protection to prevent victims from breaking out of animations.

🚀 Features

Multi-Target Support: Primarily built for ox_target with compatibility hooks for qb-target and q-target.

Forced Action: Instantly starts the animation upon targeting—no confirmation prompt required for the victim.

Immersive Animations: Police/tactical style wounded officer drag.

Carry Animation: RPEmotes-Reborn's shoulder carry animation.

Seamless Controls: The host player retains full movement and directional control.

Smart Release Keys: Host can press Escape or Backspace to drop the player.

Anti-Pause Interruption: Pressing Escape while dragging/carrying will drop the player.

Anti-Glitch Protection: Victims have their movement, combat, and animation keys (like X or other keyboard shortcuts) entirely disabled. If they attempt to cancel using RPEmotes, the script instantly forces them back into the proper animation loop.

# Installation

Download the repository and extract the folder into your server's resources directory.
Ensure the folder is named exactly crx_dragncarry.
Open your server.cfg and add the following line:
```
ensure crx_dragncarry
```

Make sure this script starts after your target resource (ox_target, qb-target, etc.) and ox_lib.

Configuration: You can easily adjust animation offsets, disable specific keys, or tweak target labels directly inside the config.lua file.

# Credits
Created and maintained by I_AM_FULLYCRX / fullcrxstiano_7.

# Support
[I_AM_FULLYCRX Official Discord](https://discord.gg/6QchSKDY7j)
[Iron Justice Roleplay Official Discord](https://discord.gg/YJXZagSzh7)
