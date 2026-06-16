# Spelunkery: Navigation Edition 🧭📐

Welcome to **Spelunkery: Navigation Edition** — an immersion-focused navigation addon for Minecraft 1.20.1 (Forge). 

This mod reworks how coordinates and navigation tools work to provide a more authentic, medieval maritime experience. Instead of relying on exact block numbers from the `F3` debug screen, players use a stylized grid system to navigate the world.

---

## ⚙️ Core Features

* **Masked Coordinate System:** Raw block coordinates ($X$ and $Z$) are masked into a global degree grid. 1,000 blocks equals exactly $1.0^\circ$ of the world.
* **🧭 The Compass (Longitude):** Right-clicking the compass measures your **Longitude** (the $X$ axis), rounded to a single decimal place (e.g., `Longitude: 2.5°`). It no longer shows raw numbers or allows magnetism on common ores.
* **📐 The Sextant (Latitude):** A dedicated navigation tool that measures your **Latitude** (the $Z$ axis) based on the world's degree grid (e.g., `Latitude: -8.7°`).
* **⏳ Measurement Cooldown:** Both instruments have a 3-second cooldown to prevent spamming, encouraging players to stop, take a reading, and plan their course.

---

## ⚖️ Credits & License

This project is a standalone addon for the [Spelunkery](https://www.curseforge.com/minecraft/mc-mods/spelunkery) mod created by **Sextant Studios**.

In compliance with the **GNU Lesser General Public License v3.0 (LGPLv3)** under which Spelunkery is distributed:
* This mod does **not** redistribute modified source code of the original mod.
* It uses Minecraft Forge event buses to safely override and expand item behaviors.
* Full credits go to Sextant Studios for their incredible work on the baseline immersion mechanics!

Licensed under the **GNU General Public License v3.0 (GPLv3)**.
