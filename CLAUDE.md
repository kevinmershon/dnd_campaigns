# D&D Campaign Wiki - Obsidian Project

## Project Overview
This is an Obsidian-based wiki for crafting and managing D&D campaigns. Each campaign lives in its own subfolder with interconnected markdown files.

## Directory Structure
```
wiki_dnd/
├── CLAUDE.md          # AI assistant instructions
├── README.md          # Project documentation
└── campaigns/
    └── <campaign_name>/
        ├── _index.md           # Campaign overview and entry point
        ├── sessions/           # Session notes and recaps
        ├── characters/
        │   ├── pcs/            # Player characters
        │   └── npcs/           # Non-player characters
        ├── locations/          # Places, dungeons, cities
        ├── factions/           # Organizations and groups
        ├── items/              # Magic items, artifacts
        ├── lore/               # World history, religions, cultures
        ├── quests/             # Active and completed quests
        ├── encounters/         # Combat encounters, random tables
        ├── offshoots/          # Side content, optional exploration
        └── assets/             # Images and media
            ├── maps/           # Location maps, dungeon layouts
            ├── npcs/           # NPC portraits and character art
            ├── items/          # Item illustrations
            └── handouts/       # Player handouts (letters, documents)
```

## Obsidian Conventions

### Linking
- Use `[[wikilinks]]` for internal references
- Use `[[link|display text]]` for custom display names
- Use `[[folder/note]]` for cross-folder references

### Frontmatter
All notes should include YAML frontmatter:
```yaml
---
type: npc|pc|location|faction|item|quest|session|lore
tags: [relevant, tags]
status: active|inactive|deceased|destroyed|completed
---
```

### Tags
Standard tag prefixes:
- `#type/` - Content type (npc, location, etc.)
- `#status/` - Current state
- `#region/` - Geographic area
- `#faction/` - Organization affiliation

### Statblocks
Use standard 5e statblock format in code blocks:
````markdown
```statblock
name: Creature Name
size: Medium
type: humanoid
alignment: neutral
ac: 15
hp: 45
speed: 30 ft.
stats: [16, 14, 14, 10, 12, 8]
```
````

### Images and Assets
Store images in the `assets/` folder, organized by type:
- `assets/maps/` - Location maps, dungeon layouts, town layouts
- `assets/npcs/` - NPC portraits and character art
- `assets/items/` - Item illustrations
- `assets/handouts/` - Player handouts (letters, wanted posters, documents)

**Embedding images**:
```markdown
![[assets/maps/town-map.png]]
```

**Naming convention**: Use lowercase with hyphens, descriptive names:
- `dusthollow-main-street.png`
- `mirela-portrait.jpg`
- `wanted-poster-pike.png`

## Content Guidelines

### NPCs
- Include appearance, personality, motivations, secrets
- Link to associated locations and factions
- Track relationship status with party

### Locations
- Include sensory details (sights, sounds, smells)
- List notable NPCs present
- Note connections to other locations

### Sessions
- Number sequentially (session-001, session-002)
- Include date played, players present
- Summarize key events, decisions, consequences

## File Naming
- Use lowercase with hyphens: `the-silver-dragon-inn.md`
- Prefix session files with numbers: `session-001-the-beginning.md`
- Keep names concise but descriptive

## Implementation Notes
- All content is plain markdown, no external dependencies
- Campaign folders are self-contained and portable
- Use relative links within campaigns for portability
