# Navratri Garba Night

A mobile-first 3D garba ground for Navratri. Design a low-poly dancer, give them a name, and watch them join the circle around the lit garbo lamp.

## Features

- Decorated garba ground: mandap with the garbo, marigold garlands, rangoli, bunting with twinkling bulbs, lantern posts and diyas.
- Dancer studio: character, skin tone, hair (braid, bun, open, ponytail, short, pagdi), upper wear (choli, kediyu, kurta), bottom wear (chaniya, ghaghra, salwar, dhoti, churidar), fabric colours, dandiya sticks or taali claps.
- Music picker that changes the step for the whole circle:
  - Garba song 1: Tran taali
  - Garba song 2: Dandiya raas (partners face each other and circle around)
  - Dhol beat (synthesised in the browser): Be taali
- The page measures each song's tempo so the claps and stick hits land on the beat.
- Your dancers are saved in your browser (localStorage).

## Run locally

Songs are loaded with `fetch`, so open the page through a local web server rather than double-clicking the file:

```bash
npx serve .
```

## Files

- `index.html`: the whole app (Three.js r128 from cdnjs)
- `Audio/GarbaSong1.mp3`, `Audio/GarbaSong2.mp3`: the two songs
