# dove - a simple, unblocked games api
sort of, docs to add games to your website


| # | Provider | Repo | Catalogs |
|---|----------|------|---------|
| 1 | [Night.](#1-night) | `yellowdevelopment/night@main` |`Games, Apps`|
| 2 | [gn-math](#2-gn-math) | `freebuisness/assets@latest` | `Games` |
| 3 | [ugs](#3-ugs) | `bubbls/ugs-singlefile@main` | `Games` |
| 4 | [Seraph](#4-seraph) | `skibbsz/seraph@main` | `Games, Apps` |
| 5 | [ckv](#5-ckv) | `skibbsz/ChickenKingsVault@main` | `Games` |

## Base overview & how to use

1. The Basics
- To Load a catalog, select the provider you want to use then fetch the games/apps catalog url
- With the catalog url of your selected provider loaded, populate buttons via the catalog (The catalog already has links to the needed files/icons & should dynamically load the buttons)
- Then, Set your base url to that of your selected provider
- After you've done that and setup everything else thats needed (Game cards, js, iframe/embed system, etc) you need a system to run the recieved html files that will be delivered from the provider or else you'll just recieve a bunch of raw html code.
- Now after you've actually finalized everything, you can then proceed onto adding other providers with different js classes and a button to load each of them like I did
- If you vibecode like I do, just drop this readme.md file into your ai bot and it should know what to do and set it up
2. Note
- I just described it the way I used these providers, some of the providers like Night., Seraph, and ckv's files will be delivered through my jsdelivr while gn-math and ugs are not managed by me. I just provided the endpoints and what you need to know to run it in your website.

## 1. Night.
- https://usenight.vercel.app
- **Base Url:** `https://cdn.jsdelivr.net/gh/yellowdevelopment/night@main/`
- **Games Catalog:** `https://cdn.jsdelivr.net/gh/yellowdevelopment/night@main/mages.json`
- **Apps Catalog**: `https://cdn.jsdelivr.net/gh/yellowdevelopment/night@main/apps.json`
- **Games base:** `https://cdn.jsdelivr.net/gh/yellowdevelopment/night@main/mages/`
- **Apps base:** `https://cdn.jsdelivr.net/gh/yellowdevelopment/night@main/apps/`
- **Cover base:** `https://cdn.jsdelivr.net/gh/yellowdevelopment/night@main/icons/`
- ✅ 500+ Games
- ✅ Games & Apps Catalog


## 2. gn-math
- https://gn-math.dev
- **Catalog:** `https://cdn.jsdelivr.net/gh/freebuisness/assets@latest/zones.json`
- **Game base:** `https://cdn.jsdelivr.net/gh/freebuisness/html@main/`
- **Cover base:** `https://cdn.jsdelivr.net/gh/freebuisness/covers@main/`
- ✅ 800+ Games
- ⚠️ Some games don't work due to cdn restrictions

## 3. Ultimate Game Stash (ugs)
- https://docs.google.com/document/d/1_FmH3BlSBQI7FGgAQL59-ZPe8eCxs35wel6JUyVaG8Q/
- **Catalog:** `https://cdn.jsdelivr.net/gh/bubbls/ugs-singlefile@main/games.js`
- **Game base:** `https://cdn.jsdelivr.net/gh/bubbls/ugs-singlefile@main/UGS-Files/`
- ✅ 2800+ Games
- ❌ No Covers

## 4. Seraph
- https://github.com/a456pur/seraph
- **Base Url:** `https://cdn.jsdelivr.net/gh/skibbsz/seraph@main/`
- **Games Catalog:** `https://cdn.jsdelivr.net/gh/skibbsz/seraph@main/games.json`
- **Apps Catalog**: `https://cdn.jsdelivr.net/gh/skibbsz/seraph@main/apps.json`
- **Cover base:** `https://cdn.jsdelivr.net/gh/skibbsz/seraph@main/thumbnails/`
- ✅ 500+ Games
- ✅ Games & Apps Catalog
- ❌ Has longer horizontal covers (doesn't look good)
- ❌ Unmanaged

## 5. ChickenKingsVault (ckv)
- https://github.com/WanoCapy/ChickenKingsVault
- **Base Url:** `https://cdn.jsdelivr.net/gh/skibbsz/ChickenKingsVault@main/`
- **Catalog:** `https://cdn.jsdelivr.net/gh/skibbsz/ChickenKingsVault@main/games.js`
- **Game base:** `https://cdn.jsdelivr.net/gh/skibbsz/ChickenKingsVault@main/gamefiles/`
- **Cover base** `https://cdn.jsdelivr.net/gh/skibbsz/ChickenKingsVault@main/gameimages/`
- ❌ Unmanaged

