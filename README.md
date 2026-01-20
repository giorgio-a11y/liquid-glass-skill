# Liquid Glass Claude Skill

A Claude Code skill for building native macOS/iOS applications with Apple's Liquid Glass design language.

## Installation

Copy the skill to your project's `.claude/skills/` directory:

```bash
mkdir -p .claude/skills/references
curl -o .claude/skills/SKILL.md \
  https://raw.githubusercontent.com/giorgio-a11y/liquid-glass-skill/main/SKILL.md
curl -o .claude/skills/references/components.md \
  https://raw.githubusercontent.com/giorgio-a11y/liquid-glass-skill/main/references/components.md
curl -o .claude/skills/references/apple-hig.md \
  https://raw.githubusercontent.com/giorgio-a11y/liquid-glass-skill/main/references/apple-hig.md
```

## Structure

```
liquid-glass-skill/
├── SKILL.md              # Main skill (252 lines, loads automatically)
└── references/
    ├── components.md     # Full component implementations
    └── apple-hig.md      # Complete Apple HIG reference
```

## What It Does

When triggered, Claude will:
- Apply Liquid Glass design patterns
- Use proper materials and glass effects
- Follow Apple HIG spacing, typography, colors
- Create accessible, native-feeling interfaces

## Triggers

The skill activates when you ask Claude to:
- Build macOS or iOS apps
- Create SwiftUI interfaces
- Design Apple-style UI
- Implement glass effects or materials

## Looking for a Standalone Guide?

If you just want to read the guidelines without Claude integration:
**[liquid-glass-guide](https://github.com/giorgio-a11y/liquid-glass-guide)**
