# Neumorphism

## Intent
Create soft, extruded interfaces that appear to emerge from the background, combining subtle shadows to suggest 3D depth without harsh contrasts.

## Principles
1. **Extruded surfaces** - Elements appear to push out from background
2. **Monochromatic palette** - Single hue with light/dark variations
3. **Convex and concave** - Some elements raised, others pressed
4. **Soft shadows** - No hard edges, only diffuse shadow transitions
5. **Background unity** - UI elements share background color with surface

## Layout Rules
- Single background color throughout
- Elements share background color (no white cards)
- Consistent element spacing: 16-24px
- Rounded corners everywhere (12-24px radius)
- Flat layouts, minimal elevation
- Soft grid alignment
- Generous padding for touch targets
- Consistent component sizing

## Typography
- Font: Clean sans-serif (Inter, Nunito, Poppins)
- Soft weight variations (Light, Regular, Medium)
- Title: 20-24px semibold
- Body: 14-16px regular
- Labels: 12-14px medium
- Subtle text shadows for depth
- High readability despite soft UI

## Colors
- Background: Light gray (#E0E5EC) or off-white
- Shadow dark: rgba(0,0,0,0.15-0.25)
- Shadow light: rgba(255,255,255,0.8)
- Text: Dark gray (#4A5568)
- Accent: Muted pastel versions
- Active state: Inset shadows (concave)
- No harsh contrasts

## Components
- Neumorphic Buttons: Raised, soft shadow, press animation
- Neumorphic Cards: Subtle extrusion, same color as background
- Neumorphic Inputs: Inset (pressed in) appearance
- Neumorphic Toggles: Pill with sliding circle
- Neumorphic Sliders: Track and thumb with depth
- Neumorphic Icons: Soft shadow icons
- Neumorphic Progress: Rounded bar with inner shadow

## Do's
- Use dual shadows (light top-left, dark bottom-right)
- Match element color to background
- Apply convex (raised) for inactive, concave (pressed) for active
- Use large border-radius for softness
- Create smooth transition animations
- Keep entire UI monochromatic
- Use subtle accent colors sparingly
- Apply same shadow distance and blur for consistency

## Don'ts
- Mix neumorphism with flat design
- Use white backgrounds with shadowed elements
- Apply harsh drop shadows
- Use multiple background colors
- Create sharp corners
- Combine with high-contrast elements
- Use neumorphism for detailed graphics
- Ignore accessibility of low-contrast text

## Agent Instructions
- Use background color for all elements
- Apply two-box-shadow: dark (bottom-right), light (top-left)
- Match shadow blur and distance
- Use border-radius: 16-20px minimum
- Create inset shadow for active/pressed states
- Keep palette monochromatic
- Avoid mixing with other design styles
- Ensure 4.5:1 contrast for text

## Output Constraints
- HTML/CSS: Box-shadow with dual shadows
- React: Neumorphic component variants
- Border-radius: 12-24px
- Shadow blur: 15-30px
- Shadow distance: 5-10px
- Transition: 150-200ms
- Single background color required

## Machine-Readable Rules
```json
{
  "name": "neumorphism",
  "category": "depth-texture",
  "background_required": "monochromatic",
  "border_radius_min": 16,
  "shadow_type": "dual",
  "shadow_blur": 20,
  "shadow_distance": 6,
  "contrast_min": 4.5,
  "color_palette": "monochrome",
  "corners": "rounded"
}
```
