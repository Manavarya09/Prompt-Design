# AI-Native UI

## Intent
Design interfaces that embrace AI capabilities, featuring prompt-first interactions, conversational elements, and dynamic content generation.

## Principles
1. **Prompt-first** - Natural language input central
2. **Conversational** - Dialogue-based interactions
3. **Dynamic content** - AI-generated in real-time
4. **Adaptive** - Learns user preferences
5. **Transparent AI** - Show how AI works

## Layout Rules
- Central prompt/input area
- Chat-style message threads
- Streaming response display
- Context sidebar (optional)
- Expandable response sections
- Full-width input on mobile
- Asymmetric conversation bubbles
- Loading/typing indicators

## Typography
- Font: Clean sans-serif (Inter, DM Sans)
- Messages: 14-16px regular
- User messages: Right-aligned
- AI responses: Left-aligned, slightly larger
- Code blocks: Monospace
- Clear message separation
- Timestamp: 11-12px muted

## Colors
- Background: Light or dark (toggle)
- User bubbles: Brand primary
- AI bubbles: Light gray or secondary
- Input area: Elevated surface
- Streaming text: Animated gradient
- Confidence indicators: Green/yellow/red
- Model indicator: Subtle badge

## Components
- Prompt Input: Large, expandable textarea
- Message Bubbles: Rounded, timestamped
- Streaming Text: Character-by-character reveal
- Code Blocks: Syntax highlighted
- Action Buttons: Regenerate, copy, expand
- Context Display: Source citations
- Thinking Indicator: AI "thinking" animation
- Conversation History: Collapsible thread

## Do's
- Feature prompt input prominently
- Show streaming responses
- Include message timestamps
- Support code highlighting
- Add regeneration options
- Show AI confidence
- Enable conversation history
- Support attachments

## Don'ts
- Hide the prompt interface
- Use slow loading states
- Make AI responses unclear
- Ignore error handling
- Create confusing message threading
- Use inconsistent message styles
- Hide AI limitations
- Overload with options

## Agent Instructions
- Create prominent prompt input
- Design chat-style layout
- Show streaming responses
- Add message bubbles
- Include action buttons
- Support code display
- Add loading indicators
- Show conversation history

## Output Constraints
- HTML/CSS: Chat interface
- React: Conversation components
- Streaming: Real-time updates
- Code: Syntax highlighting
- Input: Expandable textarea
- Animation: Typing effect

## Machine-Readable Rules
```json
{
  "name": "ai-native-ui",
  "category": "futuristic",
  "prompt_central": true,
  "chat_interface": true,
  "streaming": true,
  "code_blocks": true,
  "message_bubbles": true,
  "history_visible": true,
  "action_buttons": true,
  "attachments": true
}
```
