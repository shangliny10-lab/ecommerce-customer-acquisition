# Paid Advertising Strategy

## Ad Platform Overview

### Amazon PPC (Marketplace Ads)

#### Ad Types
| Ad Type | Placement | Best For | Cost Model |
|---------|-----------|----------|-----------|
| **Sponsored Products** | Search results, product pages | Product visibility, keyword targeting | CPC |
| **Sponsored Brands** | Top of search (headline) | Brand awareness, multiple products | CPC |
| **Sponsored Display** | Product pages, off-Amazon | Retargeting, competitor targeting | CPC/vCPM |
| **Sponsored Brands Video** | Search results | Video demos, storytelling | CPC |

#### Campaign Structure
```
Campaign: [Product Category] - [Match Type]
├── Ad Group: Brand Keywords (exact)
├── Ad Group: Exact Product Keywords (exact)
├── Ad Group: Broad Category Keywords (broad → harvest)
├── Ad Group: Auto Targeting (discovery)
└── Ad Group: Competitor ASIN Targeting (product targeting)
```

#### Bidding Strategy
- **Dynamic bids - down only**: Amazon lowers bids when less likely to convert (safe start)
- **Dynamic bids - up and down**: Adjusts both ways (aggressive, for proven campaigns)
- **Fixed bids**: Full control (for precise testing)
- **Placement adjustments**: Top of search (0-900% increase), Product pages (0-900%)

#### Key Metrics & Targets
| Metric | Benchmark | Action |
|--------|-----------|--------|
| ACOS | <25% (profitable), 25-40% (acceptable), >40% (optimize) | Adjust bids, keywords |
| TACOS | <10% (healthy), 10-20% (growing), >20% (review) | Overall ad efficiency |
| CTR | >0.4% (good), >0.8% (great) | Improve main image/title |
| CVR | >10% (good), >15% (great) | Improve listing, price, reviews |
| Impression share | Track over time | Increase bids/budget if low |

#### Optimization Cycle
1. **Week 1**: Launch auto + broad campaigns, collect data
2. **Week 2**: Harvest converting search terms → exact campaigns
3. **Week 3**: Add negative keywords (high spend, no conversion)
4. **Week 4**: Optimize bids based on ACOS by keyword
5. **Ongoing**: Weekly bid adjustments, monthly campaign restructure

---

### Google Ads

#### Campaign Types
| Campaign Type | Best For |
|--------------|----------|
| **Search** | High-intent buyers, keyword targeting |
| **Shopping** | Product listing ads (requires Merchant Center) |
| **Performance Max** | Automated across all Google inventory |
| **Display** | Retargeting, brand awareness |
| **YouTube** | Video ads, awareness, retargeting |

#### Search Campaign Structure
```
Campaign: [Brand] - Search
├── Ad Group: Brand (exact/phrase)
├── Ad Group: Product (exact)
├── Ad Group: Category (phrase)
├── Ad Group: Competitor (phrase/exact)
└── Ad Group: Long-tail (broad modified)
```

#### Shopping Campaign Best Practices
- Optimize product feed title (keyword-rich, under 150 chars)
- High-quality images (white background, multiple angles, lifestyle)
- Accurate pricing and availability
- Use product ratings and reviews
- Segment by product type, brand, margin, best sellers
- Negative keywords are critical (exclude irrelevant searches)

#### Smart Bidding Strategies
- **Maximize Clicks**: Budget-focused, traffic volume
- **Maximize Conversions**: Conversion volume at target budget
- **Target CPA**: Cost per acquisition target (needs 30+ conversions/mo)
- **Target ROAS**: Return on ad spend target (needs conversion value data)
- **Enhanced CPC**: Manual bids with AI adjustment (transition strategy)

---

### Meta Ads (Facebook + Instagram)

#### Campaign Structure (CBO)
```
Campaign: [Objective] - [Product/Offer] - [Month]
├── Ad Set: Broad (18-65, interests open)
├── Ad Set: Interest-based (niche interests, behaviors)
├── Ad Set: Lookalike (1% - based on purchasers)
├── Ad Set: Retargeting (website visitors 30d)
└── Ad Set: Retargeting (cart abandoners 14d)
```

#### Campaign Objectives by Funnel
| Objective | Funnel Stage | Best For |
|-----------|-------------|----------|
| **Awareness / Reach** | Top | Brand awareness, new market entry |
| **Traffic** | Top-Mid | Blog content, landing pages |
| **Engagement** | Mid | Video views, page engagement, event responses |
| **Lead Generation** | Mid | Email capture, lead magnets |
| **App Promotion** | Mid | App installs |
| **Conversions** | Bottom | Purchases, add to cart, initiate checkout |
| **Catalog Sales (DPA)** | Bottom | Retargeting with dynamic products |
| **Store Traffic** | Bottom | Physical stores |

#### Ad Creative Formats
| Format | Best For | Specs |
|--------|----------|-------|
| **Single image** | Simple offers, product shots | 1080×1080 (1:1), 1080×1920 (9:16) |
| **Carousel** | Multiple products, features, before/after | 1080×1080, 2-10 cards |
| **Video** | Demos, storytelling, UGC | 1080×1920, 15-30s, captions |
| **Reels** | Trendy, native-feeling, high reach | 1080×1920, 15-60s |
| **Collection** | Mobile shopping experience | Cover + product catalog |
| **Stories** | Full-screen, immersive, urgent | 1080×1920, 5-15s |

#### Creative Testing Framework
- **Test 3-5 creatives per ad set** (not 1-2)
- **Variables to test**: Hook (first 3s), offer, visual style, CTA, length
- **Budget**: $10-20/day per ad set for testing (7 days minimum)
- **Winner criteria**: 2x CPA of average, or statistically significant lift
- **Scale**: Duplicate winning ad sets, increase budget 20% every 3 days
- **Refresh**: New creatives every 2-4 weeks (ad fatigue)

#### Retargeting Strategy
| Audience | Window | Offer | Creative |
|----------|--------|-------|----------|
| Site visitors (no add to cart) | 30 days | Educational content, bestseller | Video demo, social proof |
| Product viewers | 14 days | Free shipping, small discount | Dynamic product ad |
| Add to cart (no purchase) | 14 days | 10% off, urgency, review | DPA + discount overlay |
| Initiate checkout | 7 days | 15% off, free shipping, support | Urgency + guarantee |
| Past purchasers | 90-180 days | Cross-sell, loyalty, referral | New products, exclusive |

---

### TikTok Ads

#### Ad Formats
| Format | Best For | Specs |
|--------|----------|-------|
| **In-Feed Ads** | Native-feeling, reach, conversions | 9:16, 15-60s, sound on |
| **Spark Ads** | Boost organic posts (proven creative) | Use existing TikTok post |
| **TopView** | Premium, first video when opening app | 9:16, up to 60s |
| **Branded Hashtag Challenge** | UGC, brand awareness, viral | 6-day campaign |
| **Branded Effects** | Interactive, engagement | AR filters/effects |

#### Campaign Structure
```
Campaign: [Objective] - [Product]
├── Ad Group: Broad (18-55, no interest targeting)
├── Ad Group: Interest (niche interests + behaviors)
├── Ad Group: Lookalike (1% - purchasers)
├── Ad Group: Retargeting (video viewers 50%+)
└── Ad Group: Retargeting (website visitors)
```

#### Creative Principles (TikTok Native)
- **Hook in first 1-2 seconds**: Text overlay + visual pattern interrupt
- **UGC style**: Phone-filmed, real people, not overly polished
- **Sound on**: Use trending audio or clear voiceover (80% watch with sound)
- **Captions**: Burned-in subtitles (many watch without sound)
- **Length**: 15-30 seconds (highest completion)
- **CTA**: End with clear action ("link in bio", "shop now", "comment YES")
- **No hard sell**: Entertain/educate first, sell second

#### TikTok Pixel & Events
- Install TikTok Pixel on website (or use Shopify app)
- Track: ViewContent, AddToCart, InitiateCheckout, Purchase
- Use **Complete Payment** optimization when 50+ conversions/week
- Use **Initiate Checkout** optimization when below 50 purchases/week
- Enable **Enhanced Match** for better attribution

---

## Budget Allocation Model

### By Funnel Stage (New Brand)
| Stage | % of Budget | Channels |
|-------|------------|----------|
| Awareness | 30-40% | Paid social (broad), TikTok, influencer, content |
| Consideration | 25-35% | Retargeting, SEO content, email, comparison |
| Conversion | 25-35% | PPC/search, marketplace ads, retargeting, email |
| Retention | 5-10% | Email, loyalty, referral, organic social |

### By Channel (Established Brand)
| Channel | % of Budget | Rationale |
|---------|------------|-----------|
| Marketplace PPC (Amazon/etc.) | 30-40% | Highest intent, direct ROI |
| Paid social (Meta/TikTok) | 25-35% | Reach, new customer acquisition |
| Google Search/Shopping | 15-25% | High-intent, comparison shoppers |
| Retargeting (all platforms) | 10-15% | High ROAS, recovery |
| Influencer/Content | 5-10% | Trust, UGC, organic amplification |

## Ad KPI Benchmarks

| Metric | Facebook/Instagram | TikTok | Google Search | Google Shopping | Amazon PPC |
|--------|-------------------|--------|--------------|----------------|------------|
| CTR | 1-2% | 1-3% | 3-5% | 0.5-1% | 0.4-0.8% |
| CVR | 1-3% | 1-2% | 3-5% | 1-3% | 10-15% |
| ROAS | 2-4x | 1.5-3x | 3-5x | 3-6x | 3-5x (ACOS 20-33%) |
| CPA | $15-40 | $10-30 | $20-50 | $15-35 | $5-15 |
| Frequency | 1.5-2.5/wk | 2-4/wk | N/A | N/A | N/A |

*Note: These are general benchmarks. Actual performance varies by category, price point, market, and creative quality.*

## Ad Optimization Checklist

### Daily
- [ ] Check spend pacing (on track for daily budget?)
- [ ] Pause ads with CPA > 2x target (after 3x target spend)
- [ ] Check for disapproved ads or account issues

### Weekly
- [ ] Review top-performing creatives (identify patterns)
- [ ] Add negative keywords/search terms
- [ ] Adjust bids on high/low ACOS keywords
- [ ] Launch 2-3 new creatives for testing
- [ ] Review audience performance (shift budget to winners)

### Monthly
- [ ] Restructure campaigns (consolidate winners, kill losers)
- [ ] Refresh creative library (retire fatigued ads)
- [ ] Review funnel metrics (CTR → CVR → AOV → ROAS)
- [ ] Test new audiences or placements
- [ ] Reallocate budget based on 30-day ROAS by channel
