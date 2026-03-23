# Duotone Design

## Intent
Create striking, branded interfaces using exactly two colors, where the relationship between light and dark creates all visual hierarchy and interest.

## Principles
1. **Two-color commitment** - Strict limitation drives creativity
2. **Contrast as design** - Two hues define everything
3. **Brand impact** - Strong, memorable visual identity
4. **Universal applicability** - Works for any brand colors
5. **Systematic approach** - Every element uses the pair

## Layout Rules
- Bold two-color backgrounds (split or blocks)
- Grid with alternating color zones
- High contrast between sections
- 16-24px spacing
- Geometric shapes in accent color
- Cards with two-color treatment
- Photography treated as duotone
- Consistent two-color patterns

## Typography
- Font: Bold geometric sans-serif
- Title: 28-40px bold, accent color option
- Body: 14-16px regular, dark color
- High contrast between text and background
- Large text benefits from duotone treatment
- Letter-spacing: 0.02-0.05em
- Uppercase headlines for impact

## Colors
- Primary: Any brand color (#FF0000, #0066FF, #7B2DFF)
- Secondary: White (#FFFFFF) or black (#000000)
- Dark mode: Primary + black
- Light mode: Primary + white
- Text: Contrasting base color
- Backgrounds: Alternating primary/secondary
- Hover states: Invert or darken
- Duotone images: Two-color image treatments

## Components
- Duotone Buttons: Primary color fill
- Duotone Cards: White with colored header/accent
- Duotone Navigation: Two-tone bar
- Duotone Icons: Two-color icon style
- Duotone Images: SVG filter for two-color
- Duotone Shapes: Abstract geometric elements
- Duotone Badges: Colored pills
- Duotone Dividers: Thick colored lines

## Do's
- Use exactly two colors (no shades)
- Create strong contrast between them
- Apply two colors consistently
- Use one color for emphasis, one for base
- Create geometric patterns with the pair
- Apply duotone to images
- Make CTAs in accent color
- Maintain strict adherence to two colors

## Don'ts
- Add third colors
- Use gradients between the two
- Create intermediate shades
- Apply random color assignments
- Mix warm and cool tones inconsistently
- Use the two colors without intention
- Add subtle tones or off-colors
- Include grayscale elements

## Agent Instructions
- Restrict palette to exactly two colors
- Define primary and secondary clearly
- Apply colors with purpose
- Use contrast for hierarchy
- Create geometric patterns
- Apply duotone treatment to images
- Maintain strict two-color rule
- Ensure accessible contrast ratios

## Output Constraints
- HTML/CSS: CSS custom properties for pair
- React: Duotone theme with two colors
- Colors: Exactly two
- No shades or gradients
- Image treatment: Duotone SVG filter
- Pattern: Geometric two-color
- Contrast: 4.5:1 minimum

## Machine-Readable Rules
```json
{
  "name": "duotone-design",
  "category": "modes-color",
  "color_count": 2,
  "shades_allowed": false,
  "gradient_allowed": false,
  "duotone_images": true,
  "contrast_min": 4.5,
  "pattern_potential": true,
  "brand_flexible": true
}
```
