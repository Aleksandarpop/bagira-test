# Funnel Analysis: БАГИРА (Bagira)
**URL:** https://www.bagira.bg/
**Date:** 2026-03-18
**Business Type:** E-commerce — Technical Hypermarket (Hardware/Tools/Home)
**Funnel Type:** E-commerce (Browse → Cart → Checkout)
**Overall Funnel Health: 38/100**

---

## Executive Summary

Bagira's e-commerce funnel has fundamental structural problems that are likely causing significant revenue loss. The most critical issue is **opaque delivery pricing** — customers outside Stara Zagora cannot see shipping costs until a staff member calls them. This alone could be responsible for 30-50% of cart abandonment.

The product pages are surprisingly well-structured with multiple conversion paths (Buy, Quick Order without registration, Installment financing, Reserve & pickup, Phone order, Inquiry). However, the funnel breaks at three critical points: (1) Homepage provides no guidance toward products, (2) Category pages lack content to aid decision-making, and (3) Delivery costs are hidden behind a phone call.

The site lacks essential e-commerce trust signals: no customer reviews (despite having star ratings), no return policy visibility on product pages, no delivery time estimates on product pages, and a 60% Facebook recommendation rate that suggests existing customer satisfaction issues.

**Estimated revenue opportunity:** Fixing the top 3 issues (transparent shipping, customer reviews, homepage CTA) could increase online conversion by 40-60%, potentially adding 15,000-25,000€/year in online revenue (estimated based on current traffic levels).

---

## Funnel Map

```
VISITOR JOURNEY MAP
===================

Traffic Sources (Google Ads, Facebook, Organic, Direct)
  |
  v
[HOMEPAGE] ─── 100% of visitors
  | No clear CTA, no product guidance
  | Estimated 60% bounce
  v
[CATEGORY PAGE] ─── ~40% click through
  | Product grid only, no buying guidance
  | Estimated 50% continue browsing
  v
[PRODUCT PAGE] ─── ~20% reach product
  | Good structure: price, specs, multiple buy options
  | BUT: No reviews, no delivery estimate, no social proof
  | Estimated 5-8% add to cart
  v
[CART / QUICK ORDER] ─── ~3-4% reach cart
  | Quick Order (no registration) is good
  | BUT: Shipping cost unknown until phone call
  | Estimated 40-50% abandon cart
  v
[CHECKOUT + PHONE CONFIRMATION] ─── ~1.5-2% attempt checkout
  | Requires phone confirmation for delivery pricing
  | Manual process adds 24hr+ delay
  v
[ORDER CONFIRMED] ─── ~1-1.5% complete purchase
  | No post-purchase upsell
  | No review request
  | No loyalty program

Overall estimated: 1-1.5% visitor-to-purchase conversion
Industry benchmark: 2-4% for e-commerce
GAP: 50-75% below benchmark
```

---

## Page-by-Page Analysis

### Step 1: Homepage

**URL:** https://www.bagira.bg/
**Purpose:** Welcome visitors, guide them to relevant products
**Primary Action Expected:** Click a category or search for a product

| Dimension | Score | Notes |
|-----------|-------|-------|
| Clarity | 3/10 | No headline, no value proposition text. Just a category sidebar + product carousel |
| Continuity | N/A | Entry point |
| Motivation | 2/10 | No reason given to shop here vs. competitors. No USPs displayed |
| Friction | 5/10 | Navigation works, search exists, but no guided entry points |
| Trust | 3/10 | No reviews, no guarantees, no "why shop here" messaging |

**Page Score: 3.3/10**

**Critical Issues:**
1. **Empty H1** — The H1 tag contains only the logo, zero text content
2. **No value proposition** — Nothing tells visitors why they should shop at Bagira
3. **No promotional banners** — The hero carousel area was blank/loading during analysis
4. **No "bestsellers" or "most popular" section** — Only "Нови продукти" (New Products)
5. **No trust bar** — Missing: free delivery threshold, return policy, financing badges
6. **No urgency elements** — No sales, no limited offers, no seasonal promotions visible

**Recommendations:**
- Add a trust bar below the header: "Доставка за Стара Загора: 10лв | Финансиране от DSK | 14 дни за връщане"
- Add a text-based H1: "Технически хипермаркет БАГИРА — Инструменти, машини и всичко за дома"
- Create a hero section with seasonal promotion and clear CTA
- Add "Най-продавани" (Best Sellers) and "Промоции" (Sales) sections
- Add social proof: "Над 32,000 доволни клиенти ни следят във Facebook"

---

### Step 2: Category Page

**URL Example:** /машини
**Purpose:** Help visitors browse and find the right product
**Primary Action Expected:** Click on a subcategory or specific product

| Dimension | Score | Notes |
|-----------|-------|-------|
| Clarity | 5/10 | H1 present ("Машини"), products displayed, but no guidance |
| Continuity | 5/10 | Logical flow from homepage category click |
| Motivation | 2/10 | Zero educational content, no buying guide, no recommendations |
| Friction | 6/10 | Filters and subcategories exist via brand list |
| Trust | 2/10 | No reviews visible, no "expert picks", no social proof |

**Page Score: 4.0/10**

**Critical Issues:**
1. **No category description** — Zero content explaining what products are available
2. **No buying guidance** — A customer choosing between 1,304 products has no help
3. **No filters visible** — Only brand filter ("Марки"), no price/feature filters visible
4. **No featured/recommended products** — All products equal, no curation

**Recommendations:**
- Add 300-500 word category description with embedded buying tips
- Add prominent filters (price range, power type, brand, rating)
- Create "Препоръчано от БАГИРА" (Recommended by Bagira) section
- Add comparison checkbox on product cards
- Show product ratings on category cards

---

### Step 3: Product Page

**URL Example:** /39687/мотофреза-7-кс-208cc-moller
**Purpose:** Convince visitor to purchase this specific product
**Primary Action Expected:** Add to cart or quick order

| Dimension | Score | Notes |
|-----------|-------|-------|
| Clarity | 7/10 | Product name, price, specs, availability all visible |
| Continuity | 7/10 | Good breadcrumb navigation, logical from category |
| Motivation | 5/10 | Price, discount badge (-34%), specs present. Missing: reviews, comparison, "why this product" |
| Friction | 7/10 | Multiple buy paths: Buy, Quick Order, Installments, Reserve, Phone, Inquiry |
| Trust | 4/10 | "В наличност" (In stock) badge, but no reviews, no guarantee, no return policy |

**Page Score: 6.0/10**

**Strengths (keep these):**
- Clear pricing with both EUR and BGN
- Prominent ПРОМО -34% badge
- "БЪРЗА ПОРЪЧКА без регистрация!" (Quick Order without registration) — excellent friction reducer
- "КУПИ НА ИЗПЛАЩАНЕ" (Buy on installments) with monthly payment shown
- "РЕЗЕРВИРАЙ и вземи от" (Reserve and pick up from)
- Phone number for direct ordering
- Product specs listed clearly
- Breadcrumb navigation
- Product Schema markup (BreadcrumbList + Product)

**Critical Issues:**
1. **Star rating with no reviews** — Shows 5 stars but no customer reviews. This looks fake and damages trust
2. **No delivery estimate on product page** — Customer must leave the page to find delivery info
3. **No return policy visible** — Nowhere on the product page
4. **Only 2 product images** — Insufficient for a 339€ product
5. **No "related products" or cross-sells** — Missing revenue from accessories/complementary items
6. **No "recently viewed" section** — No way to go back to previously browsed products
7. **Product description is plain text** — Long paragraph with no formatting, images, or video

**Recommendations:**
- Remove star rating OR implement real customer review system
- Add delivery estimate badge: "Доставка за 1-3 работни дни"
- Add return policy badge: "14 дни за връщане"
- Add 5-8 product photos including lifestyle/use shots
- Add related products section: "Често купувани заедно" (Frequently bought together)
- Format product description with headers, bullet points, and use-case images
- Add "Защо да изберете този продукт" (Why choose this product) summary

---

### Step 4: Cart / Quick Order

**Not fully testable without placing an order, but observations from UI:**

| Dimension | Score | Notes |
|-----------|-------|-------|
| Clarity | 5/10 | Quick Order option clear, but standard cart flow unclear |
| Continuity | 5/10 | Add to cart button works, but no mini-cart preview |
| Motivation | 3/10 | No urgency, no scarcity, no cross-sell in cart |
| Friction | 4/10 | Delivery cost unknown — must wait for phone call |
| Trust | 3/10 | No security badges near checkout, no guarantee reminder |

**Page Score: 4.0/10**

**Critical Issues:**
1. **SHIPPING COST UNKNOWN** — The delivery page states: "Цената за доставка ще Ви бъде съобщена от наш служител при последвало обаждане" (Delivery price will be communicated by our staff member in a follow-up call). This is a **conversion killer**. Customers must wait for a phone call to know the total cost.
2. **Stara Zagora delivery is 10 лв (5.11€)** — This is known, but not shown on product pages
3. **National delivery** — 1-5 business days, but price is variable and communicated by phone only
4. **No free shipping threshold** — No incentive to increase order value
5. **No mini-cart preview** — Clicking "Buy" doesn't show confirmation without page reload

**Recommendations:**
- **CRITICAL:** Implement transparent shipping costs (flat rate or calculated by weight/location)
- Add free shipping threshold (e.g., "Безплатна доставка над 100€")
- Show shipping estimate on every product page
- Add mini-cart preview (slide-out cart on "Add to Cart")
- Add cross-sell in cart: "Допълнете поръчката с..." (Complete your order with...)
- Add urgency: "Поръчай до 16:30 за доставка утре" (Order by 4:30 PM for next-day delivery)

---

### Step 5: Checkout & Order Confirmation

**Flow appears to be:**
1. Customer places order online
2. Bagira staff calls to confirm order and communicate delivery price
3. Customer confirms or cancels
4. Order is processed

**This is a semi-manual process that introduces massive friction:**

| Dimension | Score | Notes |
|-----------|-------|-------|
| Clarity | 2/10 | Customer doesn't know what happens after clicking "Buy" |
| Continuity | 2/10 | The shift from online to phone breaks the digital experience |
| Motivation | 2/10 | No post-order reassurance, no order tracking |
| Friction | 1/10 | Phone call requirement is maximum friction for online shoppers |
| Trust | 3/10 | Phone confirmation adds human touch but signals "we don't trust automated orders" |

**Page Score: 2.0/10**

---

## Funnel Metrics (Estimated)

| Metric | Estimated Current | Industry Benchmark | Gap |
|--------|-------------------|-------------------|-----|
| Bounce Rate (Homepage) | 55-65% | 35-45% | -20% |
| Homepage → Category | 35-40% | 50-60% | -15% |
| Category → Product | 40-50% | 50-65% | -10% |
| Product → Add to Cart | 3-5% | 8-12% | -5% |
| Cart → Checkout | 40-50% | 60-70% | -20% |
| Checkout → Purchase | 60-70% | 80-90% | -15% |
| **Overall Conversion** | **1-1.5%** | **2-4%** | **-1.5 to 2.5%** |

---

## Revenue Impact Analysis

**Scenario modeling (estimated):**

Assumptions:
- Monthly unique visitors: 15,000 (estimated from social media activity and ad spend)
- Current conversion rate: 1.2%
- Average order value: 80€
- Current monthly online revenue: 15,000 × 1.2% × 80€ = 14,400€/month

| Improvement | New Conv. Rate | Monthly Revenue | Lift |
|------------|---------------|-----------------|------|
| Fix shipping transparency | 1.8% (+50%) | 21,600€ | +7,200€/month |
| + Add customer reviews | 2.1% | 25,200€ | +10,800€/month |
| + Homepage optimization | 2.4% | 28,800€ | +14,400€/month |
| + Full funnel optimization | 3.0% | 36,000€ | +21,600€/month |

**Annual revenue opportunity: 86,400€ - 259,200€/year** depending on scope of improvements.

---

## Optimization Recommendations

### Priority 1 — Do Now (This Week)

**1. Make Shipping Costs Transparent** — Est. 50% conversion lift
- Display flat-rate or weight-based shipping on every product page
- Add shipping calculator at cart level
- Consider free shipping over 100€ to increase AOV
- Show Stara Zagora local delivery: "10лв доставка за Стара Загора" prominently

**2. Add Trust Bar to Header/Homepage** — Est. 10-15% bounce reduction
- Create a banner: "Доставка за Ст. Загора: 10лв | Финансиране от DSK | 14 дни връщане | 0886 886 332"
- Display on every page below the header

**3. Show Delivery Estimate on Product Pages** — Est. 5-10% add-to-cart lift
- Add "Доставка за 1-3 работни дни" badge near the Buy button
- Show "Поръчай до 16:30 за доставка утре" for Stara Zagora

### Priority 2 — Plan (This Month)

**4. Implement Customer Reviews** — Est. 15-20% conversion lift
- Integrate review system (Judge.me or custom)
- Remove fake 5-star ratings (or populate with real reviews)
- Auto-request reviews 7 days after delivery via email/SMS
- Display review count on category page product cards

**5. Add Related Products / Cross-Sells** — Est. 10-15% AOV increase
- "Често купувани заедно" (Frequently bought together) on product pages
- "Допълнете поръчката" (Complete your order) in cart
- "Подобни продукти" (Similar products) for comparison

**6. Homepage Redesign** — Est. 20-30% bounce reduction
- Add hero section with seasonal promotion
- Add value proposition text
- Add bestsellers, promotions, and seasonal collections
- Add social proof counter

### Priority 3 — Strategic (This Quarter)

**7. Automate Checkout Flow** — Est. 20-30% checkout completion lift
- Remove phone call requirement
- Implement automated shipping cost calculation
- Add online payment processing (currently appears phone-confirmed)
- Add order tracking capability

**8. Email Automation** — Est. 10-15% repeat purchase lift
- Cart abandonment email sequence (1hr, 24hr, 72hr)
- Post-purchase follow-up with review request
- Welcome sequence for new customers
- Seasonal promotional emails

**9. Add Free Shipping Threshold** — Est. 15-25% AOV increase
- "Безплатна доставка за поръчки над 100€"
- Show progress bar: "Добавете още 23€ за безплатна доставка"

**10. Mobile Optimization** — Unknown but likely significant
- Ensure responsive product images
- Thumb-friendly Buy buttons
- Simplified mobile checkout
- Click-to-call phone number button

---

## Delivery Policy Issues (Critical)

The current delivery policy creates multiple friction points:

| Issue | Impact | Fix |
|-------|--------|-----|
| Shipping cost communicated by phone only (national) | Very High — Customers abandon because they can't see total cost | Implement transparent shipping calculator |
| Local delivery fixed at 10лв but not shown on product pages | High — Hidden cost surprise at checkout | Show "Доставка: 10лв за Ст. Загора" on product pages |
| "Customer must pay all transport costs if they refuse delivery" | High — Punitive language discourages purchases | Reframe: "14-дневно право на връщане" with clear, fair policy |
| No free shipping tier | Medium — No incentive for larger orders | Add free shipping above 100€ |
| Fixed delivery time appointments cost extra | Low — Understandable but should be transparent | Show cost for fixed delivery slot upfront |

---

## Email Nurture Integration (Currently Missing)

Bagira has NO email marketing infrastructure detected. Recommended funnel-to-email mapping:

| Funnel Stage | Email Sequence | Timing |
|-------------|---------------|--------|
| New visitor (email capture) | Welcome + 10% first order discount | Immediate |
| Cart abandonment | "Забравихте нещо в количката?" | 1hr, 24hr, 72hr |
| Post-purchase | Order confirmation + delivery tracking | Immediate |
| Post-delivery | Review request + related products | 7 days after delivery |
| Inactive customer | Win-back with seasonal offer | 30/60/90 days |
| Seasonal | Spring garden, winter heating, holiday gifts | Seasonal |

**Note:** TheMarketer pixel is installed — this platform supports email automation. It may already be partially configured but not visible from the frontend.

---

## Traffic Source Alignment

| Traffic Source | Best Entry Point | Current State | Recommendation |
|---------------|-----------------|---------------|----------------|
| Google Ads (product) | Product page | Unknown targeting | Send to product pages with delivery info visible |
| Google Ads (brand) | Homepage | Likely homepage | Create optimized brand landing page |
| Facebook (promo) | Promotional landing page | Goes to homepage | Create dedicated promo landing pages |
| Organic (product) | Product page | Category pages rank poorly | Fix SEO on category pages (see SEO-AUDIT.md) |
| Organic (local) | Local landing page | No local pages exist | Create "Технически магазин Стара Загора" page |
| Direct | Homepage | Homepage is weak | Improve homepage (see Priority 2 above) |

---

## Next Steps

1. **THIS WEEK:** Implement transparent shipping costs on product pages — single highest-impact change
2. **THIS WEEK:** Add trust bar across all pages (delivery, financing, returns, phone)
3. **THIS MONTH:** Implement customer review system and remove fake 5-star ratings
4. **THIS MONTH:** Add related products and cross-sell functionality
5. **THIS QUARTER:** Automate the checkout process to eliminate phone confirmation requirement
6. **THIS QUARTER:** Build email marketing automation (cart abandonment, post-purchase, seasonal)
