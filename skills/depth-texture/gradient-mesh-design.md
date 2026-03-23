# Gradient Mesh Design

## Intent
Create visually stunning interfaces using complex, flowing gradient backgrounds that establish mood and depth through organic color blending.

## Principles
1. **Organic flow** - Gradients create natural movement
2. **Color harmony** - Blended hues work together
3. **Depth illusion** - Multiple layers suggest 3D space
4. **Mood setting** - Colors evoke emotion
5. **Background dominance** - Gradients are hero elements

## Layout Rules
- Full-bleed gradient backgrounds
- Floating content over mesh gradients
- Glass panels for content organization
- Centered or asymmetric layouts
- 32px+ padding for content
- Layered depth: gradient → shapes → content
- Large viewports for full effect
- Responsive with simplified gradient on mobile

## Typography
- Font: Geometric sans-serif (Poppins,Montserrat,Outfit)
- Bold weights for headings
- Title: 28-40px bold
- Subtitle: 18-24px semibold
- Body: 14-16px regular
- White or dark text for contrast over gradients
- Text shadows for readability
- Letter-spacing: 0.02-0.05em

## Colors
- Gradient mesh: 3-5 colors blended
- Popular: Purple/blue/pink, orange/yellow/pink, teal/blue/green
- Floating shapes: Semi-transparent white or accent
- Text: White on dark areas, dark on light areas
- Cards: Glass effect over gradient
- Buttons: Solid or gradient fills
- Subtle grain texture optional

## Components
- Mesh Backgrounds: CSS or SVG gradient meshes
- Floating Shapes: Blurred circles/ellipses
- Glass Cards: Frosted overlay on gradient
- Gradient Buttons: Matching mesh colors
- Hero Sections: Full-bleed mesh with centered text
- Navigation: Transparent or glass over mesh
- CTA Sections: Contrasting gradient panels

## Do's
- Use smooth, flowing gradients
- Blend 3-5 complementary colors
- Add floating blur shapes for depth
- Use glass cards for content
- Ensure text contrast over gradients
- Include subtle noise texture
- Layer background elements
- Match component colors to mesh palette

## Don'ts
- Use jarring color transitions
- Apply gradients to small elements
- Create gradients with clashing colors
- Bury content under complex backgrounds
- Use gradients on text directly
- Ignore mobile gradient performance
- Add too many floating shapes
- Use low-quality gradient images

## Agent Instructions
- Create gradient with 3-5 blended colors
- Add floating blur shapes (30-50% opacity)
- Use glass cards for content containers
- Apply subtle grain texture overlay
- Ensure contrast for readability
- Use color palette consistently
- Optimize gradient for performance
- Support reduced-motion preferences

## Output Constraints
- HTML/CSS: CSS gradients, SVG, or canvas
- React: Gradient mesh background component
- Colors: 3-5 harmonious hues
- Blur shapes: backdrop-filter: blur(80-150px)
- Performance: GPU-accelerated properties
- Fallback: Solid gradient for low-performance

## Machine-Readable Rules
```json
{
  "name": "gradient-mesh-design",
  "category": "depth-texture",
  "colors_count": [3, 5],
  "blur_shapes": true,
  "background_fullbleed": true,
  "glass_cards": true,
  "grain_texture": true,
  "performance_optimized": true,
  "responsive_simplify": true,
  "contrast_enforced": true
}
```
