# Jukebox Real Music — Project Summary

## One-liner

**Vanilla music discs, but they actually play classic Minecraft YouTube parodies.**

## What it is

Jukebox Real Music is a Minecraft Java Edition **resource pack** (no mods required). It swaps the short vanilla disc tracks for full fan-made parody songs — Revenge, TNT, Fallen Kingdom, and the rest — and adds custom album-art textures plus proper in-game song titles when a disc is playing.

Drop a disc in a jukebox. Hear the real song. See the right name on screen.

## Who it's for

Anyone who grew up on Minecraft parody music and wants that feeling back in survival, on a server, or in a creative world — without installing mods or a custom music mod.

## What's included


|                        |                                                             |
| ---------------------- | ----------------------------------------------------------- |
| **Custom tracks**      | 13 music discs                                              |
| **Custom textures**    | 12 album-art disc icons (Creeper Rap is audio-only for now) |
| **In-game labels**     | Jukebox “Now playing” titles for every replaced disc        |
| **Minecraft versions** | Java 1.19.4 → 1.21.x                                        |
| **Dependencies**       | None — resource pack only                                   |


## Track mapping (vanilla disc → song)


| Disc    | Song                      |
| ------- | ------------------------- |
| 13      | Revenge                   |
| cat     | Hunger Games              |
| blocks  | 500 Chunks                |
| chirp   | Supernatural Mobs         |
| far     | Fallen Kingdom            |
| mall    | Screw the Nether          |
| mellohi | Dragonhearted             |
| stal    | Don't Mine at Night       |
| strad   | How Do I Craft This Again |
| ward    | TNT                       |
| 11      | Creeper Rap               |
| wait    | Wrecking Mob              |
| pigstep | Mine All Day              |


Newer vanilla discs (5, otherside, relic, creator, etc.) are **not** changed.

## Repository layout

```
JukeboxRealMusic/
├── Jukebox Real Music/    ← the actual Minecraft resource pack
│   ├── pack.mcmeta
│   ├── pack.png
│   └── assets/minecraft/
│       ├── lang/          ← disc names & jukebox titles
│       ├── sounds/records/← parody .ogg files
│       └── textures/item/ ← album-art disc icons
├── README.md              ← install guide & full details
└── SUMMARY.md             ← this file
```

## Short description

> Minecraft Java resource pack — vanilla music discs play classic YouTube parody songs (Revenge, TNT, Fallen Kingdom, etc.) with custom album art. No mods. 1.19.4–1.21.x.

## Status

| Area | Status |
|------|--------|
| Audio replacement | Done (13/13) |
| Jukebox titles | Done |
| Disc textures | 12/13 (missing: Creeper Rap / disc 11) |
| Cross-version support | Done |
| Public documentation | Done |


## Legal note

Songs are fan-made parodies; rights belong to the original artists. This is a non-commercial fan project. See README for the full copyright section.