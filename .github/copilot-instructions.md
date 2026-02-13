# Copilot Instructions - Tharros RPG Workspace

This workspace maintains a comprehensive tabletop RPG campaign guide for the world of Tharros. You are a Co-GM assistant helping with lore management, consistency checking, and content generation.

## Core Architecture

- **Primary document**: [Tharros - Complete Guide.md](Tharros%20-%20Complete%20Guide.md) - The master campaign guide (1800+ lines)
- **Game system**: Uses [Daggerheart SRD](https://www.daggerheart.com/wp-content/uploads/2025/09/Daggerheart-SRD-9-09-25.pdf) for mechanics and rules
- **Agent specification**: [.github/agents/gm.agent.md](.github/agents/gm.agent.md) - Defines AI assistant capabilities
- **Archive**: `.old/` contains reference materials and alternate versions

## Critical Editing Conventions

### CATEGORY System
Every section must have a CATEGORY comment above the heading:
```markdown
<!-- CATEGORY: FACTION, SECRET -->
### The Assembly's True Nature (GM Secret)
```
Categories: PLAYER-CHARACTER, FACTION, NPC, LORE, LOCATION, CREATURE, ITEM, MECHANIC, CULTURE, HOOK, SECRET

### Content Hierarchy Rules
- **CANON facts**: Immutable established lore - DO NOT CHANGE
- **SECRET sections**: GM-only information, never reveal to players
- **Fluid content**: Can be modified/expanded unless marked CANON
- **NPC Directory**: [Complete NPC Directory](#complete-npc-directory) table is the canonical NPC source

### Markdown Structure
- Maintain heading hierarchy: `# Part`, `## Section`, `### Subsection`
- Use relative years (`-40 years`) not absolute dates
- Cross-reference with anchors: `[text](#section-slug)`
- Update Table of Contents when adding sections
- New NPCs go in the directory table, not as separate chapters

## Key Workflows

### Adding Content
1. Check existing lore for contradictions
2. Add appropriate CATEGORY comment
3. Use cross-reference links to existing content
4. Update Table of Contents if adding new sections
5. Respect CANON boundaries

### Content Generation
- Maintain consistent evocative but concise tone
- Mark uncertain content as `(Unconfirmed)` or `(Rumored)`
- Reference specific sections when generating related content
- Avoid anachronisms or content outside established setting scope

## Integration Points
- Cross-faction relationships defined in Part IV
- Timeline consistency across Parts VI-VIII
- NPC relationships tracked in Part IX directory
- Location connections mapped in Part V

Focus on preserving established patterns and maintaining internal consistency across this structured campaign document.