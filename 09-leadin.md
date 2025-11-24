# LeadIn

## Overview
News-based lead discovery platform using LLMs to sieve through enterprise news and identify potential sales opportunities and business development leads.

## Problem Statement
Sales teams waste time manually scanning news for triggers (funding rounds, expansions, leadership changes, new initiatives). Relevant signals are buried in noise, and manual research doesn't scale.

## Target Audience
- B2B sales teams
- Business development professionals
- Account executives
- Sales intelligence teams
- Consultants seeking new clients
- Agencies pitching services

## Core Features
- Automated enterprise news monitoring
- LLM-powered relevance filtering based on:
  - Company ICP (ideal customer profile)
  - Trigger events (funding, hiring, expansion, product launches)
  - Pain signals (layoffs, transitions, challenges)
- Lead scoring and prioritization
- Contact enrichment and recommendation
- Personalized outreach message generation
- Integration with CRM systems
- Daily/weekly lead digests
- Custom alert rules per user

## Value Proposition
Never miss a warm lead - AI monitors thousands of news sources and surfaces only the opportunities that match your offering and timing.

## Technical Approach
- News aggregation APIs (NewsAPI, company filings, press releases)
- LLM for relevance scoring and signal extraction
- Entity recognition for company/people identification
- Contact database integration (Apollo, ZoomInfo)
- CRM integrations (Salesforce, HubSpot)
- Email/Slack notifications
- Dashboard for lead management

## Market Analysis
### Competitors
- ZoomInfo, Apollo (database focus, limited news intelligence)
- Google Alerts (too noisy, no intelligence)
- Owler, Crunchbase (news tracking, not lead-focused)
- Clay (manual workflow building)

### Business Model
- Per-seat pricing ($50-100/user/month)
- Team plans with shared monitoring
- Enterprise custom solutions
- API access for integration

## Next Steps
- [ ] Identify target industries for MVP
- [ ] Build news ingestion and filtering pipeline
- [ ] Create lead scoring algorithm
- [ ] Pilot with 5-10 sales professionals

## Business Model Canvas

### Customer Segments
- B2B sales teams (5-50 people)
- Business development professionals
- Account executives at tech/SaaS companies
- Sales intelligence teams
- Consultants and agencies
- Enterprise sales reps

### Value Propositions
- Never miss warm lead opportunities
- AI filters news noise to relevant signals
- Timely outreach at perfect moment
- Personalized lead insights and context
- Automate lead research workflow
- Higher conversion with trigger-based selling
- Competitive intelligence included

### Channels
- Direct sales to sales teams
- LinkedIn (B2B sales community)
- Sales conferences and events
- CRM marketplace integrations
- Sales enablement consultants
- Product Hunt and tech communities
- Content marketing (sales best practices)
- Partnerships with sales tools

### Customer Relationships
- Self-service onboarding with setup assistance
- Customer success team for enterprise
- Slack/email support
- Regular feature updates
- User community and best practices sharing
- ROI tracking and reporting
- Sales playbook templates

### Revenue Streams
- Per-seat pricing ($50-100/user/month)
- Team plans with volume discounts
- Enterprise custom solutions ($5k-20k/year)
- API access for custom integrations
- White-label for sales enablement platforms
- One-time setup/consulting fees

### Key Resources
- News aggregation infrastructure
- LLM for relevance scoring
- Contact database partnerships
- CRM integrations
- Lead scoring algorithms
- Sales intelligence expertise
- Customer success team

### Key Activities
- News monitoring and ingestion
- AI-powered signal extraction
- Lead scoring and prioritization
- CRM integration maintenance
- Contact data enrichment
- Customer success and training
- Sales playbook development

### Key Partnerships
- News APIs and data providers
- Contact databases (Apollo, ZoomInfo)
- CRM platforms (Salesforce, HubSpot)
- Sales enablement platforms
- Industry news publications
- Sales training organizations
- LinkedIn Sales Navigator

### Cost Structure
- News API and data subscriptions (major cost)
- AI/LLM API costs
- Contact database access
- Cloud hosting and infrastructure
- Sales and customer success team
- Marketing and customer acquisition
- CRM integration maintenance
- Product development

## Value Proposition Canvas

### Customer Profile

#### Customer Jobs
- Find new sales opportunities
- Research prospects efficiently
- Time outreach perfectly
- Stay ahead of competitors
- Hit sales quotas
- Build qualified pipeline
- Personalize outreach at scale
- Track industry developments

#### Pains
- Manually scanning news is time-consuming
- Miss opportunities buried in noise
- Outreach timing often wrong
- Research takes hours per lead
- Google Alerts too broad and noisy
- Hard to track multiple accounts
- Competitors reach prospects first
- Cold outreach has low conversion
- Don't know which leads to prioritize

#### Gains
- Always-full pipeline
- Perfect timing on outreach
- Higher response rates
- Win more deals
- Less time on research
- Beat competitors to opportunities
- Confident, personalized pitches
- Hit/exceed quota
- Warm leads vs. cold calling

### Value Map

#### Products & Services
- Automated news monitoring (thousands of sources)
- AI relevance filtering by ICP
- Lead scoring and prioritization
- Trigger event identification
- Contact enrichment
- Personalized outreach suggestions
- CRM integration and sync
- Daily/weekly lead digests
- Custom alert configuration
- Competitive intelligence tracking

#### Pain Relievers
- Automate 10+ hours/week of research
- AI filters 99% of noise, surfaces gems
- Real-time alerts enable perfect timing
- Pre-researched context saves hours
- Single feed vs. multiple sources
- Track unlimited accounts effortlessly
- 24/7 monitoring vs. manual checking
- Trigger-based outreach beats cold
- Data-driven prioritization vs. guesswork

#### Gain Creators
- 3x more qualified leads in pipeline
- 50% higher response rates
- Close 25% more deals
- Save 10-15 hours/week on research
- Reach prospects 2-3 days earlier
- 5x ROI in first quarter
- Personalized outreach at scale
- Consistent quota achievement
- 80% warm vs. 20% cold outreach

## Testing Business Ideas

### Critical Assumptions to Test

#### Desirability Assumptions
1. **Sales teams struggle with manual news monitoring**
   - Risk: Medium | Evidence: Medium (known pain point)

2. **Trigger-based selling improves conversion**
   - Risk: Low | Evidence: High (established sales methodology)

3. **Users willing to pay $50-100/user/month**
   - Risk: High | Evidence: Low

4. **AI can filter news accurately to ICP**
   - Risk: High | Evidence: Low

#### Feasibility Assumptions
5. **Can aggregate comprehensive news coverage**
   - Risk: Medium | Evidence: High (APIs exist)

6. **LLM can score lead quality accurately**
   - Risk: Medium | Evidence: Medium

7. **CRM integrations are feasible**
   - Risk: Low | Evidence: High

#### Viability Assumptions
8. **News data costs sustainable with pricing**
   - Risk: High | Evidence: Low

9. **Can acquire customers at CAC under $500**
   - Risk: High | Evidence: Low

10. **Churn rate under 10% monthly**
    - Risk: Medium | Evidence: Low

### Proposed Experiments

#### Experiment 1: Sales Team Pain Interviews
- **Tests:** Assumptions #1, #3
- **Method:** Interview 30 B2B sales reps about lead research process
- **Success Metric:** 70%+ spend 5+ hours/week on research, 60%+ would pay for solution
- **Time/Cost:** 2 weeks, $150 (incentives)

#### Experiment 2: Manual Concierge for 5 Sales Reps
- **Tests:** Assumptions #1, #2, #4
- **Method:** Manually monitor news and send daily lead reports for 2 weeks
- **Success Metric:** 80%+ find leads relevant, 50%+ convert to outreach, 3+ meetings booked
- **Time/Cost:** 3 weeks, $100 (news subscriptions)

#### Experiment 3: News Filtering Prototype
- **Tests:** Assumptions #4, #6
- **Method:** Build basic news aggregator with AI filtering, test with 10 users
- **Success Metric:** 70%+ relevance rate, 4/5 stars, leads actionable
- **Time/Cost:** 4 weeks, $800 (development + APIs)

#### Experiment 4: Landing Page + Pre-sales
- **Tests:** Assumptions #3, #9
- **Method:** Landing page targeting sales teams, offer $200 for 3-month beta
- **Success Metric:** 5%+ conversion, 20+ sign-ups, CAC under $400
- **Time/Cost:** 2 weeks, $1000 (ads)

#### Experiment 5: Data Cost Analysis
- **Tests:** Assumption #8
- **Method:** Calculate actual costs for news APIs, contact data per user
- **Success Metric:** Total data costs under 40% of subscription price
- **Time/Cost:** 1 week, $0

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
