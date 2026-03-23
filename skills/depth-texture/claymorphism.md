# Claymorphism

## Intent
Create playful, tactile 3D interfaces that resemble soft clay or modeling compound, with rounded forms and glossy highlights.

## Principles
1. **Playful volume** - Elements appear sculpted and squeezable
2. **Glossy highlights** - Shiny reflections suggest smooth material
3. **Soft extrusion** - Elements push out with generous radius
4. **Pastel palette** - Muted, friendly colors
5. **Tactile presence** - Interfaces feel touchable and interactive

## Layout Rules
- Generous spacing: 20-32px between elements
- Large border-radius: 24-48px for major elements
- Floating elements with soft shadows
- Depth through overlapping shapes
- Layered z-index for dimensionality
- Background: Subtle gradient or solid pastel
- Pill and capsule shapes preferred
- Organic, friendly curves

## Typography
- Font: Rounded sans-serif (Nunito, Quicksand, Poppins)
- Soft, approachable weights (Medium, Semibold)
- Title: 24-32px semibold
- Body: 14-16px regular
- Rounded letterforms where possible
- Generous line-height: 1.5-1.6
- Playful but readable

## Colors
- Primary pastel: Soft pink, blue, purple, mint, peach
- Highlight: White with transparency
- Shadow: Muted version of element color
- Background: Light lavender, peach, or mint
- Text: Dark gray (#2D3748)
- Accent: Vibrant pastel (hot pink, electric blue)
- Inner shadows for depth
- Gloss overlay effects

## Components
- Clay Buttons: Raised, glossy, rounded pill shape
- Clay Cards: Soft floating elements with shadows
- Clay Avatars: Circular with highlight and shadow
- Clay Icons: Rounded with inner shadows
- Clay Toggles: Soft rounded track with raised thumb
- Clay Progress: Pill-shaped with animated fill
- Clay Badges: Small rounded pills
- Clay Navigation: Soft floating pill bar

## Do's
- Use large border-radius (24px+)
- Add inner highlight (top) and shadow (bottom)
- Apply glossy overlay effect
- Use soft pastel colors
- Create playful animations (bounce, squish)
- Layer elements for depth
- Maintain friendly, approachable tone
- Use capsule shapes for buttons

## Don'ts
- Use sharp corners anywhere
- Create flat, 2D elements
- Use harsh drop shadows
- Apply muted, corporate colors
- Overcrowd the interface
- Use serif or serious fonts
- Create rigid grid alignments
- Mix with minimalist styles

## Agent Instructions
- Apply large border-radius (24-48px)
- Use dual inner shadows for 3D effect
- Add subtle top highlight (white overlay)
- Create outer shadow for floating effect
- Use pastel color palette
- Apply bounce animations
- Maintain rounded aesthetic throughout
- Create glossy, squeezable appearance

## Output Constraints
- HTML/CSS: Multiple box-shadows, gradients
- React: Clay component with 3D effects
- Border-radius: 24-48px
- Shadows: Inner + outer combined
- Animations: Bouncy, spring-like
- Color: Pastels only

## Machine-Readable Rules
```json
{
  "name": "claymorphism",
  "category": "depth-texture",
  "border_radius_min": 24,
  "colors": "pastel",
  "highlight": true,
  "inner_shadow": true,
  "gloss_effect": true,
  "animations": "bouncy",
  "shapes": "rounded",
  "spacing_generous": true
}
```
