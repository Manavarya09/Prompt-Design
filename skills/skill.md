# PromptDesign

## Description

PromptDesign is a comprehensive library of 35 structured design language specifications that enable AI agents to understand, apply, and transform UIs across any design language.

## Usage

```
/load promptdesign
```

This loads the main PromptDesign skill with access to all 35 design languages.

## Commands

### Load a Design Language

```
/load promptdesign/[category]/[skill-name]
```

Examples:
```
/load promptdesign/core/minimalism
/load promptdesign/depth-texture/glassmorphism
/load promptdesign/modes-color/dark-mode-minimal
```

### List Available Skills

```
/promptdesign list
```

### Search Skills

```
/promptdesign search [query]
```

## Categories

| Category | Skills |
|----------|--------|
| core | 8 foundational skills |
| depth-texture | 6 visual effect skills |
| modes-color | 5 color system skills |
| experimental | 5 bold/avant-garde skills |
| product-oriented | 5 product-specific skills |
| futuristic | 5 next-gen skills |

## Transform UI

Apply a design language to transform any UI:

```
Input: [Your UI code or description]
Design: [Selected design language]

Output: Transformed UI following the design language rules
```

## Example

```
/load promptdesign/core/minimalism

Transform this HTML with minimalism:
<div style="background: blue; padding: 50px;">
  <h1 style="font-size: 48px; color: white;">Hello</h1>
  <p style="font-size: 24px;">World</p>
  <button style="background: green; padding: 20px;">Click</button>
</div>
```

## Master Prompt

When using PromptDesign, the AI follows these instructions:

```
You are a Design Language Engine.

Follow the [DESIGN_LANGUAGE] rules strictly:
- Layout: Grid system, spacing, structure
- Typography: Font family, sizes, hierarchy
- Colors: Use defined palette
- Components: Follow component specs

Enforce all constraints. Reject invalid patterns.
Maintain accessibility (WCAG AA minimum).
```

## License

MIT
