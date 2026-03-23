# Dark Mode Minimal

## Intent
Create elegant, battery-efficient interfaces using dark backgrounds with carefully selected accent colors, prioritizing visual comfort and focus.

## Principles
1. **True dark backgrounds** - Not gray, but near-black
2. **Reduced eye strain** - Lower brightness overall
3. **Accent pop** - Colors stand out against dark
4. **Focus enhancement** - Dark recedes, content advances
5. **Battery efficiency** - OLED-friendly pure blacks

## Layout Rules
- Pure black (#000000) or near-black (#0A0A0A) backgrounds
- Card surfaces: Slightly elevated dark (#121212, #1A1A1A)
- Generous spacing for clarity
- Single column or asymmetric layouts
- Minimum 16px margins
- Floating elements with subtle elevation
- Dark navigation bars
- Consistent dark theme throughout

## Typography
- Font: System dark-mode optimized (SF Pro, Segoe UI, Roboto)
- Title: 24-32px semibold
- Body: 14-16px regular
- Reduced weight compared to light mode
- High contrast: White (#FFFFFF) or light gray (#E0E0E0)
- Subtle text shadows for readability
- Monospace for code

## Colors
- Background: Pure black (#000000)
- Surface: #121212, #1A1A1A, #1E1E1E
- Primary text: #FFFFFF
- Secondary text: #A0A0A0
- Accent: Electric blue (#00D4FF), green (#00FF88), or purple (#BB86FC)
- Borders: #2A2A2A
- Success: #00FF88
- Warning: #FFD600
- Error: #FF5252

## Components
- Dark Cards: Elevated surface color with subtle border
- Dark Buttons: Filled accent or ghost style
- Dark Inputs: Dark background with light border
- Dark Navigation: #0A0A0A bar with light text
- Dark Toggles: Dark track with accent thumb
- Dark Progress: Dark bar with accent fill
- Dark Modals: Dark overlay with elevated card
- Dark Chips: Small accent-bordered tags

## Do's
- Use pure black for true OLED efficiency
- Elevate surfaces with slight lightness increase
- Use accent colors sparingly for impact
- Maintain 4.5:1 contrast ratio
- Apply subtle glow to accent elements
- Reduce text weight slightly
- Use rounded corners (8-12px)
- Include smooth transition between modes

## Don'ts
- Use gray backgrounds instead of black
- Apply white backgrounds for cards
- Use bright, jarring accent colors
- Create harsh contrast edges
- Ignore color temperature (cool vs warm darks)
- Over-brighten text
- Use blue light filters inconsistently
- Mix light mode components

## Agent Instructions
- Apply pure black (#000000) as background
- Use #121212-#1E1E1E for elevated surfaces
- Ensure white text on dark backgrounds
- Use accent sparingly (buttons, focus states)
- Add subtle border to define surfaces
- Include glow effects on accent elements
- Maintain consistent elevation hierarchy
- Support system dark mode preference

## Output Constraints
- HTML/CSS: CSS variables for theming
- React: useDarkMode hook or context
- Contrast: 4.5:1 minimum
- Surface elevation: 3 levels max
- Transition: 200ms for theme switching
- System preference: prefers-color-scheme

## Machine-Readable Rules
```json
{
  "name": "dark-mode-minimal",
  "category": "modes-color",
  "background": "#000000",
  "surface_levels": ["#121212","#1A1A1A","#1E1E1E"],
  "text_primary": "#FFFFFF",
  "text_secondary": "#A0A0A0",
  "contrast_min": 4.5,
  "accent_limited": true,
  "border_color": "#2A2A2A",
  "system_support": true
}
```
