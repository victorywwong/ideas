# Seen.ai

## Overview
A workplace Q&A platform where employees interact with an AI bot that automates daily updates, making work visible and reducing status meeting overhead.

## Problem Statement
People work to be seen and recognized, but constant status updates are time-consuming. Daily standups, status reports, and visibility work take time away from actual productive work.

## Target Audience
- Remote teams
- Product/engineering teams
- Distributed organizations
- Managers tracking team progress
- Individual contributors wanting visibility

## Core Features
- Daily check-in conversations with AI bot
- Automated status summaries for managers
- Question answering about "what are you working on?"
- Integration with work tools (Jira, GitHub, Slack, etc.)
- Natural language queries about team progress
- Async updates instead of meetings
- Recognition and highlights surfacing

## Value Proposition
Stay visible without the overhead - let AI handle status updates and team transparency automatically through natural conversation.

## Technical Approach
- LLM for conversational check-ins
- Integration with work management tools APIs
- Slack/Teams bot interface
- Dashboard for managers and teams
- Natural language processing for status extraction
- Privacy controls for sensitive work

## Market Analysis
### Competitors
- Status Hero, Geekbot (scheduled check-ins, less AI-driven)
- Slack status updates (manual)
- Standup meetings (time-consuming)
- Range, Know Your Team (more survey-focused)

### Business Model
- Per-seat pricing ($5-10/user/month)
- Team plans
- Enterprise licensing

## Next Steps
- [ ] Survey remote workers on status update pain points
- [ ] Design conversation patterns for daily check-ins
- [ ] Build Slack bot prototype
- [ ] Test with small team for 2 weeks

## Business Model Canvas

### Customer Segments
- Remote-first companies (10-500 employees)
- Distributed engineering/product teams
- Agencies with client-facing teams
- Startups wanting transparency without meetings
- Managers leading distributed teams
- Individual contributors wanting visibility

### Value Propositions
- Async status updates eliminate standup meetings
- Natural conversation vs. rigid forms
- Automated visibility for managers
- Less time on status reporting, more on work
- Team progress always accessible
- Recognition and highlights surfaced automatically

### Channels
- Slack/Teams app marketplace
- Direct sales to remote companies
- Product Hunt launch
- Remote work communities and forums
- Content marketing (remote work best practices)
- Partnerships with remote work tools
- Word of mouth from satisfied teams

### Customer Relationships
- Self-service bot setup and onboarding
- In-app chat support
- Community Slack for users
- Regular feature updates
- Manager dashboards and insights
- Team health reports

### Revenue Streams
- Per-seat pricing ($5-10/user/month)
- Team plans (10+ users, volume discounts)
- Enterprise plans with:
  - Custom integrations
  - Advanced analytics
  - SSO and security features
  - Dedicated support
- Annual subscriptions (2 months free)

### Key Resources
- LLM infrastructure for conversations
- Slack/Teams API integrations
- Work tool integrations (Jira, GitHub, Linear)
- Analytics and dashboard platform
- User conversation data and patterns
- Customer support team

### Key Activities
- AI conversation model training
- Integration development and maintenance
- Manager dashboard development
- Natural language status extraction
- User privacy and data security
- Customer success and support
- Product iteration based on feedback

### Key Partnerships
- Slack, Microsoft Teams
- Work management tools (Jira, Linear, Asana)
- GitHub, GitLab (for developer activity)
- Remote work communities
- HR and people ops consultants
- Remote-first company advisors

### Cost Structure
- AI/LLM API costs
- Cloud hosting and infrastructure
- Integration maintenance
- Product development
- Sales and marketing
- Customer support
- Compliance and security

## Value Proposition Canvas

### Customer Profile

#### Customer Jobs
- Keep team informed of progress
- Stay visible to manager and peers
- Track what everyone is working on
- Report status without meetings
- Get recognition for work done
- Understand team capacity and blockers
- Make async collaboration work

#### Pains
- Daily standups feel like interruptions
- Writing status reports is tedious
- Hard to get visibility for remote work
- Manual updates take time from actual work
- Status meetings don't scale across timezones
- Work goes unnoticed and unappreciated
- Information scattered across multiple tools
- Difficult to track team progress
- Status Hero/Geekbot feels rigid and form-like

#### Gains
- More time for deep work
- Async communication that works
- Recognition from managers and peers
- Visibility without overhead
- Better team coordination
- Clear understanding of who's doing what
- Less meeting fatigue
- Work is seen and valued

### Value Map

#### Products & Services
- Conversational AI check-in bot
- Natural language status extraction
- Manager dashboard with team overview
- Integration with work tools (Jira, GitHub)
- Automated status summaries
- Question answering about team progress
- Recognition and highlight surfacing
- Analytics on team health and velocity
- Slack/Teams native interface

#### Pain Relievers
- Natural conversation vs. rigid forms
- 2-minute daily check-in vs. 30-min standup
- Automatic visibility without manual reporting
- AI writes summaries for managers
- Async across all timezones
- Work automatically surfaced and recognized
- Single source for team status
- Weekly summaries auto-generated
- Feels helpful, not surveillance-like

#### Gain Creators
- Save 2.5 hours/week per person (eliminate meetings)
- Increase deep work time by 15%+
- 3x more frequent recognition/highlights
- Real-time team progress visibility
- Better cross-timezone collaboration
- Improved team morale (feeling seen)
- Data-driven insights on team health
- Reduced meeting fatigue

## Testing Business Ideas

### Critical Assumptions to Test

#### Desirability Assumptions
1. **Remote workers dislike daily standup meetings**
   - Risk: Medium | Evidence: Medium (common complaint)

2. **Conversational check-ins preferred over forms**
   - Risk: High | Evidence: Low

3. **Managers willing to replace standups with AI tool**
   - Risk: High | Evidence: Low

4. **Users will engage with bot daily**
   - Risk: High | Evidence: Low

#### Feasibility Assumptions
5. **AI can extract meaningful status from natural conversation**
   - Risk: Medium | Evidence: Medium

6. **Work tool integrations provide enough context**
   - Risk: Low | Evidence: High (APIs exist)

7. **Privacy concerns can be addressed**
   - Risk: High | Evidence: Medium

#### Viability Assumptions
8. **Teams willing to pay $5-10/user/month**
   - Risk: Medium | Evidence: Medium (similar tools exist)

9. **Can acquire customers at CAC under $200 per team**
   - Risk: High | Evidence: Low

10. **Churn rate under 15% monthly**
    - Risk: Medium | Evidence: Low

### Proposed Experiments

#### Experiment 1: Pain Point Survey
- **Tests:** Assumptions #1, #3
- **Method:** Survey 50 remote workers and 20 managers about status update processes
- **Success Metric:** 70%+ dislike current process, 60%+ open to AI alternative
- **Time/Cost:** 1 week, $100 (incentives)

#### Experiment 2: Wizard of Oz Bot
- **Tests:** Assumptions #2, #4, #5
- **Method:** Manually play Seen.ai bot with 2 teams (10 people) for 2 weeks
- **Success Metric:** 80%+ daily engagement, 70%+ prefer over standups, managers satisfied
- **Time/Cost:** 2 weeks, $0 (manual work)

#### Experiment 3: Slack Bot MVP
- **Tests:** Assumptions #2, #4, #5
- **Method:** Build basic Slack bot, test with 3 teams for 3 weeks
- **Success Metric:** 70%+ daily engagement rate, 4/5 stars, teams want to continue
- **Time/Cost:** 4 weeks, $500 (development + AI)

#### Experiment 4: Landing Page + Pre-sales
- **Tests:** Assumptions #8, #9
- **Method:** Landing page targeting remote teams, collect pre-orders ($50 for 3 months)
- **Success Metric:** 5%+ conversion, 20+ teams, CAC under $150
- **Time/Cost:** 2 weeks, $600 (ads)

#### Experiment 5: Manager Value Test
- **Tests:** Assumption #3
- **Method:** Show 10 managers dashboards from experiment #2, gauge interest
- **Success Metric:** 70%+ find valuable, 50%+ would replace standups
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
