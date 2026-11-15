# 🌌 Nemesis — Hybrid AI Minecraft Companion (Gemini + Ollama)

> **Not a command bot. A teammate that listens, speaks, builds, and clutches.**  
> 🌐 **Official Website:** [Nemesis Official Website](https://Nemesismc.lovable.app)

**Nemesis** is the next-generation successor to **Genesis**. Built with a **hybrid AI architecture**, Nemesis lets you choose between **cloud-powered Google Gemini** or **100% local Ollama models** depending on your hardware and preferences. Talk to it in chat or speak into your mic, and Nemesis breaks complex goals down step-by-step to execute them in-game.

---

## ✨ What's New & Key Features

* 🧠 **Hybrid AI Brain (Gemini + Ollama):** Switch seamlessly between **Google Gemini** for fast cloud intelligence and **local Ollama** (such as `llama3.2`) for offline, zero-cost, unlimited AI actions with no API rate limits.
* 🪜 **Stepwise Thinking:** Breaks multi-step goals into clear plans—figuring out which tools it needs, what materials to gather, and where to go.
* 🎙️ **Voice Instructions & TTS:** Speak commands into your microphone; Nemesis hears you, executes the action, and talks back with text-to-speech (with auto-mute while speaking).
* 🏰 **Instant `.schem` Building:** Drop any `.schem` file into the folder and say *"build house.schem"*. Nemesis reads the block palette and constructs it with `/setblock`—no resource gathering required.
* 👑 **Ownership & Voice Filtration:**
  * `Sensei.json`: Defines owners and trusted players, with an `ownerOnly` toggle to ignore unauthorized users.
  * `VoicePlayers.json`: Filters which voices Nemesis obeys using confidence thresholds and wake words.
* ⚔️ **Advanced PvP & Attribute Swapping Suite:**
  * **Attribute Swapping:** Performs frame-accurate hotbar attribute swapping with both the **Mace** and **Spear** for maximum burst damage.
  * **Aerial & Explosive Combat:** Supports **Elytra Mace PvP**, **Elytra Spear PvP**, and **Crystal PvP**.
  * **Melee & Ranged Mastery:** Crit-timed jump swings, shield blocking between hits, smart strafing, and bow combat beyond 5 blocks.
* 🪂 **4-Way MLG Clutches:** Keeps water buckets, boats, ender pearls, and Totems of Undying in its hotbar to clutch falls automatically.
* ⛏️ **Auto-Mining, Crafting & Survival:** Mines ores (up to Ancient Debris) by upgrading its own pickaxe tier, builds crafting tables and furnaces on demand, sleeps through the night, auto-gears, and retreats to eat golden apples below 6 hearts.
* 🌐 **Any-Version Auto-Detect:** Automatically detects the server's Minecraft version upon joining.

---

## 💬 Example Commands (Chat or Voice)

| What You Say | What Nemesis Does |
| :--- | :--- |
| *"Yo Nemesis, build house.schem right here."* | Reads the `.schem` palette and builds it block-by-block. |
| *"Mine me 10 diamonds."* | Plans tool tiers, mines down, and gathers 10 diamonds. |
| *"Go sleep, it's night."* | Finds or crafts a bed and sleeps through the night. |
| *"Defend me from that guy."* | Engages using attribute-swapped Mace/Spear hits, Elytra dives, Crystals, or bow. |
| *"Nemesis, give me all your diamonds."* | Checks `Sensei.json` permissions before delivering or refusing. |

---

## ⚙️ Access & Voice Configuration

Nemesis uses two JSON configuration files to keep your bot secure:

* **`Sensei.json`:** Controls in-game ownership and command permissions:
  ```json
  {
    "owner": ["Neon_Elitz", "King_Of_Curses"],
    "trusted": ["ShadowFighter473"],
    "ownerOnly": true
  }
  ```
* **`VoicePlayers.json`:** Controls which speakers are recognized via microphone input, confidence filtering, and wake-word detection.

---

## 🔗 Links

* **Official Website & Preview:** [Nemesis](https://Nemesismc.lovable.app)

*Disclaimer: Nemesis is an independent project and is not affiliated with or endorsed by Mojang or Microsoft.*
