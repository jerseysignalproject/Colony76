# 🚀 Colony '76

**Colony '76** is a high-fidelity, single-file civilization simulator. Designed with a "Permacomputing" philosophy, the entire game—logic, rendering, and sound—lives within a single HTML file. No build tools, no `npm install`, and no external dependencies. Just raw, hackable JavaScript.

---

## 🏛️ The "Ages of Man" System
This edition introduces the **Civilization Ladder**. You no longer begin with industrial power; you must guide your colony through 7 distinct eras of human history.

### The 7 Eras
1.  **Stone Age (Start):** Survival basics. No tax revenue. Focus on Corn and Yurts.
2.  **Copper Age (50 Pop):** The Wheel. Roads provide a +5% tax bonus to adjacent dwellings.
3.  **Iron Age (200 Pop):** Smelting. Unlocks Wheat, Heavy Machinery, and the Quarry.
4.  **Age of Sail (500 Pop):** Navigation. Trade via Docks and Boats. Rice cultivation begins.
5.  **Mechanical Age (1,200 Pop):** Efficiency. Windmills boost nearby crop yields.
6.  **Industrial Age (3,000 Pop):** Steam Power. Factories, Railroads, and Apartments.
7.  **Age of Flight (5,500 Pop):** Aeronautics. Build Skyscrapers and Radar Stations to reach the pinnacle of progress.

---

## 🍞 Core Survival Mechanics

### 1. The Hunger Update
Population isn't just a score; it's a mouth to feed. 
* **Consumption:** $\text{Food} -= \lfloor \text{Pop} \times 0.05 \rfloor$ every tick.
* **Starvation:** If food drops below zero, **Starvation Imminent** is triggered. Tax revenue is slashed by **80%** as your citizens lose the will to contribute.

### 2. Economic Strategy
* **Winter Hardship:** During Winter months, crops stop growing and **Industrial maintenance costs double**. 
* **Market Adjacency:** Strategic placement is key. Markets gain a **+25% tax bonus** for every adjacent Road, Railroad, or Dock tile.
* **Industrial Maintenance:** Factories and Airfields have high upkeep. Balance your expansion or face bankruptcy.

---

## 🛠️ Designed for Hackers
Colony '76 is built to be edited. Because it is a single file, you can modify the game instantly:
* **Easy Expansion:** Add new buildings or eras by simply editing the `types` array in the script tag.
* **Native Audio:** Uses the **ZZFX/ZZFXM** engine—sounds are generated via code, meaning no broken audio links, ever.
* **Open Logic:** The AI and economic logic are exposed and commented for anyone to learn or improve upon.

---

## 🕹️ How to Play
1.  **Open** the `.html` file in any modern web browser.
2.  **Manage Food:** Build enough crops to sustain your growing population.
3.  **Scale the Ladder:** Watch your Rank and Era update as your population hits milestones.
4.  **Pause and Plan:** Use the **Pause** button to stop the simulation and strategize your layout without losing resources.

---

## 📜 License
**MIT License.** Colony '76 is free to play, free to fork, and free to evolve—forever.
