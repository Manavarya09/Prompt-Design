# Soft UI (Modern Neumorphism)

## Intent
Create gentle, refined interfaces that blend neumorphic depth with improved accessibility, using subtle shadows and muted tones.

## Principles
1. **Refined softness** - Gentler than classic neumorphism
2. **Better contrast** - Accessible without losing depth
3. **Modern palette** - Sophisticated muted colors
4. **Purposeful shadows** - Depth serves hierarchy
5. **Subtle differentiation** - Elements distinguish through light

## Layout Rules
- Background: Off-white, light gray, or soft tint
- Spacing: 16-24px consistent
- Border-radius: 16-20px
- Floating elements with soft shadows
- Card sections with subtle elevation
- Grid-aligned but organic feel
- Balanced use of convex/concave
- Touch targets: 48px minimum

## Typography
- Font: Inter, Plus Jakarta Sans, or DM Sans
- Weight hierarchy: Light, Regular, Medium, Semibold
- Title: 20-24px semibold
- Body: 14-16px regular
- Line-height: 1.5-1.6
- Dark gray text for contrast
- Uppercase labels: 11-12px, letter-spacing 0.05em

## Colors
- Background: #F3F4F6 or warm white
- Dark shadow: rgba(0,0,0,0.08)
- Light shadow: rgba(255,255,255,0.7)
- Text primary: #374151
- Text secondary: #6B7280
- Accent: Muted teal, lavender, or coral
- Active: Inset shadow effect
- Subtle gradient backgrounds optional

## Components
- Soft Buttons: Raised with shadow, press effect
- Soft Cards: Elevated with gentle shadow
- Soft Inputs: Inset or flat with border
- Soft Tabs: Underline indicator
- Soft Toggles: Pill with smooth transition
- Soft Icons: Subtle shadow icons
- Soft Progress: Rounded bar with gradient
- Soft Badges: Rounded pills

## Do's
- Maintain higher contrast than classic neumorphism
- Use consistent shadow values
- Apply convex/concave appropriately
- Keep palette muted and sophisticated
- Use 4.5:1 contrast minimum
- Add subtle hover transitions
- Include pressed states
- Balance depth with clarity

## Don'ts
- Use pure white with strong shadows
- Create low-contrast text
- Mix shadow intensities randomly
- Apply neumorphism to small elements
- Use harsh color accents
- Stack shadows excessively
- Ignore accessibility
- Over-shadow the interface

## Agent Instructions
- Use shadow values: blur 20-30px, distance 8-12px
- Maintain 4.5:1 contrast minimum
- Apply subtle shadows, not dramatic
- Use inset for active/pressed states
- Keep border-radius consistent
- Select muted, sophisticated colors
- Add smooth transition animations
- Ensure all interactive elements have focus states

## Output Constraints
- HTML/CSS: Box-shadow with soft values
- React: SoftUI component library
- Contrast: 4.5:1 minimum
- Border-radius: 16-20px
- Shadow blur: 20-30px
- Colors: Muted sophistication

## Machine-Readable Rules
```json
{
  "name": "soft-ui",
  "category": "depth-texture",
  "contrast_min": 4.5,
  "border_radius": 18,
  "shadow_blur": 25,
  "shadow_distance": 10,
  "colors": "muted",
  "background": "off-white",
  "convex_default": true,
  "concave_active": true
}
```
