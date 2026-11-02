# Home Assistant Blueprints

A collection of Home Assistant automation blueprints made by me :3

Click a blueprint's **Import** badge to add it straight to your Home Assistant instance.

## Blueprints

### Camera Snapshot AI Notification 📸

When motion is detected, takes 3 quick camera snapshots, asks an AI Task entity
what caused the motion, and sends the answer to your phone with a snapshot attached.
Skips the notification when the AI sees nothing of interest.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FEnderDragonEP%2FHomeAssistant-Blueprints%2Fblob%2Fmain%2Fcamera_ai_notify.yaml)

### Ikea Bilresa scroll wheel 🎚️

Controls lights and media players with the IKEA BILRESA scroll wheel remote over
Matter. Each of its 3 channels has its own button actions and scroll wheel mode:
dimming, color temperature, color hue, volume, or your own action.
Forked from [jhol-byte's blueprint](https://community.home-assistant.io/t/ikea-bilresa-scroll-wheel-blueprint-matter/965365).

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FEnderDragonEP%2FHomeAssistant-Blueprints%2Fblob%2Fmain%2FIkea_bilresa_scroll_wheel.yaml)

### Smart dehumidifier (energy saving) 💧

Keeps a room at your target humidity with as little runtime as possible, using a
separate room humidity sensor. Works with a dehumidifier entity or a switch / smart
plug. Optional extras include schedules, window and presence awareness, cheap-power
and solar-surplus gating, compressor protection, tank-full and sensor-lost safety,
and drain-pump control.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FEnderDragonEP%2FHomeAssistant-Blueprints%2Fblob%2Fmain%2Fsmart_dehumidifier.yaml)

### ZHA - Xiaomi Mijia Wireless Switch (WXKG01LM) 🔘

Turns the round Xiaomi Mijia button into a multi-function remote with ZHA: actions
for 1 to 5+ presses, hold and release, plus an optional hold-to-dim mode for a light.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FEnderDragonEP%2FHomeAssistant-Blueprints%2Fblob%2Fmain%2Fxiaomi_wxkg01lm_zha.yaml)

## Installation

The quickest way is to click a blueprint's **Import** badge above. Otherwise, import it manually:

1. In Home Assistant, go to **Settings → Automations & scenes → Blueprints**.
2. Click **Import Blueprint** (bottom right).
3. Paste the blueprint's URL and click **Preview**, then **Import blueprint**. For example:

   ```url
   https://github.com/EnderDragonEP/HomeAssistant-Blueprints/blob/main/camera_ai_notify.yaml
   ```

To use it, click the blueprint in the list and fill in the inputs to create an automation.

## Support

Found a bug or have a feature request? Please open an
[issue](https://github.com/EnderDragonEP/HomeAssistant-Blueprints/issues).
