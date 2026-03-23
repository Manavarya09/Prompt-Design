# High Contrast Accessibility UI

## Intent
Create interfaces that exceed accessibility standards, ensuring all users including those with visual impairments can access and interact with content effectively.

## Principles
1. **WCAG AAA compliance** - Target highest standards
2. **No assumptions** - Design for diverse abilities
3. **Maximum contrast** - 7:1 ratio minimum for text
4. **Clear focus states** - Visible keyboard navigation
5. **Redundant coding** - Color + pattern + text for meaning

## Layout Rules
- Clear visual separation between elements
- Minimum touch targets: 44x44px
- Generous spacing between interactive elements
- No reliance on color alone for information
- Consistent, predictable navigation
- Breadcrumbs for orientation
- Skip navigation links
- Resizable text up to 200%

## Typography
- Font: Highly legible sans-serif (Atkinson Hyperlegible, Lexend)
- Base size: 16-18px minimum
- Body: 16-18px, Line-height: 1.5-1.6
- Headings: Bold, clearly larger
- Letter-spacing: Slightly increased
- All caps avoided except short labels
- Minimum font size: 14px for any text

## Colors
- Background: Pure white (#FFFFFF)
- Text: Pure black (#000000)
- Links: Dark blue (#0000EE) underlined
- Focus: Thick outline (3px minimum)
- Error: Red border + icon + text
- Success: Green border + checkmark + text
- Interactive: Dark outline or fill
- High contrast mode support

## Components
- Accessible Buttons: Large, clear text, thick borders
- Focus Indicators: 3px solid outline, high contrast
- Form Labels: Always visible, associated with inputs
- Error Messages: Icon + color + text
- Required Fields: Asterisk + label + aria-required
- Skip Links: First focusable element
- Alternative Text: Required for all images
- ARIA Labels: Where visual context missing

## Do's
- Target WCAG AAA (7:1 contrast)
- Use 44x44px minimum touch targets
- Provide multiple indicators for states
- Include focus-visible styles
- Add skip links for keyboard users
- Use clear, consistent navigation
- Test with screen readers
- Support browser zoom to 200%

## Don'ts
- Use decorative elements only
- Rely solely on color for meaning
- Create small, cramped interfaces
- Use placeholder text as labels
- Hide essential content visually
- Use blinking or flashing content
- Create complex nested tables
- Assume all users can see color

## Agent Instructions
- Apply 7:1 contrast minimum
- Use 44x44px touch targets
- Add visible focus states (3px outline)
- Include aria-labels and roles
- Ensure color is not sole indicator
- Add skip links
- Use clear, associated labels
- Test with accessibility tools
- Support text resize without loss

## Output Constraints
- HTML/CSS: ARIA attributes, focus styles
- React: Accessibility props required
- Contrast: 7:1 (AAA), 4.5:1 (AA) minimum
- Touch targets: 44px minimum
- Focus outline: 3px solid
- Font size: 16px minimum
- Line height: 1.5 minimum

## Machine-Readable Rules
```json
{
  "name": "high-contrast-accessibility",
  "category": "modes-color",
  "contrast_min": 7,
  "contrast_aaa_target": true,
  "touch_target_min": 44,
  "focus_outline": 3,
  "aria_required": true,
  "skip_links": true,
  "zoom_support": 200,
  "color_not sole_indicator": true,
  "wcag_level": "AAA"
}
```
