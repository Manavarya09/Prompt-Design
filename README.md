# PromptDesign

### Give AI a Sense of Design

---

**35 structured design languages. One command. Consistent UIs.**

AI generates messy layouts, inconsistent spacing, and random colors. PromptDesign fixes that by giving AI a complete design specification to follow.

---

## Quick Start

```bash
npm install promptdesign
```

**Claude / skills.sh:**
```
/load promptdesign/core/minimalism
/load promptdesign/depth-texture/glassmorphism
```

**JavaScript:**
```javascript
import { getDesignLanguage } from 'promptdesign';
const design = await getDesignLanguage('minimalism');
```

---

## The Problem

AI-generated UIs look like AI generated them:
- Inconsistent spacing (random 16px, 24px, 8px values)
- Messy colors (arbitrary hex codes, clashing palettes)
- No design system (each component looks different)

## The Solution

Structured design language specifications that AI follows. Each skill includes:
- Layout rules (grid, spacing, responsive)
- Typography (fonts, sizes, hierarchy)
- Color system (palettes, contrast, usage)
- Components (buttons, forms, cards)
- Do's and Don'ts
- Machine-readable JSON

---

## 35 Design Languages

| Category | Skills |
|----------|--------|
| **Core** (8) | minimalism, flat-design, material-design, swiss-international, enterprise-ui, data-first-dashboard, card-based-ui, bento-grid-layout |
| **Depth** (6) | glassmorphism, neumorphism, claymorphism, soft-ui, gradient-mesh-design, aurora-ui |
| **Color** (5) | dark-mode-minimal, monochrome-aesthetic, duotone-design, high-contrast-accessibility, pastel-ui |
| **Bold** (5) | brutalism, anti-design, retro-web, cyberpunk-ui, vaporwave-aesthetic |
| **Product** (5) | saas-modern, fintech-ui, ecommerce-conversion, mobile-first-ui, super-app-ui |
| **Futuristic** (5) | tech-futurism, ai-native-ui, spatial-ui, voice-first-ui, gesture-based-ui |

---

## Each Skill Includes

- **Principles** - Core design philosophy
- **Layout Rules** - Grid system, spacing, breakpoints
- **Typography** - Font family, sizes, weights, line heights
- **Colors** - Complete palette with hex codes
- **Components** - Button styles, form specs, card layouts
- **Do's / Don'ts** - Quick design guidance
- **Agent Instructions** - Prompts for AI transformation
- **Output Constraints** - Technical specs for code output
- **JSON Schema** - Machine-readable for programmatic access

---

## Use Cases

| Need | Skills |
|------|--------|
| Clean landing page | minimalism, glassmorphism |
| Mobile app | material-design, soft-ui |
| Dashboard | data-first-dashboard, bento-grid-layout |
| E-commerce | ecommerce-conversion, saas-modern |
| Dark theme | dark-mode-minimal, cyberpunk-ui |
| Accessible | high-contrast-accessibility, voice-first-ui |

---

## API

```javascript
import { getDesignLanguage, getAllDesignLanguages, transformUI } from 'promptdesign';

// Get a single design language
const design = await getDesignLanguage('glassmorphism');

// List all available languages
const all = await getAllDesignLanguages();

// Transform UI following rules
const result = await transformUI({
  design: 'minimalism',
  input: '<div>Your UI</div>'
});
```

---

## Compatible Platforms

Claude (skills.sh) / OpenAI / GPT / Cursor / VS Code / Custom APIs

---

## License

MIT

---

[View Landing Page](https://manavarya09.github.io/Prompt-Design)
