# Brutalism (Modern Web)

## Intent
Create raw, honest interfaces that reject superficial polish, exposing structural elements and embracing unconventional aesthetics as a statement.

## Principles
1. **Raw authenticity** - No decorative fluff
2. **Structural exposure** - Show the bones of the interface
3. **Deliberate ugliness** - Beauty is overrated
4. **High contrast** - Bold black and white
5. **Typographic dominance** - Text is design

## Layout Rules
- Harsh grid, often broken intentionally
- Full-width sections
- Asymmetric, unbalanced layouts
- Large typography as structural element
- Minimal padding
- Visible borders defining regions
- Sometimes intentionally broken layouts
- Bold section breaks

## Typography
- Font: System fonts, monospace, or bold display fonts
- Massive headlines: 48-120px
- Monospace for body text
- Mix font weights aggressively
- Uppercase for emphasis
- Tight letter-spacing for headlines
- Raw, unpolished text rendering
- Sometimes broken text alignment

## Colors
- Background: White or black
- Primary: Black and white only
- Accent: Single bright color (yellow, red, green)
- Harsh borders: 2-4px black
- No gradients
- No shadows
- High contrast always
- Sometimes inverted sections

## Components
- Raw Buttons: Thick borders, no radius, harsh
- Stark Cards: Thick black borders, no shadow
- Basic Inputs: Thick border, large padding
- Grid Tables: Visible borders everywhere
- Navigation: Text-only, bold
- Loading States: Animated ASCII art
- Form Elements: Oversized, obvious

## Do's
- Use thick black borders
- Mix serif and sans-serif
- Break grid intentionally
- Create oversized elements
- Use system fonts
- Add raw, unpolished touches
- Embrace contrast
- Make statements

## Don'ts
- Add subtle shadows
- Use rounded corners
- Apply gradients
- Hide structural elements
- Use more than 3 colors
- Create soft, approachable designs
- Polish rough edges
- Follow conventions blindly

## Agent Instructions
- Apply thick black borders (2-4px)
- Use system fonts or monospace
- Create oversized typography
- Break grid layouts
- Use black and white dominance
- Remove all shadows and gradients
- Add intentional roughness
- Reject polish

## Output Constraints
- HTML/CSS: Minimal styling, raw structure
- React: Simple functional components
- Border: 2-4px solid black
- No border-radius
- Font: System or monospace
- Contrast: Maximum

## Machine-Readable Rules
```json
{
  "name": "brutalism",
  "category": "experimental",
  "border_width": [2, 4],
  "border_radius": 0,
  "shadow_allowed": false,
  "gradient_allowed": false,
  "colors": ["black","white","accent"],
  "typography_scale": "large",
  "grid_strict": false,
  "intentional_breaks": true
}
```
