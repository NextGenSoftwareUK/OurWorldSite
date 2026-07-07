# Our World — The OASIS Flagship Metaverse

**Geo-located AR/VR · OASIS Omniverse**

Our World is the flagship experience of the OASIS Omniverse — a geo-located augmented and virtual reality metaverse where real-world positive actions earn karma and shape the digital world around you. Powered by OGEngine, HoloNET and the OASIS API.

## What is Our World?

Our World overlays a rich digital layer on top of the physical world:

- **Geo-located discovery** — explore your local park and discover portals, quests, treasures and events at real GPS locations
- **AR combat** — fight monsters and defend locations using your phone camera in augmented reality
- **VR worlds** — dive deeper through portals into full VR environments
- **Karma economy** — real-world positive actions (cleaning up litter, volunteering, rescuing animals) earn in-game karma and rewards
- **Avatar continuity** — your OASIS universal avatar and all your karma, NFTs and achievements carry in from every other OASIS app

## OASIS Integration

| Feature | Detail |
|---|---|
| Avatar SSO | Single sign-on from OPORTAL — one avatar, every world |
| Karma | Real-world and in-game actions both earn OASIS karma |
| NFT Items | Weapons, pets, skins owned on-chain; portable across all OASIS games |
| GeoHotSpots | Physical GPS locations registered in STARNET |
| HoloNET | P2P data storage via Holochain for decentralised world state |

## Related Projects

- [`OGEngineSite`](../OGEngineSite) — the shared game engine
- [`OneWorldSite`](../OneWorldSite) — the full 3D UE5 sequel
- [`HoloNETSite`](../HoloNETSite) — the Holochain .NET client powering P2P storage

## Tech Stack

| Layer | Detail |
|---|---|
| Game Engine | OGEngine (Unity + custom AR layer) |
| Site | Single-file `index.html` — inline CSS + vanilla JS |
| OASIS API | `@oasisomniverse/web4-api@2.0.2` via esm.sh |
| Fonts | Orbitron, Rajdhani, Share Tech Mono (Google Fonts) |

## Running the Site Locally

```bash
npx serve .
# or
python -m http.server 8080
```

---

*Part of the [OASIS Omniverse](https://oasisomniverse.one) · The flagship OASIS experience*
