# Mobile-First UI

## Intent
Create touch-optimized interfaces that prioritize mobile users, ensuring excellent experiences before scaling to larger screens.

## Principles
1. **Touch-first design** - Finger-friendly interactions
2. **Content prioritization** - Most important first
3. **Progressive enhancement** - Mobile base, desktop extension
4. **Thumb-zone optimization** - Key actions in easy reach
5. **Performance critical** - Fast loading on mobile data

## Layout Rules
- 100% width mobile layouts
- Bottom navigation (3-5 items)
- Swipe-friendly content
- Collapsible sections
- Sticky headers
- Full-width cards
- 16px minimum touch spacing
- Safe area padding

## Typography
- Font: System fonts (SF Pro, Roboto)
- Base: 16px minimum
- Body: 16-18px
- Titles: 20-24px
- Buttons: 16-18px bold
- Line-height: 1.4-1.5
- Avoid small text
- Sufficient contrast

## Colors
- Primary: Strong brand color
- Background: White or light
- Text: Dark for readability
- Interactive: Color + size + icon
- Status: Clear colors
- Touch feedback: Ripple/highlight
- High contrast

## Components
- Bottom Navigation: Icon + label, 5 max
- Full-width Buttons: 48px height min
- Swipe Cards: Card actions on swipe
- Pull to Refresh: Gesture support
- Bottom Sheets: Modal from bottom
- Expandable Lists: Accordion sections
- Full-screen Modals: Mobile-specific
- Floating Action Button: Primary action

## Do's
- Use 44x44px minimum touch targets
- Place key actions in thumb zone
- Support swipe gestures
- Stack content vertically
- Use full screen width
- Include back navigation
- Add loading skeletons
- Optimize images for mobile

## Don'ts
- Use hover states as primary
- Create tiny touch targets
- Require precise interactions
- Use horizontal scrolling
- Load heavy assets
- Hide navigation
- Use small fonts
- Create complex gestures

## Agent Instructions
- Set 16px minimum font
- Use 44x44px touch targets
- Place actions in thumb zone
- Create bottom navigation
- Support swipe gestures
- Stack layouts vertically
- Add loading states
- Optimize for performance

## Output Constraints
- HTML/CSS: Mobile-first CSS
- React: Touch component library
- Touch targets: 44px min
- Font size: 16px min
- Performance: Lighthouse optimized
- Gestures: Swipe support

## Machine-Readable Rules
```json
{
  "name": "mobile-first-ui",
  "category": "product-oriented",
  "touch_target_min": 44,
  "font_min": 16,
  "navigation": "bottom",
  "swipe_support": true,
  "thumb_zone": true,
  "performance": "critical",
  "stacked_layout": true,
  "gestures": ["swipe","pull"]
}
```
