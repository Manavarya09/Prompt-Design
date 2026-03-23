# Super App UI

## Intent
Create dense, feature-rich interfaces that pack multiple services into one cohesive app, balancing functionality with usability.

## Principles
1. **Service discovery** - Easy navigation between services
2. **Information density** - Pack in the value
3. **Clear categorization** - Services organized logically
4. **Quick actions** - Jump to common tasks
5. **Context awareness** - Relevant suggestions

## Layout Rules
- Dashboard home with service shortcuts
- Tab bar: 5-8 services
- Dense card grid
- Scrollable sections
- Pull-down quick actions
- Bottom sheet for details
- Nested navigation
- Persistent search

## Typography
- Font: System sans-serif (performance)
- Section headers: 16-18px semibold
- Card titles: 14-16px medium
- Body: 12-14px regular
- Dense but readable
- Clear hierarchy
- Icon + text labels
- Tab bar: 10-11px

## Colors
- Primary: Strong brand color
- Service colors: Per-service identification
- Background: Light gray
- Cards: White
- Status: Standard (green, yellow, red)
- Tab bar: Contrast with content
- Quick actions: Accent highlights

## Components
- Service Cards: Icon, name, shortcut action
- Tab Bar: 5-8 services
- Quick Actions: Grid of shortcuts
- Notification Badge: Red dot count
- Service Headers: Per-service branding
- Transaction List: Compact format
- Balance Widget: Dashboard summary
- Bottom Sheet: Detailed views

## Do's
- Create clear service hierarchy
- Enable quick switching
- Pack useful shortcuts
- Show notification badges
- Support deep linking
- Include search everywhere
- Balance density with clarity
- Provide contextual actions

## Don'ts
- Create overwhelming interfaces
- Hide services too deep
- Use inconsistent patterns
- Ignore performance
- Overload home screen
- Use tiny text
- Ignore service identity
- Create slow navigation

## Agent Instructions
- Create dashboard with shortcuts
- Use tab bar navigation
- Pack density appropriately
- Add notification badges
- Support quick actions
- Include global search
- Organize services clearly
- Balance information density

## Output Constraints
- HTML/CSS: Dense layouts
- React: Super app components
- Touch targets: 44px min
- Performance: Lazy loading
- Navigation: Tab-based
- Density: Medium-high

## Machine-Readable Rules
```json
{
  "name": "super-app-ui",
  "category": "product-oriented",
  "services_count": [5, 8],
  "tab_navigation": true,
  "density": "high",
  "quick_actions": true,
  "search_global": true,
  "notifications": true,
  "deep_linking": true,
  "performance": "critical"
}
```
