# Funnel Diagnosis & Optimization

## Ecommerce Acquisition Funnel

### Standard Funnel Stages

```
[Awareness] → [Interest] → [Consideration] → [Intent] → [Purchase] → [Retention] → [Advocacy]
     |            |              |               |           |             |             |
   Reach       Engagement     Evaluation      Add-to-cart   Order    Repeat buy    Referral
```

### Key Metrics by Stage

| Stage | Metric | Formula | Benchmark (Good) |
|-------|--------|---------|-----------------|
| **Awareness** | Impressions / Reach | Ad views, social reach | Growing MoM |
| | CTR (Click-Through Rate) | Clicks / Impressions | 1-3% (social), 3-5% (search) |
| **Interest** | Sessions / Visitors | Unique site visits | Growing MoM |
| | Bounce Rate | Single-page sessions / Total sessions | <40% (good), <30% (great) |
| | Time on Site | Avg. session duration | >2 min |
| | Pages per Session | Pageviews / Sessions | >2.5 |
| **Consideration** | Product Page Views | Product page sessions | — |
| | Add-to-Cart Rate | Add to cart / Product page views | 5-10% |
| | Email Signup Rate | Signups / Visitors | 2-5% |
| **Intent** | Initiate Checkout Rate | Checkout starts / Add to cart | 40-60% |
| | Cart Abandonment Rate | 1 - (Purchases / Add to cart) | 60-80% (industry avg) |
| **Purchase** | Conversion Rate | Purchases / Sessions | 1-3% (DTC), 10-15% (Amazon) |
| | AOV (Avg Order Value) | Revenue / Orders | Category-dependent |
| | Checkout Completion | Purchases / Checkout starts | 50-70% |
| **Retention** | Repeat Purchase Rate | Repeat customers / Total customers | 20-30% (good), 40%+ (great) |
| | LTV (Lifetime Value) | Avg revenue per customer over lifetime | 3x CAC (healthy) |
| | Churn Rate | Customers lost / Total customers | <5%/month |
| **Advocacy** | NPS (Net Promoter Score) | % Promoters - % Detractors | >50 (excellent) |
| | Referral Rate | Referred customers / Total customers | 5-15% |
| | Review Rate | Reviews / Orders | 5-10% |

## Diagnosis Process

### Step 1: Map the Current Funnel

Build a funnel table with actual numbers:

| Stage | Count | Rate vs. Previous | Benchmark | Gap? |
|-------|-------|-------------------|-----------|------|
| Impressions | | — | — | |
| Clicks | | CTR: % | 1-3% | |
| Sessions | | — | — | |
| Product Views | | % of sessions | 40-60% | |
| Add to Cart | | ATC rate: % | 5-10% | |
| Initiate Checkout | | % of ATC | 40-60% | |
| Purchases | | CVR: % | 1-3% | |
| Revenue | | AOV: $ | — | |

### Step 2: Identify the Biggest Leak

Calculate the drop-off rate at each stage:
```
Drop-off at stage X = (Users at previous stage - Users at stage X) / Users at previous stage
```

The stage with the highest drop-off (relative to benchmark) is your biggest leak.

### Step 3: Diagnose Root Causes

For each underperforming stage, check these common causes:

#### Low CTR (Ad → Click)
- [ ] Ad creative is weak (no clear hook, poor visual)
- [ ] Ad targeting is wrong (wrong audience)
- [ ] Ad copy doesn't match user intent
- [ ] Offer is unattractive (no discount, no urgency)
- [ ] Ad placement is poor (below fold, wrong context)
- [ ] Ad frequency too high (ad fatigue)
- [ ] Competitors have stronger offers/creative

#### High Bounce Rate (Click → Leave Immediately)
- [ ] Landing page doesn't match ad promise (message mismatch)
- [ ] Page loads too slow (>3 seconds)
- [ ] Mobile experience is poor (not optimized)
- [ ] No clear value proposition above the fold
- [ ] Pop-ups or interstitials annoy users
- [ ] Wrong traffic source (audience not interested in product)
- [ ] No social proof or trust signals

#### Low Add-to-Cart Rate
- [ ] Product images are poor (few angles, no lifestyle, no zoom)
- [ ] No product video or demo
- [ ] Product description is weak (features not benefits)
- [ ] Price is too high relative to perceived value
- [ ] Few or no reviews (social proof missing)
- [ ] Size chart / specs unclear (uncertainty)
- [ ] Shipping cost or time not shown upfront (surprise later)
- [ ] No urgency or scarcity (no reason to buy now)
- [ ] Add-to-cart button is hard to find or not prominent

#### High Cart Abandonment
- [ ] Unexpected shipping costs at checkout
- [ ] Checkout requires account creation (no guest checkout)
- [ ] Too many form fields (long checkout process)
- [ ] Limited payment options (no PayPal, Apple Pay, etc.)
- [ ] Concerns about payment security (no trust badges)
- [ ] Slow checkout process (page load, errors)
- [ ] No coupon field (user leaves to search for code)
- [ ] Return policy unclear (fear of being stuck)

#### Low Conversion Rate (Overall)
- [ ] Any combination of the above
- [ ] Traffic quality is low (wrong audience, bot traffic)
- [ ] Brand trust is low (new brand, no social proof)
- [ ] Product-market fit issue (product doesn't solve real problem)
- [ ] Price point is wrong for target audience
- [ ] Competitors offer better value
- [ ] Seasonal or timing issue (wrong time to buy)

### Step 4: Prioritize Fixes by Impact × Effort

| Fix | Impact | Effort | Priority |
|-----|--------|--------|----------|
| | High/Med/Low | High/Med/Low | P1/P2/P3 |

**P1 (High impact, Low effort)**: Do first
**P2 (High impact, High effort)**: Plan and execute
**P3 (Low impact, Low effort)**: Do when convenient
**Skip (Low impact, High effort)**: Don't do

## Optimization Playbooks by Stage

### Top-of-Funnel: Traffic & CTR Optimization

#### Improve Ad CTR
1. **Test hooks**: First 3 seconds of video / first line of copy
2. **Use social proof**: "As seen on", "10,000+ happy customers", star ratings in ad
3. **Create urgency**: "Limited time", "Only X left", "Sale ends tonight"
4. **Show the product in use**: Demo > static product shot
5. **Test offers**: Free shipping vs. 10% off vs. BOGO
6. **Use UGC-style creative**: Real people > polished studio (on social)
7. **A/B test**: 3-5 creatives per ad set, let data decide

#### Improve Organic Reach
1. **Post consistently**: Algorithm favors regular posters
2. **Use trending formats/audio**: Ride trends (with brand-relevant twist)
3. **Engage within first hour**: Comments boost algorithm distribution
4. **Post when audience is active**: Check platform analytics
5. **Use hashtags strategically**: Mix of niche and trending
6. **Collaborate**: Cross-promotion with complementary brands/creators

### Mid-Funnel: Engagement & Consideration

#### Reduce Bounce Rate
1. **Message match**: Landing page headline mirrors ad copy
2. **Fast load time**: Compress images, use CDN, minimize scripts (<3s load)
3. **Mobile-first**: Design for mobile (most traffic is mobile)
4. **Clear value prop**: Above-the-fold answer "What is it and why should I care?"
5. **Social proof above fold**: Reviews, ratings, customer count
6. **No intrusive pop-ups**: Delay pop-ups until 15-30s or scroll depth
7. **Clear navigation**: Easy to find products, categories, search

#### Increase Add-to-Cart
1. **High-quality images**: 5-7 images, white background + lifestyle + detail + scale
2. **Product video**: 30-60s demo showing product in use
3. **Benefit-driven description**: "What's in it for me?" not just specs
4. **Reviews**: At least 10-20 reviews with 4+ star average (actively collect)
5. **Clear sizing/specs**: Size charts, dimensions, compatibility info
6. **Transparent shipping**: "Free shipping over $X", "Ships in 1-2 days" shown on product page
7. **Trust badges**: Secure checkout, money-back guarantee, easy returns
8. **Urgency elements**: "Only 3 left", "Sale ends in 2 days", "Today only"
9. **Sticky add-to-cart**: Button stays visible while scrolling (mobile)
10. **Cross-sell**: "Frequently bought together", "You may also like"

### Bottom-of-Funnel: Checkout & Purchase

#### Reduce Cart Abandonment
1. **Guest checkout**: No account required (offer account creation after purchase)
2. **Minimal fields**: Only essential info (name, email, shipping address, payment)
3. **Multiple payment options**: Credit card, PayPal, Apple Pay, Google Pay, Klarna/Afterpay
4. **Transparent pricing**: Show shipping cost before checkout (shipping calculator on cart page)
5. **Trust signals**: SSL badge, "Secure checkout", payment provider logos
6. **Progress indicator**: "Step 1 of 3" — reduce perceived complexity
7. **Auto-fill**: Address autocomplete, saved payment info
8. **No surprises**: No unexpected fees at final step
9. **Clear return policy**: "30-day free returns" visible during checkout
10. **Abandoned cart emails**: Automated sequence (1h, 24h, 72h) with incentive

#### Improve Conversion Rate
1. **All of the above** (each stage improvement compounds)
2. **Retargeting**: Ads to cart abandoners and product viewers
3. **Email capture**: Exit-intent pop-ups with discount
4. **Live chat**: Real-time support to answer purchase questions
5. **FAQ on product page**: Answer common objections
6. **Guarantee**: Risk reversal (money-back, free returns)
7. **Multiple buying options**: One-time, subscribe & save, bundle
8. **Social proof at checkout**: "Join 10,000+ happy customers"

### Post-Purchase: Retention & LTV

#### Increase Repeat Purchase Rate
1. **Post-purchase email sequence**: Usage tips, complementary products, review request
2. **Loyalty program**: Points for purchases, referrals, social shares
3. **Subscribe & save**: Recurring orders for consumable products
4. **Personalized recommendations**: Based on purchase history
5. **Exclusive offers**: Early access, member-only discounts
6. **Win-back campaigns**: Re-engage lapsed customers with special offers
7. **Excellent customer service**: Fast responses, easy returns, proactive outreach

#### Increase LTV
1. **Upsell at checkout**: "Add [complementary product] for $X"
2. **Cross-sell post-purchase**: "Customers who bought X also bought Y"
3. **Bundles**: Product bundles at slight discount (increase AOV)
4. **Tiered pricing**: Premium version with more features
5. **Referral program**: Reward customers for referring friends
6. **Community building**: Facebook group, user forum, brand community

## Funnel Audit Checklist

### Tracking & Data
- [ ] Google Analytics 4 installed and configured
- [ ] Enhanced ecommerce tracking enabled
- [ ] Facebook Pixel / CAPI installed
- [ ] TikTok Pixel installed
- [ ] UTM parameters on all campaigns
- [ ] Goal funnels set up in GA
- [ ] Attribution model selected (data-driven recommended)
- [ ] Cross-device tracking enabled

### Top of Funnel
- [ ] Ad creative library has 10+ active creatives
- [ ] A/B testing running continuously
- [ ] Organic posting schedule consistent (3-5/week minimum)
- [ ] SEO content published regularly (2-4/month)
- [ ] Influencer partnerships active (3-5/month)

### Mid Funnel
- [ ] Landing pages load in <3 seconds
- [ ] Mobile experience optimized
- [ ] Product pages have 5+ images + video
- [ ] Reviews collected actively (10+ per product minimum)
- [ ] Email capture mechanism active (pop-up, lead magnet)
- [ ] Retargeting audiences set up (30d, 60d, 90d)

### Bottom Funnel
- [ ] Guest checkout available
- [ ] Checkout has <5 form fields
- [ ] Multiple payment options (3+)
- [ ] Abandoned cart email sequence active (3+ emails)
- [ ] Shipping costs shown before checkout
- [ ] Return policy clearly visible

### Post-Purchase
- [ ] Post-purchase email sequence active (5+ emails)
- [ ] Review request automated
- [ ] Loyalty/referral program in place
- [ ] Win-back campaign for lapsed customers
- [ ] Customer support response time <24h
