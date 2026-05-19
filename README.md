# home-assistant-scripts

Script blueprints for Home Assistant — the fun stuff you wire to remotes, helpers, and “why is the living room doing that?” automations.

Installed here as a git submodule at `blueprints/script/etokheim-scripts/`.  
Automation blueprints live in [home-assistant-automations](https://github.com/etokheim/home-assistant-automations).

---

## Cycle Scenes in Area

Hue-style scene cycling for an entire area: tap once to walk through scenes, with smart “lights were off for a while” handling and first-class support for [Scene Extrapolation](https://github.com/etokheim/scene-extrapolation).

[![Add to Home Assistant](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fetokheim%2Fhome-assistant-scripts%2Fblob%2Fmaster%2Fcycle_scenes_in_area.yaml)

---

## Cycle Scenes

Same cycling idea, but you pick the scenes explicitly — handy when you are not using Scene Extrapolation or want a fixed playlist.

[![Add to Home Assistant](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fetokheim%2Fhome-assistant-scripts%2Fblob%2Fmaster%2Fcycle_scenes.yaml)

---

## Return the Lights

Lights went off in a hurry? This brings back exactly what was on — same brightness, same vibe, no surprise “full blast” recovery.

[![Add to Home Assistant](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fetokheim%2Fhome-assistant-scripts%2Fblob%2Fmaster%2Freturn_the_lights.yaml)

---

## Easy updates for blueprints?

Every blueprint here includes a `source_url` pointing at this repo, so you can keep them fresh without manual copy-paste.

If you want one-click (or hands-off) updates from the UI, check out **[Blueprints Updater](https://github.com/luuquangvu/blueprints-updater)** by [luuquangvu](https://github.com/luuquangvu) — a really well-done HACS integration that tracks blueprint changes and updates them like any other Home Assistant update. I am not affiliated with the project; I just use it and think it is worth sharing.
