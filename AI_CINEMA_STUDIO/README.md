# 🎬 AI CINEMA STUDIO v1

> **A professional framework for automated cinematic production using Generative AI.**

## 📖 Overview
AI CINEMA STUDIO v1 is a structured production pipeline designed to create consistent, high-quality narrative content for the series **"Dramaia: The Unwritten Pages"**. It transforms simple narrative inputs into detailed technical specifications for image, video, and audio generation.

## 📦 Project Structure

| Directory | Purpose | Key Files |
| :--- | :--- | :--- |
| `00_CORE/` | System Configuration & Rules | `STUDIO_CONFIG.json`, `MASTER_PROMPT.md`, `PRODUCTION_RULES.json` |
| `01_SERIES/` | Narrative Brain | `SERIES_BIBLE.json`, `STORY_ENGINE.json` |
| `02_CHARACTERS/` | Character Bibles | `Anthony.json`, `Jamie.json`, `Franz.json` |
| `03_LOCATIONS/` | Location Bibles | `Jamie_Apartment.json` |
| `04_PROPS/` | Asset Tracking | `KEY_ITEMS.json` |
| `05_CONTINUITY/` | Production Memory | `CONTINUITY_TRACKER.json` |
| `09_EXPORTS/` | Delivery Standards | `EXPORT_SCHEMA.json` |

## 🚀 How to Use the Pipeline

### 1. Initialization
Ensure all JSON files in `00_CORE`, `01_SERIES`, and `02_CHARACTERS` are loaded into the AI context.

### 2. Generation Command
To generate an episode, use the following prompt structure:
> *"Use AI CINEMA STUDIO v1 to generate Episode [X]: [Title]."*

### 3. The Engine Process
The `MASTER_PROMPT.md` will automatically:
1.  Retrieve the narrative arc from `SERIES_BIBLE.json`.
2.  Check character states and prop locations in `CONTINUITY_TRACKER.json`.
3.  Apply lighting and camera rules from `PRODUCTION_RULES.json`.
4.  Generate structured prompts for Midjourney, Runway/Pika, and ElevenLabs.

## 🎨 Visual & Audio Identity
*   **Genre:** Psychological Thriller / Neo-Noir.
*   **Lighting:** High contrast, Chiaroscuro for threats, Warm amber for sanctuary.
*   **Camera:** Anamorphic lenses, shallow depth of field, deliberate movements.
*   **Audio:** Minimalist piano, ambient drones, focus on breathing and foley.

## ⚠️ Critical Rules
*   **Consistency:** Never change physical character features (hair, eyes) without updating the JSON.
*   **Continuity:** Always check `05_CONTINUITY/` before starting a new episode to track props (e.g., broken glass).
*   **Tone:** Maintain the "Dramaia" melancholic and suspenseful atmosphere.

## 🛠️ Version History
*   **v1.0 (July 2026):** Initial framework construction. Core modules, characters, and pilot episodes (1-4) integrated.

---
*Built for Dramaya. Designed for longevity.*