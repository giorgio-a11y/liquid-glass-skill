# Liquid Glass Claude Skill

A Claude Code skill for building native macOS/iOS applications with Apple's Liquid Glass design language.

## Installation

Copy the `liquid-glass` folder to your project's `.claude/skills/` directory:

```bash
# Clone and copy
git clone https://github.com/giorgio-a11y/liquid-glass-skill.git /tmp/liquid-glass-skill
mkdir -p .claude/skills
cp -r /tmp/liquid-glass-skill/liquid-glass .claude/skills/
rm -rf /tmp/liquid-glass-skill
```

Or manually download and place the `liquid-glass/` folder in `.claude/skills/`.

## Structure

Your project should look like:
```
your-project/
└── .claude/
    └── skills/
        └── liquid-glass/
            ├── SKILL.md
            └── references/
                ├── components.md
                └── apple-hig.md
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
