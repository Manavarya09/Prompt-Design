# Monochrome Aesthetic

## Intent
Create sophisticated, timeless interfaces using variations of a single hue, proving that elegant design doesn't require a rainbow of colors.

## Principles
1. **Single hue discipline** - One color, infinite variations
2. **Value hierarchy** - Lightness creates all contrast
3. **Timeless sophistication** - Avoids trendy color pitfalls
4. **Visual harmony** - Everything works together
5. **Typographic focus** - Type becomes primary design element

## Layout Rules
- Strict grid alignment
- Generous whitespace
- Asymmetric layouts preferred
- Content-focused, no decorative elements
- Single column or simple multi-column
- 24px+ section spacing
- Clear visual hierarchy through scale
- Minimalist navigation

## Typography
- Font: Single typeface, multiple weights
- Title: 28-40px bold
- Subtitle: 18-24px medium
- Body: 14-16px regular
- Captions: 11-12px regular
- Letter-spacing variations
- Type hierarchy does all the work
- Uppercase for small labels

## Colors
- Background: White (#FFFFFF) or off-white
- Light shades: #F5F5F5, #E5E5E5, #D4D4D4
- Medium shades: #A3A3A3, #737373
- Dark shades: #525252, #404040, #262626
- Black: #171717 or #000000
- One accent: Darker or tinted version of base hue
- No other colors anywhere

## Components
- Monochrome Buttons: Single hue variations
- Monochrome Cards: Light background, dark text
- Monochrome Inputs: Simple borders
- Monochrome Navigation: Text-only or simple icons
- Monochrome Icons: Line style, same hue
- Monochrome Dividers: Hairline rules
- Monochrome Images: Desaturated or duotone overlay
- Monochrome Tags: Subtle background shades

## Do's
- Use shades of one color throughout
- Create hierarchy through lightness contrast
- Let typography carry the design
- Apply generous whitespace
- Use uppercase sparingly
- Maintain consistent spacing
- Add subtle hover states (darker shade)
- Use single accent for CTAs

## Don'ts
- Introduce secondary colors
- Use bright or saturated accents
- Add decorative elements
- Create busy layouts
- Mix multiple typefaces
- Use gradients (except subtle shade gradients)
- Add texture or patterns
- Apply shadows (except subtle depth)

## Agent Instructions
- Restrict palette to single hue family
- Create 5-7 value variations
- Use white or lightest shade for background
- Use black or darkest shade for primary text
- Apply scale for hierarchy (font sizes)
- Remove all color decorations
- Use only grayscale for images
- Maintain absolute consistency

## Output Constraints
- HTML/CSS: CSS custom properties for shades
- React: Single color theme object
- Shade count: 5-7 values
- Font: Single family, 3-4 weights
- No decorative elements
- Image handling: Grayscale or single hue tint

## Machine-Readable Rules
```json
{
  "name": "monochrome-aesthetic",
  "category": "modes-color",
  "hue_count": 1,
  "shade_count": [5, 7],
  "background": "lightest",
  "text": "darkest",
  "gradient_allowed": false,
  "decorative_elements": false,
  "font_family_single": true,
  "typography_hierarchy": true
}
```
