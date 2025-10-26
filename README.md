# Project Title:  <ins> <i> Eco Runner </i> <ins> </ins>

# Table of Contents
1. [Controls](https://github.com/Zaif.K_Name/EcoRunner##Controls)

Simple overview of use/purpose:
 <b>Eco Runner is an educational adventure game designed to raise awareness about climate change and sustainability. Players take on the role of an environmental hero tasked with cleaning up pollution, restoring ecosystems, and promoting responsible behavior through interactive storytelling. </b>

<i> Every action counts. Eco Runner teaches players that small steps—like recycling or cleaning up waste—can lead to big environmental change. </i>

<p>The core mission of Eco Runner is to raise awareness about sustainability and climate action through immersive gameplay. Players navigate diverse environments—urban, forest, oceanic—each facing unique ecological challenges. By completing tasks such as cleaning up litter, recycling materials, and rehabilitating wildlife habitats, players learn that every action counts in the fight against climate change.</p>

## Description

<b> In Eco Runner, players explore diverse environments—from forests and oceans to urban landscapes—each facing unique ecological challenges. The game combines platforming, puzzle-solving, and resource management to teach players about climate change, recycling, and responsible living </b>

## Controls
<img width="631" height="190" alt="image" src="https://github.com/user-attachments/assets/f5421f9d-69fd-4221-85ca-b3f1da27d9d4" />

## Main Menu (Interactive Design) <b>Eco Runner</b>
<img width="987" height="555" alt="image" src="https://github.com/user-attachments/assets/49043d69-71cf-4ad2-b4b3-f739804366e2" />
<p>The main menu of <b>ECO RUNNER  </b> sets the tone for an immersive, environmentally conscious gaming experience. With its striking visual design and clear thematic messaging, it invites players into a world where sustainability and action go hand in hand.</p>
The menu offers three straightforward options in vibrant green text:

<b> PLAY</b> – Launches the game, signaling immediate engagement with eco-themed challenges.

<b>OPTIONS</b> – Allows players to customize settings, likely including controls, audio, and possibly eco-related gameplay modifiers. Although this hasn't been coded yet. 

<b> QUIT</b> – Exits the game, maintaining the minimalist and user-friendly interface. Whilst this has been coded this is only possible outside of Unity when the game has been fully developed. , <i>All these button uses SpatialMappingOcclusion</i> to achieve this desired effect.

## Why it Matters 
Eco Runner helps players understand that:

* Climate change is a shared responsibility

* Small actions can lead to meaningful impact

* Games can be a force for good

## Features

🪙 Coin Collection System
The coin mechanic serves as both a reward and a progression driver. Coins are strategically placed to encourage exploration and risk-taking, often positioned near hazards or on elevated platforms. Each coin collected contributes to the player's score and may unlock future upgrades or achievements. The floating animation and subtle glow effect make them visually enticing, while their placement subtly guides the player through optimal paths.

⏱️ Time Limit & Self-Destruct Mechanism
Each level is coded with a 90-second time window, adding urgency and pacing to the gameplay. If the player fails to reach the goal within this limit, a self-destruction sequence is triggered—whether through environmental collapse, character fade-out, or a thematic "nature rejection" effect. This mechanic reinforces the idea that action must be timely to preserve the ecosystem, aligning with the game’s environmental message.

⏸️ Resume/Pause Menu
The pause menu is clean and functional, allowing players to pause gameplay in real time with adherence to the physics of the game.

🧱 Spike Dodging & Level Progression
Progression to Level 2 requires precise movement and hazard avoidance. Spikes are placed as environmental threats that demand timing and spatial awareness. Their placement isn’t random—they’re designed to test the player’s mastery of jump arcs and platform spacing. Successfully dodging them not only unlocks the next level but reinforces the theme of navigating a damaged world with care and precision.

⚠️ Death Boundary
A coded death boundary ensures that falling off-screen or into designated danger zones results in instant failure. This mechanic maintains challenge integrity and prevents unintended exploration beyond the designed map. It’s a classic platformer feature, but here it’s framed as falling into ecological ruin—adding thematic weight to player failure.

🎥 Virtual Camera Follow
The game uses a virtual camera system that smoothly tracks the player’s movement across the tilemap. This dynamic follow ensures:

Consistent framing of the character

Visibility of upcoming terrain and hazards

A cinematic feel that enhances immersion The camera may also zoom or pan slightly during key moments (e.g., coin pickups, near-death escapes), adding polish and emotional impact.
## Spawn Entry:
 <img width="990" height="554" alt="image" src="https://github.com/user-attachments/assets/bbd19204-4064-48d0-b3da-5c56f84eeadc" />
<p>In designing the spawn environment for Eco Runner, I aimed to create a visually immersive and thematically rich entry point that immediately communicates the game’s ecological focus. The tilemap features layered grassy platforms with soft, organic edges, suggesting natural terrain rather than rigid, artificial structures. I used pixel textures that blend earthy tones—deep greens, muted browns, and mossy overlays—to evoke a sense of overgrowth and renewal. The background, with its silhouetted pine trees and twilight sky, adds depth and atmosphere, reinforcing the idea that the player is entering a forest in recovery. Every texture was chosen to feel hand-crafted and alive, from the flower crown on the character to the subtle shimmer of the coin, creating a world where nature is central and every detail supports the theme of restoration. My goal was to make the player feel grounded in a living ecosystem from the very first moment, where exploration and environmental impact are tightly intertwined.</p>


## Character Design & Storyline:
🌍 The Year is 2145. Earth is in Crisis.

The ice caps have melted. Sea levels have swallowed coastlines. Forests are fading into memory, and the air is thick with pollution. Humanity stands at a crossroads.

But one hero refuses to give up.

Meet Kai, a fearless climate defender armed with cutting-edge eco-tech and unstoppable courage. From the flooded ruins of old cities to the last surviving green zones, Kai battles the forces destroying our planet.


<img width="484" height="135" alt="image" src="https://github.com/user-attachments/assets/4118e7e2-5d48-42e2-91a0-741fe7cd34ee" />

<img width="126" height="146" alt="image" src="https://github.com/user-attachments/assets/c1f85c89-7b03-47bc-8a67-ece949341a97" />
<img width="503" height="244" alt="image" src="https://github.com/user-attachments/assets/28af92be-209e-4dcc-8083-8dfdb37ef16e" />

##Organisation of Files/Scripts/Assets: 
<img width="1240" height="213" alt="image" src="https://github.com/user-attachments/assets/2cd97d8f-c974-4478-932f-518e25aaa9f6" />
I’ve effectively incorporated free or credited assets (e.g. pixel art tiles, character sprites, UI icons) to build a cohesive visual style. These assets are integrated seamlessly into your game world, and their use is clearly acknowledged in your documentation. With the experimentation of various sprites and assets, I have continued to develop my game with a range of interactive features. Most of the files are organised and have been up to date whilst being commited to GitHub in regular intervals. 

## Developer Docuementation

## Tilemaps
Whilst this was effective in my game currently I have faced alot of issues that I have resolved with Tilemap slicing, editing and modification.
<img width="448" height="298" alt="image" src="https://github.com/user-attachments/assets/db3dad10-3e09-4d3c-80c0-c87b7cfc6d7e" /> <img width="448" height="298" alt="image" src="https://github.com/user-attachments/assets/6d6d3c1e-0ec4-47f4-80ac-3f82a99a433b" />

<p> Various tile palletes were used for this mostly from the Unity Asset store. The tilemaps in Eco Runner were crafted using a diverse mix of tile palettes, primarily sourced from the Unity Asset Store and supplemented by custom assets provided by my multimedia partner. This hybrid approach allowed for both consistency and creative flexibility—standardized tiles ensured smooth integration with Unity’s grid system, while bespoke textures added thematic depth and uniqueness to the game world. Grass platforms, mossy edges, and layered terrain were carefully selected to evoke a sense of natural regrowth, aligning with the game’s environmental message. Each tile was placed with intention, balancing visual appeal with gameplay clarity, and creating a world that feels both handcrafted and alive. This collaborative asset strategy not only streamlined development but also showcased my ability to integrate external resources into a cohesive, playable environment. The effect was used to mimick the mood and storyline of the game which is directly linked to the background and environment which the player navigates. </p>

<img width="1647" height="345" alt="image" src="https://github.com/user-attachments/assets/aea0a8d2-0039-436b-b6d3-b1ad73c1f02a" />


### Executing program

* How to run the program
* Step-by-step bullets

## UI/ Level Design
🧭 User Interface (UI)
Eco Runner features a clean, intuitive UI designed to support fast-paced platforming while reinforcing the game’s eco-conscious theme.

HUD Elements:

*Coin Counter (Top Left): Tracks collectible progress in real time.

Level Indicator (Top Right): Displays current stage for player orientation.

Time Tracker (Bottom Left): Shows countdown from 90 seconds, adding urgency to each run.

Pause/Resume Menu:

Accessible via keyboard or controller input.

Options include Resume, Restart Level, Settings, and Exit to Main Menu.

Designed with minimal distraction and fast navigation for younger players.

Visual Styling:

UI elements use green tones and organic shapes to reflect the game’s environmental theme.

Fonts are bold and readable, optimized for players aged 8–15.

## Unity Scripting


  
```
code blocks for commands
```
## Outstanding Elements
Multimedia Partner did deliver with the a few sprites e.g Protagonist

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Zaif Khan
ex. [@benpaddlejones](https://github.com/benpaddlejones)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]() or see [branch]()
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [Github md syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [TempeHS Unity template](https://github.com/TempeHS/TempeHS_Unity_DevContainer)
