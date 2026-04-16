<p align="center">
  <img src="https://github.com/AleDiz/PopPushAleDev/blob/main/img/logoPopPush.png" alt="Pop Push Logo" width="400">
</p>

# Pop Push 🍿

**Project Role:** Game Designer & Programmer  
**Tech Stack:** Z80 Assembly | Game Boy (GB)  
**Team Size:** 3 members (GBRetroDev 2025)  

*Pop Push is a fast-paced arcade game for the original Game Boy, developed in pure Z80 assembly during the GBRetroDev 2025 game jam (1 month). Inspired by simple yet addictive arcade experiences, the game focuses on minimalism, challenge, and replayability.*

---

## 🕹️ Play the Game
**Play it on itch.io:** 👉 [**Play Pop Push**](https://javierrhp.itch.io/pop-push)

---

## 🎮 Game Overview

*Pop Push is a fast-paced arcade game.*

You play as a brave corn cob trapped inside a microwave—surrounded by deadly heat. One wrong move and you’ll pop into popcorn.

Dodge incoming heat waves, bounce between walls, and survive as long as possible while chasing the highest score.

Master the rhythm, stay alive, and if you somehow reach 99 points… there might be a surprise waiting.

---

## 🧠 Design Focus

Unlike my previous Game Boy project [Soldier Assemble](https://github.com/AleDiz/SoldierAssembleAleDev), this game was intentionally **design-driven rather than technology-driven**.

The main goal was clear:
> Create the simplest possible game that is still fun and addictive.

This led to several key design decisions:

- **One-Button Gameplay:**  
  The entire experience is built around a single input, forcing clarity in mechanics and making the game instantly understandable.

- **Arcade Philosophy:**  
  Short sessions, immediate restarts, and a strong “just one more try” loop.

- **Difficulty Curve:**  
  The game increases its difficulty in noticeable steps every few bounces, requiring progressively better timing and player skill.

- **Rhythm-Based Interaction:**  
  Gameplay naturally evolves into a rhythm challenge, where player timing becomes the core mastery skill.

---

## 🔁 Core Loop

The gameplay loop is intentionally minimal but tightly tuned:

1. Bounce between walls  
2. Avoid incoming hazards  
3. Survive longer  
4. Beat your high score  
5. Repeat  

This loop was carefully balanced to ensure constant tension and reward.

---

## 🧩 Technical Notes (Brief)

Although the focus was on design, the game builds upon the custom engine developed for [*Soldier Assemble*](https://github.com/AleDiz/SoldierAssembleAleDev) (GBRetroDev 2024), allowing faster iteration during the jam.

A key technical addition in this project was:

- **Persistent High Score System:**  
  Implemented score saving directly on the Game Boy cartridge memory.  
  This required learning how to handle persistent data storage on real GameBoy hardware, ensuring the player’s progress remains between sessions—reinforcing the arcade replayability.

---

## 🎯 Design Takeaways

- Simplicity does not mean lack of depth  
- A strong core loop is more important than feature quantity  
- Difficulty pacing is critical in arcade games  
- Constraints (like one-button input) can enhance creativity  

---

## 📩 Contact & Feedback

- **GitHub:** [AleDiz](https://github.com/AleDiz)
- **LinkedIn:** [Alejandro Díaz](https://www.linkedin.com/in/alejandro-diaz-alcaraz-037099242)
- **Email:** aledevgames@gmail.com

---

**Note:** This project was developed in pure Z80 assembly for original Game Boy hardware. Some low-level systems and engine details are shared with [*Soldier Assemble*](https://github.com/AleDiz/SoldierAssembleAleDev) and are documented in that project.
