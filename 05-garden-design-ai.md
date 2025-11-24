# Garden Design AI

## Overview
Upload photos of your garden space and receive a complete design plan with shopping list, planting instructions, and ongoing maintenance guidance.

## Problem Statement
Garden design is intimidating for beginners. Hiring a designer is expensive, and DIY requires knowledge of plants, layout, soil conditions, and local climate. People want beautiful gardens but don't know where to start.

## Target Audience
- Homeowners with yard space
- Apartment dwellers with balconies
- Beginner gardeners
- People moving to new homes
- Urban gardening enthusiasts

## Core Features
- Photo upload of garden space
- Dimension and space analysis
- Sunlight/shade assessment
- Design generation based on:
  - Local climate zone
  - Maintenance preference (low/medium/high)
  - Style preference (formal, cottage, modern, edible, etc.)
  - Budget constraints
- Complete shopping list with links
- Step-by-step planting instructions
- Seasonal maintenance calendar
- Plant care reminders

## Value Proposition
Transform your outdoor space from photos to fully planned garden with everything you need to buy and do, without expensive consultants.

## Technical Approach
- Computer vision for space analysis
- LLM for design generation
- Plant database with climate compatibility
- Integration with nursery/retailer catalogs
- Calendar API for maintenance reminders
- Mobile app for ongoing care tracking

## Market Analysis
### Competitors
- iScape, Garden Planner (manual design tools)
- PlantSnap, PictureThis (plant ID only)
- Local garden designers (expensive)
- Garden centers (limited personalization)

### Business Model
- One-time design fee ($20-50)
- Subscription for ongoing maintenance ($5/month)
- Affiliate revenue from plant/supply purchases

## Next Steps
- [ ] Research plant databases and APIs
- [ ] Build photo analysis prototype
- [ ] Test design generation with sample gardens
- [ ] Partner with local nurseries for inventory

## Business Model Canvas

### Customer Segments
- New homeowners with blank yards
- Apartment/balcony dwellers
- DIY gardeners (beginner to intermediate)
- People wanting edible gardens
- Homeowners wanting curb appeal
- Renters with temporary outdoor spaces

### Value Propositions
- Professional garden design without consultant fees
- Complete plan from photos in minutes
- Shopping list with exact products
- Step-by-step planting guidance
- Ongoing maintenance support
- Designs matched to local climate and skill level

### Channels
- Direct web/mobile platform
- Instagram/Pinterest (visual showcase)
- Gardening influencer partnerships
- Home improvement content creators
- Nursery and garden center partnerships
- Real estate and home staging professionals
- Google/Facebook ads targeting homeowners
- SEO for garden design queries

### Customer Relationships
- Self-service design generation
- In-app maintenance reminders and tips
- Community gallery and inspiration
- Seasonal newsletters with gardening tips
- Optional expert review/consultation add-on
- Progress sharing and updates

### Revenue Streams
- One-time design fee ($20-50 per space)
- Monthly maintenance subscription ($5/month)
- Premium designs with expert review ($75-100)
- Affiliate revenue from:
  - Plant and supply purchases
  - Nurseries and retailers
  - Gardening tools
- Sponsored plant collections
- Professional landscaper tier (B2B)

### Key Resources
- Computer vision for space analysis
- Plant database (climate zones, care requirements)
- LLM for design generation
- Nursery/retailer product catalogs
- Garden design templates and rules
- User garden photos and feedback
- Mobile app platform

### Key Activities
- Photo analysis and space assessment
- AI design generation
- Plant database maintenance and updates
- Retailer integration and catalog updates
- Maintenance calendar and reminders
- Community moderation and inspiration
- Partnership development with nurseries

### Key Partnerships
- Local and online nurseries
- Garden supply retailers (Home Depot, Lowe's)
- Plant databases and resources
- Gardening influencers and bloggers
- Landscapers and garden designers
- Weather and climate services
- Real estate staging professionals

### Cost Structure
- Computer vision and AI API costs
- Cloud hosting and storage
- Plant database licensing
- App development and maintenance
- Marketing and customer acquisition
- Customer support
- Content creation (care guides, tips)

## Value Proposition Canvas

### Customer Profile

#### Customer Jobs
- Design attractive outdoor space
- Choose right plants for climate
- Create functional garden layout
- Know what to buy and where
- Learn proper planting techniques
- Maintain healthy garden over time
- Maximize limited space
- Stay within budget

#### Pains
- Garden design feels overwhelming
- Don't know which plants work together
- Hiring designer costs $500-2000+
- Trial and error kills plants and wastes money
- Hard to visualize final result
- Unclear how much to buy
- Plant care instructions scattered
- Plants die from improper care
- Limited space utilization
- Don't know where to start

#### Gains
- Beautiful outdoor space to enjoy
- Curb appeal and property value increase
- Fresh herbs/vegetables from garden
- Confidence in plant choices
- Pride in DIY accomplishment
- Low-maintenance garden that thrives
- Money saved vs. hiring designer
- Relaxing outdoor sanctuary
- Successful plants that grow well

### Value Map

#### Products & Services
- Photo-based space analysis
- AI-generated garden design
- Climate-appropriate plant selection
- Visual layout and spacing plan
- Complete shopping list with links
- Step-by-step planting guide
- Seasonal maintenance calendar
- Plant care reminders and tips
- Design style customization
- Budget optimization

#### Pain Relievers
- Design created in 10 minutes vs. weeks of research
- AI ensures climate compatibility
- 90% cheaper than hiring designer ($30 vs. $1000)
- Success rate for plant selection 95%+
- Visual mockup shows final result
- Exact quantities prevent over/under-buying
- All care instructions in one place
- Reminders prevent plant death
- Smart layout maximizes space
- Clear starting point with guided process

#### Gain Creators
- Transform outdoor space for under $500
- Increase property value by $2000-5000
- Harvest fresh produce and herbs
- 90% customer satisfaction with designs
- Bragging rights for DIY accomplishment
- Plants thrive with proper care guidance
- Save $1000+ vs. professional designer
- Create peaceful outdoor retreat
- 80%+ plant survival rate (vs. 40% trial and error)

## Testing Business Ideas

### Critical Assumptions to Test

#### Desirability Assumptions
1. **Beginner gardeners willing to pay for AI design**
   - Risk: High | Evidence: Low

2. **Photo-based design is sufficient without site visit**
   - Risk: High | Evidence: Low

3. **Users will purchase plants from recommendations**
   - Risk: Medium | Evidence: Medium

4. **Maintenance subscription has value after initial design**
   - Risk: High | Evidence: Low

#### Feasibility Assumptions
5. **Computer vision can accurately assess space from photos**
   - Risk: Medium | Evidence: Medium

6. **AI can generate quality garden designs**
   - Risk: Medium | Evidence: Low

7. **Plant database comprehensive enough for recommendations**
   - Risk: Low | Evidence: High

#### Viability Assumptions
8. **Affiliate revenue covers AI costs**
   - Risk: High | Evidence: Low

9. **Can acquire customers at CAC under $30**
   - Risk: Medium | Evidence: Low

10. **Conversion rate from free to paid 10%+**
    - Risk: Medium | Evidence: Low

### Proposed Experiments

#### Experiment 1: Manual Design Concierge
- **Tests:** Assumptions #1, #2, #3
- **Method:** Offer manual garden design service, collect photos, create designs by hand
- **Success Metric:** 10 customers at $30-50, 80%+ satisfaction, 60%+ purchase plants
- **Time/Cost:** 3 weeks, $0 (time investment)

#### Experiment 2: Photo Assessment Test
- **Tests:** Assumption #5
- **Method:** Test computer vision on 50 garden photos, compare to manual assessment
- **Success Metric:** 80%+ accuracy on space dimensions and sunlight assessment
- **Time/Cost:** 2 weeks, $200 (CV APIs)

#### Experiment 3: Landing Page Pre-orders
- **Tests:** Assumptions #1, #9
- **Method:** Landing page with example designs, collect $20 pre-orders
- **Success Metric:** 5%+ conversion rate, 50+ pre-orders, CAC under $25
- **Time/Cost:** 2 weeks, $500 (ads)

#### Experiment 4: Basic Design MVP
- **Tests:** Assumptions #2, #6
- **Method:** Build simple photo-to-design tool, test with 20 users
- **Success Metric:** 4/5 stars, 70%+ satisfied with design quality, 50%+ implement it
- **Time/Cost:** 4 weeks, $800 (development)

#### Experiment 5: Maintenance Value Test
- **Tests:** Assumption #4
- **Method:** Provide free maintenance reminders to experiment #1 customers for 2 months
- **Success Metric:** 60%+ find valuable, 40%+ would pay $5/month
- **Time/Cost:** 2 months, $0

#### Experiment 6: Affiliate Revenue Test
- **Tests:** Assumption #8
- **Method:** Include nursery affiliate links in designs, track conversion
- **Success Metric:** 20%+ click-through, 5%+ purchase, $10+ revenue per design
- **Time/Cost:** 2 weeks, $0

### Learning Card Template

After each experiment:
- **What we learned:** [Key insights]
- **Data collected:** [Quantitative results]
- **Next decision:** [Pivot, persevere, or perish]
- **Follow-up experiments:** [What to test next]

## Status Log
| Date | Status | Notes |
|------|--------|-------|
| 2025-11-24 | Exploring | Initial idea capture |

---

*Last updated: 2025-11-24*
