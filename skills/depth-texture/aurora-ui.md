# Aurora UI

## Intent
Create mesmerizing, living interfaces with animated gradients and light effects that evoke natural aurora phenomena, bringing energy and movement to digital spaces.

## Principles
1. **Living motion** - Gradients shift and breathe
2. **Natural flow** - Inspired by aurora borealis
3. **Ambient energy** - Interface feels alive
4. **Layered lights** - Multiple overlapping aurora bands
5. **Performance balanced** - Stunning without lag

## Layout Rules
- Full-viewport aurora backgrounds
- Content floats above animated layers
- Fixed or parallax aurora behind scrollable content
- Glass containers for readable content
- Dark background for aurora vibrancy
- 24-32px content padding
- Breathing room between elements
- Layered z-index for depth

## Typography
- Font: Futuristic sans-serif (Exo 2, Orbitron, Rajdhani)
- Mix of bold headlines and light body
- Title: 32-48px bold
- Subtitle: 18-24px medium
- Body: 14-16px regular
- Glow effects on headlines
- White text for contrast
- Letter-spacing: 0.02-0.1em for headings

## Colors
- Aurora bands: Cyan, magenta, purple, green, blue
- Background: Deep dark (#0A0A1A or #111827)
- Glow effects: Matching aurora colors
- Text: White or light gray
- Accent glow: Soft color bleeding
- Floating particles: Tiny light dots
- Border glow: Subtle colored edges

## Components
- Aurora Backgrounds: Animated multi-layer gradients
- Glow Text: Text with soft color glow
- Aurora Cards: Dark cards with edge glow
- Pulsing Buttons: Animated glow on buttons
- Particle Effects: Floating light dots
- Aurora Borders: Glowing dividers
- Progress Bars: With flowing gradient animation
- Loading States: Spinning aurora rings

## Do's
- Animate gradients smoothly (CSS keyframes)
- Layer 3-4 aurora bands
- Use backdrop-filter for depth
- Add subtle floating particles
- Create glow effects on interactive elements
- Use dark background for contrast
- Implement reduced-motion support
- Balance animation with readability

## Don'ts
- Use fast, jarring animations
- Create seizure-inducing effects
- Ignore reduced-motion preferences
- Apply animation to text readability
- Use too many moving elements
- Create high CPU/GPU load
- Mix with flat or minimalist styles
- Animate without pause or stop

## Agent Instructions
- Create CSS keyframe animations for aurora
- Layer 3-4 gradient bands with different speeds
- Use transform: translate for performance
- Add subtle glow shadows
- Implement prefers-reduced-motion
- Use dark backgrounds
- Ensure 60fps performance target
- Add floating particle elements

## Output Constraints
- HTML/CSS: CSS animations, WebGL optional
- React: Aurora background component with hooks
- Animation duration: 10-30s for smooth loops
- Performance: RequestAnimationFrame, will-change
- Reduced motion: Static gradient fallback
- Particle count: 10-20 per viewport

## Machine-Readable Rules
```json
{
  "name": "aurora-ui",
  "category": "depth-texture",
  "animation_required": true,
  "layer_count": [3, 4],
  "colors": ["cyan","magenta","purple","green"],
  "background": "dark",
  "glow_effects": true,
  "particles": true,
  "performance_target": 60,
  "reduced_motion_support": true,
  "animation_duration": 20
}
```
