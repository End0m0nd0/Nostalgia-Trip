# 🕹️ Nostalgia Trip

![2nd Place](https://img.shields.io/badge/Game_Jam_2025-2nd_Place-gold.svg)
![Unity](https://img.shields.io/badge/Made_with-Unity-black?logo=unity)
![C#](https://img.shields.io/badge/Language-C%23-blue)

**Nostalgia Trip** is a game created during Game Jam v8 PJATK in 2025. After an intensive development process, our team proudly took **2nd place**! 🏆 
🔗 [Read the official event recap here](https://pja.edu.pl/relacja-z-game-jam-v8/)

## 🎥 Gameplay Showcase

[![Nostalgia Trip Gameplay](https://img.youtube.com/vi/2ID7UplhUp0/hqdefault.jpg)](https://www.youtube.com/watch?v=2ID7UplhUp0)<br>
*(Click the image above to watch the gameplay video on YouTube)*

## 💡 About the Project

**Nostalgia Trip** is a 2-player cooperative puzzle-platformer inspired by classics like "Fireboy and Watergirl". Players control two unique characters with distinct abilities—one can transform into a nimble hedgehog to change their size, while the other becomes a powerful gorilla. Players must work together synchronously to solve puzzles, overcome obstacles, and navigate levels filled with mechanics like rope swinging, pendulums, and button-operated doors. 

The core theme of the game is a "return to the past," which is brilliantly reflected in its visual and technical progression:
* **Level 1:** Retro 8x8 graphics with a static camera.
* **Level 2:** Upgraded 16x16 graphics with a dynamic camera tracking the players.
* **Level 3:** Detailed 32x32 graphics featuring a split-screen mode.

The project features unique visuals, utilizing custom shaders written in **ShaderLab / HLSL**. The core game logic and mechanics are scripted in **C#**, and the level environments were constructed using Unity's Tilemap system.

## 🛠️ Technologies & Tools

* **Game Engine:** Unity 2022.3.46f1 (LTS)
* **Programming:** C#
* **Graphics & Rendering:** Custom Shaders (ShaderLab, HLSL)
* **UI System:** UI Elements

## 👥 Development Team

This project was brought to life by an amazing 5-person team who joined forces for the duration of the jam:

* **[Dawid Juszyński (VeeturN)](https://github.com/VeeturN)** - Developer
* **[Julia (juliapazdziorek)](https://github.com/juliapazdziorek)** - Developer
* **[Kinga Kowalska (JackKaKi)](https://github.com/JackKaKi)** - Developer
* **[Jędrzej Nowakowski (End0m0nd0)](https://github.com/End0m0nd0)** - Developer
* **Zuzanna G** - 2D/3D Art & Visuals 🎨

## 🚀 How to Run the Project

### Requirements
* [Git](https://git-scm.com/downloads)
* [Unity Hub](https://unity.com/download)
* **Unity 2022.3.46f1 (LTS)** – the editor version this project was made with. Other 2022.3.x LTS versions should also work.

### Steps
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/End0m0nd0/Nostalgia-Trip.git
   ```
2. Open **Unity Hub**, go to **Projects → Add → Add project from disk** and select the cloned `Nostalgia-Trip` folder.
3. If Unity 2022.3.46f1 is not installed, Unity Hub will offer to install it – accept, or pick another 2022.3.x version you already have.
4. Open the project. The first launch can take a few minutes while Unity imports assets and generates the `Library` folder.
5. In the **Project** window open the scene `Assets/Scenes/UIScene.unity` – it is the entry point that loads the main menu.
6. Press **▶ Play** in the editor and start the game from the menu.

### Building a standalone version
1. Go to **File → Build Settings…**
2. Make sure `UIScene` is the first scene in the *Scenes In Build* list.
3. Pick your target platform (e.g. *Windows, Mac, Linux*) and click **Build**.

## 🎮 Controls

The game is played by two players on one keyboard.

| Action | Player 1 | Player 2 |
| --- | --- | --- |
| Move | `W` `A` `S` `D` | `↑` `←` `↓` `→` |
| Jump | `Space` | `U` |
| Transform (hedgehog / gorilla) | `R` | `I` |
| Grapple / rope (levels 2–3) | `Left Mouse Button` | `P` |
| Dash (levels 2–3) | `Left Shift` | `O` |
| Pause menu | `Esc` | `Esc` |
