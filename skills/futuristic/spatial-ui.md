# Spatial UI

## Intent
Create immersive three-dimensional interfaces that leverage depth, parallax, and layering to create spatial relationships between elements.

## Principles
1. **Z-axis design** - Depth is a design element
2. **Parallax motion** - Layers move at different speeds
3. **Occlusion** - Elements block what's behind
4. **Spatial memory** - Users remember where things are
5. **Immersive depth** - Truly 3D experience

## Layout Rules
- Multiple depth layers
- Perspective containers
- Floating cards at various z-levels
- Parallax scroll effects
- 3D transforms for elements
- Depth-based opacity
- Spatial groupings
- Perspective origin centered

## Typography
- Font: Clean, modern sans-serif
- Distant text: Smaller, more transparent
- Close text: Larger, more opaque
- Title: 32-48px bold
- Body: 14-16px regular
- Consistent 3D transformations
- Backface text treatment

## Colors
- Background: Gradient or space-like
- Far layers: Desaturated, small
- Mid layers: Full color
- Near layers: Full saturation, large
- Shadows: Deep, directional
- Overlays: Semi-transparent
- Depth fog: Gradient fade

## Components
- Spatial Cards: 3D transformed, floating
- Parallax Sections: Multi-layer scroll
- Depth Layers: Background, mid, foreground
- 3D Buttons: Perspective hover
- Floating Windows: Draggable in space
- Depth Toggle: Switch between 2D/3D
- Spatial Navigation: Breadcrumb in space
- Immersive Hero: Multi-layer depth

## Do's
- Create clear depth hierarchy
- Use parallax appropriately
- Maintain readability at all depths
- Support 2D fallback
- Use smooth transitions
- Create spatial groupings
- Add subtle shadows
- Support reduced motion

## Don'ts
- Overwhelm with 3D
- Create dizzying effects
- Ignore accessibility
- Use jarring animations
- Hide content in layers
- Create performance issues
- Forget 2D users
- Use excessive depth

## Agent Instructions
- Apply 3D transforms to elements
- Create parallax scroll effects
- Use perspective containers
- Add depth shadows
- Maintain readability
- Support reduced motion
- Provide 2D fallback
- Balance immersion and usability

## Output Constraints
- HTML/CSS: CSS 3D transforms
- React: Three.js or CSS 3D
- Perspective: 1000-2000px
- Transform: rotateX/Y, translateZ
- Parallax: CSS or JS
- Performance: GPU accelerated

## Machine-Readable Rules
```json
{
  "name": "spatial-ui",
  "category": "futuristic",
  "perspective": 1500,
  "depth_layers": [3, 5],
  "parallax": true,
  "3d_transforms": true,
  "shadow_depth": true,
  "reduced_motion": true,
  "2d_fallback": true,
  "performance": "optimized"
}
```
