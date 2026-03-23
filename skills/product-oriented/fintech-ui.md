# Fintech UI

## Intent
Build trustworthy financial interfaces that prioritize data clarity, security perception, and regulatory compliance while maintaining modern aesthetics.

## Principles
1. **Trust above all** - Every element builds confidence
2. **Data accuracy** - Numbers must be correct
3. **Security perception** - Feels safe and protected
4. **Regulatory compliance** - Accessibility and clarity
5. **Professional clarity** - Clean, organized data

## Layout Rules
- Dashboard layout with key metrics
- 12-column grid
- Data tables with sorting/filtering
- Clear transaction lists
- Account summaries prominent
- Statement sections
- 16px base spacing
- Card-based account overview

## Typography
- Font: Clear, professional (Inter, Roboto)
- Numbers: Tabular figures, monospace optional
- Title: 24-32px semibold
- Body: 14-16px regular
- Small: 11-12px for timestamps
- Color-coded amounts (green/red)
- Clear currency formatting

## Colors
- Primary: Deep blue (#0F172A) or navy
- Accent: Trustworthy blue (#3B82F6)
- Background: Light gray (#F8FAFC)
- Cards: White
- Positive: Green (#10B981)
- Negative: Red (#EF4444)
- Borders: Light (#E2E8F0)
- Security: Green badges

## Components
- Account Cards: Balance, number, actions
- Transaction List: Date, merchant, amount, status
- Data Tables: Sortable, filterable, paginated
- Charts: Line (trends), donut (breakdown)
- Security Badges: Verified, protected indicators
- Action Buttons: Transfer, pay, receive
- Currency Inputs: Formatted, validated
- Status Indicators: Pending, complete, failed

## Do's
- Show account numbers clearly
- Display amounts prominently
- Include transaction timestamps
- Add security indicators
- Provide export options
- Show clear status states
- Enable search and filter
- Support multiple accounts

## Don'ts
- Use flashy animations
- Create cluttered data displays
- Hide important information
- Use ambiguous status colors
- Display incorrect formatting
- Ignore accessibility
- Use playful colors
- Create confusing flows

## Agent Instructions
- Apply professional color palette
- Use tabular numbers for alignment
- Create clear transaction lists
- Show amounts with proper formatting
- Add security indicators
- Include status badges
- Enable data export
- Support multiple currencies

## Output Constraints
- HTML/CSS: Data table styling
- React: Financial components
- Numbers: Tabular figures
- Currency: Proper formatting
- Tables: Sortable, filterable
- Accessibility: WCAG AA

## Machine-Readable Rules
```json
{
  "name": "fintech-ui",
  "category": "product-oriented",
  "professional": true,
  "data_accurate": true,
  "tabular_numbers": true,
  "currency_format": true,
  "security_indicators": true,
  "contrast_min": 4.5,
  "tables_sortable": true,
  "export_enabled": true
}
```
