# D&D Campaign Wiki

A lightweight, file-based wiki system for crafting and managing D&D campaigns using [Obsidian](https://obsidian.md/).

## Why Obsidian?

- **Plain markdown files** - No database, no lock-in, full portability
- **Bidirectional linking** - `[[wikilinks]]` connect NPCs, locations, factions naturally
- **Graph view** - Visualize relationships across your campaign
- **Offline-first** - Works without internet, syncs via git or your preferred method
- **Extensible** - Plugins for dice rolling, statblocks, initiative tracking

## Getting Started

### 1. Install Obsidian
Download from [obsidian.md](https://obsidian.md/) (free for personal use).

### 2. Open This Vault
1. Open Obsidian
2. Click "Open folder as vault"
3. Select this `wiki_dnd` directory

### 3. Recommended Plugins
Go to Settings → Community Plugins → Browse:

| Plugin | Purpose |
|--------|---------|
| **Fantasy Statblocks** | Render 5e monster statblocks |
| **Dice Roller** | Inline dice notation (e.g., `dice: 2d6+3`) |
| **Initiative Tracker** | Combat management |
| **Dataview** | Query and display campaign data |
| **Templater** | Templates for NPCs, locations, etc. |
| **Calendar** | Track in-game dates and sessions |

### 4. Recommended Settings
- Settings → Files & Links → Use `[[Wikilinks]]` → ON
- Settings → Files & Links → Default location for new notes → Same folder as current file

## Project Structure

```
wiki_dnd/
├── campaigns/           # Each campaign in its own folder
│   └── campaign-name/
│       ├── _index.md    # Campaign home page
│       ├── sessions/    # Session notes
│       ├── characters/  # PCs and NPCs
│       ├── locations/   # Maps and places
│       ├── factions/    # Organizations
│       ├── items/       # Loot and artifacts
│       ├── lore/        # World background
│       ├── quests/      # Adventure hooks
│       ├── encounters/  # Combat setups
│       ├── offshoots/   # Side content, optional exploration
│       └── assets/      # Images and media
│           ├── maps/    # Location maps, dungeon layouts
│           ├── npcs/    # NPC portraits and art
│           ├── items/   # Item illustrations
│           └── handouts/# Player handouts
├── templates/           # Reusable note templates
├── CLAUDE.md            # AI assistant context
└── README.md            # This file
```

## Usage Tips

### Linking Everything
The power of Obsidian is connections. When writing:
- Mention an NPC? Link them: `[[Grimjaw the Merchant]]`
- Reference a place? Link it: `[[Shadowfen Swamp]]`
- Obsidian creates the file when you click the link

### Quick Capture
During sessions, dump notes fast. Clean up and link afterward.

### Graph View
Press `Ctrl/Cmd + G` to see your campaign as a connected graph. Orphan nodes (unlinked content) stand out for review.

### Search
`Ctrl/Cmd + Shift + F` searches all files. Great for finding every mention of an NPC.

### Images and Maps
Store images in the `assets/` folder within each campaign:

```
assets/
├── maps/      # Town layouts, dungeon maps, region maps
├── npcs/      # Character portraits and art
├── items/     # Item illustrations
└── handouts/  # Letters, wanted posters, documents for players
```

Embed images using Obsidian's syntax:
```markdown
![[assets/maps/dusthollow-main-street.png]]
```

Use lowercase filenames with hyphens: `tavern-floor-plan.png`

## Syncing Options

- **Git** - Version control, collaboration, history
- **Obsidian Sync** - Official paid option
- **Syncthing** - Free, peer-to-peer
- **Cloud storage** - Dropbox, iCloud, Google Drive (watch for sync conflicts)

## License

Your campaign content is yours. This repository structure is public domain.
