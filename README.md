

#  UO Unchained – Map Marker Repository

A player-curated collection of XML-based map markers and custom iconography for the **Ultima Online: Unchained** private server.

---

##  Installation

1. **Clone or download** this repository into the following directory:

Ultima Online Unchained\Data\Client


2. In-game: either **restart your client** or use the `reload mapicons` command to activate the markers.

---

##  Purpose

This project streamlines:

- Overworld and dungeon navigation
- Treasure hunting and recall routing
- Boss tracking and event coordination
- Lore-inspired exploration

Built for **players, mappers, and shard staff** alike.

---

##  Contents

### `MapIcons/`  
A complete icon set (300+ PNGs), including:

- **Mob tiering**: `MOB3nm`, `MOBBNM`, `MOB6SPAOE`, etc.  
- **Functional markers**: Moongates, exits, teleporters, shrines  
- **Treasure markers**: `TREASURE_LEVEL1` through `TREASURE_LEVEL8`  
- **Navigation tools**: `tosurface`, `tobossroom`, `stairs`, etc.  
- **Decorative types**: `scenic`, `pointofinterest`, `terrain`, etc.  

---

### `*.xml` Marker Files

Organized by region and dungeon, each file includes clean XML waypoint entries like:
```
<Marker Name="Shadow Altar" Facet="0" Icon="scenic" X="4581" Y="1337"/>
```
## Markers highlight:

    Boss and mini-boss locations
    Resource-rich areas
    Lore-heavy landmarks
    Teleport chains and hidden exits

### For Players

    Load XMLs into Razor Enhanced, UO Cartographer, or similar tools
    Quickly locate mobs, events, and resource nodes
    Build personal recall or dungeon overlays
    Track shard events and quests visually

# Credits

Project maintained by [Frogmancer SchtevE]
Discord: DMSchteve

Icons and data designed with love for the UO Unchained community. This project was built on the work done by Tykiller and Nalco from the Unchained community.

# Changelog
[2025-08-04] – Overhaul & Optimization Update
Added

    - New NPC location markers added across various overworld regions
    - Deceit dungeon map markers implemented for improved pathing

Changed

    - Removed inactive moongate markers to reduce clutter
    - Adjusted icon positions for better alignment with in-game POIs
    - Moved certain POIs to quests.xml for improved in-game filtering
    - Updated quest-related icons from landmark to pin to better reflect their purpose

Removed

    - Removed obsolete inner dungeon markers no longer relevant to the current shard layout

