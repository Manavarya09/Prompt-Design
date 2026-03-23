# Gesture-Based UI

## Intent
Create touch interfaces optimized for gesture recognition, enabling natural, intuitive interactions without traditional UI elements.

## Principles
1. **Natural gestures** - Mirror real-world actions
2. **Discoverability** - Hint at possible gestures
3. **Physical feedback** - Haptic response
4. **Direct manipulation** - Touch objects directly
5. **Minimal chrome** - UI fades away

## Layout Rules
- Edge-to-edge content
- Gesture zones (swipe from edge)
- Invisible boundaries
- Progress indicators via gesture
- Content fills viewport
- No visible buttons (optional)
- Pull gestures for menus
- Pinch/zoom on content

## Typography
- Font: System sans-serif
- Dynamic type supported
- Scales with gesture (pinch zoom)
- Title: 24-32px
- Body: 16-18px
- High contrast for gestures
- Clear hierarchy

## Colors
- Background: Matches content
- Minimal chrome
- Accent: Interactive hints
- Haptic zones: Subtle indicators
- Progress: Color change
- Contextual: Based on content

## Components
- Swipeable Cards: Dismiss, actions
- Pull Navigation: Reveal menus
- Pinch Zoom: Content scaling
- Rotate Gesture: Object rotation
- Long Press: Context menus
- Edge Swipe: Navigation
- Two-Finger Scroll: Special modes
- Gesture Hints: First-use tutorial

## Do's
- Support standard gestures
- Provide haptic feedback
- Show gesture hints initially
- Allow undo/redo
- Support accessibility
- Create smooth animations
- Handle edge cases
- Include touch fallback

## Don'ts
- Use non-standard gestures
- Hide all UI (always provide hints)
- Ignore gesture conflicts
- Create imprecise targets
- Forget haptic feedback
- Make gestures required
- Ignore accessibility needs
- Create jarring animations

## Agent Instructions
- Support swipe, pinch, rotate
- Add haptic feedback
- Show gesture hints
- Create smooth animations
- Handle all gesture states
- Support accessibility
- Provide undo support
- Include visual feedback

## Output Constraints
- HTML/CSS: Touch event handling
- React: Gesture libraries (Framer Motion)
- Touch: Multi-touch support
- Haptics: Vibration API
- Animation: Spring physics
- Accessibility: VoiceOver/TalkBack

## Machine-Readable Rules
```json
{
  "name": "gesture-based-ui",
  "category": "futuristic",
  "gestures": ["swipe","pinch","rotate","long-press"],
  "haptic_feedback": true,
  "touch_targets": 44,
  "gesture_hints": true,
  "undo_support": true,
  "animation_smooth": true,
  "accessibility": true,
  "edge_swipe": true
}
```
