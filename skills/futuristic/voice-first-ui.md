# Voice-First UI

## Intent
Design interfaces where voice interaction is primary, with minimal visual dependency and maximum accessibility for hands-free use.

## Principles
1. **Voice primary** - Speech is the main input
2. **Visual minimal** - Show only what's needed
3. **Always listening** - Ready when needed
4. **Audio feedback** - Sound as primary feedback
5. **Accessible design** - Hands-free by default

## Layout Rules
- Large touch targets (fallback)
- Minimal visual chrome
- Centered status indicator
- Waveform visualization
- Simple response display
- Full-screen listening mode
- Minimal navigation
- Compact default state

## Typography
- Font: Clear, legible (Inter, Roboto)
- Large text: 18-24px
- Voice transcripts: 16-18px
- High contrast
- Monospace for commands
- Clear hierarchy
- Scannable responses

## Colors
- Background: Dark or light (user preference)
- Listening: Pulsing accent
- Speaking: Animated gradient
- Idle: Subtle indicator
- Text: High contrast
- Waveform: Accent color
- Status: Green (ready), accent (active)

## Components
- Voice Button: Large, central, prominent
- Waveform: Audio visualization
- Transcript Display: Scrollable history
- Status Indicator: Always visible
- Command Hints: Suggested phrases
- Response Cards: Minimal, dismissible
- Listening Animation: Pulsing/radar
- Audio Player: Minimal controls

## Do's
- Create large voice activation
- Show listening state clearly
- Provide audio feedback
- Support fallback touch
- Display transcripts
- Offer command suggestions
- Show AI thinking state
- Enable preferences

## Don'ts
- Depend on visuals
- Create complex interfaces
- Require precision
- Ignore audio cues
- Make users look at screen
- Use tiny targets
- Create information overload
- Ignore background noise

## Agent Instructions
- Create prominent voice button
- Add waveform visualization
- Design transcript display
- Show listening state
- Provide audio feedback
- Support touch fallback
- Include command hints
- Keep visuals minimal

## Output Constraints
- HTML/CSS: Audio visualization
- React: Voice components
- Audio: Web Speech API
- Targets: 64px minimum
- Contrast: High
- Animation: Audio-reactive

## Machine-Readable Rules
```json
{
  "name": "voice-first-ui",
  "category": "futuristic",
  "voice_primary": true,
  "visual_minimal": true,
  "touch_target_min": 64,
  "waveform": true,
  "audio_feedback": true,
  "transcripts": true,
  "always_listening": true,
  "touch_fallback": true
}
```
