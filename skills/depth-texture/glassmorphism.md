# Glassmorphism

## Intent
Create ethereal, translucent interfaces that use blur, transparency, and subtle borders to evoke glass-like depth and modern sophistication.

## Principles
1. **Translucency over opacity** - Background elements visible through surfaces
2. **Blur as depth** - Backdrop-filter creates layered depth perception
3. **Subtle borders** - Frosted edges define glass surfaces
4. **Color underlay** - Background colors tint the glass subtly
5. **Soft luminosity** - Light effects suggest physical glass materials

## Layout Rules
- Layered depth: Background → Content layers → Glass panels
- Generous padding inside glass elements (20-32px)
- Floating panels with consistent 16-24px gaps
- Centered modal dialogs
- Cards can overlap slightly for depth
- Background must have visual complexity (gradients, images, shapes)
- Z-index hierarchy: Background → Glass → Interactive elements

## Typography
- Font: Clean sans-serif (Inter, Poppins, SF Pro)
- High contrast text on glass surfaces
- Title: 24-32px semibold
- Body: 14-16px regular
- Labels: 12px medium
- Text shadow for readability over complex backgrounds
- Semi-bold weights for important text

## Colors
- Glass fill: rgba(255,255,255,0.1-0.3)
- Glass border: rgba(255,255,255,0.2-0.4)
- Background: Gradient or image base
- Text: White (#FFFFFF) or dark (#1A1A1A) depending on glass tint
- Accent: Vibrant colors for CTAs (cyan, purple, pink)
- Subtle inner glow effects
- Background colors influence glass tint

## Components
- Glass Cards: Blurred, translucent, white border
- Glass Buttons: Semi-transparent, blur on hover
- Glass Inputs: Frosted background, subtle border
- Glass Navigation: Translucent bar, blur backdrop
- Glass Modal: Centered with heavy blur overlay
- Glass Pills/Tags: Small translucent badges
- Glass Progress: Frosted progress bar
- Glass Tooltips: Small frosted info bubbles

## Do's
- Use backdrop-filter: blur(10-30px)
- Apply subtle white borders
- Ensure text remains readable
- Layer multiple glass elements for depth
- Use vibrant background colors
- Add subtle shadow for floating effect
- Include smooth transitions on interaction
- Pair with colored backgrounds

## Don'ts
- Use glass on solid white backgrounds
- Apply excessive blur (over 50px)
- Stack too many glass layers (max 3-4)
- Use glass for critical data displays
- Ignore contrast for accessibility
- Use low-contrast text on glass
- Create glass elements smaller than 100px wide

## Agent Instructions
- Apply backdrop-filter: blur(10-30px) to glass elements
- Use rgba backgrounds with 10-30% opacity
- Add subtle white borders: 1px rgba(255,255,255,0.2)
- Ensure complex background for glass to work
- Use drop shadows for floating effect
- Maintain 4.5:1 contrast ratio
- Include blur transition on hover
- Create layered depth with z-index

## Output Constraints
- HTML/CSS: backdrop-filter support, fallback for Safari
- React: Glass component with blur prop
- Blur: 10-30px range
- Border: 1px rgba(255,255,255,0.2)
- Transition: 200-300ms ease
- Fallback: Solid semi-transparent for unsupported browsers

## Machine-Readable Rules
```json
{
  "name": "glassmorphism",
  "category": "depth-texture",
  "blur_range": [10, 30],
  "glass_opacity": [0.1, 0.3],
  "border_opacity": [0.2, 0.4],
  "backdrop_filter": true,
  "background_required": "complex",
  "layer_max": 4,
  "contrast_min": 4.5,
  "transition_duration": 250
}
```
