# E-commerce Conversion UI

## Intent
Create interfaces optimized for purchase completion, guiding users through discovery to checkout with minimal friction and maximum persuasion.

## Principles
1. **Reduce friction** - Every step should be effortless
2. **Build trust** - Encourage purchase confidence
3. **Create urgency** - Timely incentives
4. **Social proof** - Reviews and popularity
5. **Clear pricing** - No hidden costs

## Layout Rules
- Homepage: Hero → Categories → Featured → Reviews
- Product page: Image → Info → Actions
- Cart: Items → Summary → Checkout
- Sticky add-to-cart
- Progress indicators
- Related products
- 16px base spacing
- Mobile-first product grid

## Typography
- Font: Modern sans-serif (Inter, Plus Jakarta Sans)
- Price: 28-36px bold
- Product title: 20-24px semibold
- Body: 14-16px regular
- Sale price: Bold red/green
- Review stars: Icon-based
- Button text: 14-16px bold

## Colors
- Primary: Black (#000000) or dark blue
- Accent: Orange (#FF5722) or brand color
- Sale: Red (#DC2626)
- Success: Green (#059669)
- Background: White or light
- Cards: White with shadow
- Trust badges: Various colors
- Urgency: Bright accent

## Components
- Product Cards: Image, title, price, rating, CTA
- Add to Cart: Prominent, sticky option
- Cart Drawer: Slide-in cart summary
- Price Display: Original + sale + savings
- Rating Stars: Gold stars with count
- Trust Badges: Secure, free shipping, returns
- Promo Banner: Scarcity/urgency
- Size Selector: Grid of options
- Image Gallery: Zoom and swipe

## Do's
- Make add-to-cart highly visible
- Show prices prominently
- Include review ratings
- Add trust badges
- Display shipping info early
- Show product availability
- Include related products
- Support wishlist/save

## Don'ts
- Hide total costs
- Complicate checkout
- Use confusing navigation
- Slow page loads
- Lack mobile optimization
- Use misleading pricing
- Hide return policy
- Create registration walls

## Agent Instructions
- Create prominent CTAs
- Show prices clearly
- Add rating displays
- Include trust signals
- Display shipping info
- Show stock status
- Add urgency elements
- Optimize checkout flow

## Output Constraints
- HTML/CSS: E-commerce optimized
- React: Product components
- Mobile-first: Responsive
- Performance: Fast loading
- CTAs: High visibility
- Trust: Signals present

## Machine-Readable Rules
```json
{
  "name": "ecommerce-conversion",
  "category": "product-oriented",
  "cta_prominent": true,
  "pricing_clear": true,
  "reviews_visible": true,
  "trust_badges": true,
  "shipping_info": true,
  "friction_minimal": true,
  "mobile_first": true,
  "urgency_enabled": true
}
```
