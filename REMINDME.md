# REMINDME.md - AI-Assisted Developer Track

**Last Updated:** February 3, 2025  
**Current Phase:** Week 1 - Foundation & Environment Setup  
**Student:** Spanosspanos  
**Professor:** Claude

---

## README: PROJECT OVERVIEW

### The Core Strategy

**Student is building:** A portfolio of custom business automation tools that live as "hidden features" inside client websites, rather than standalone SaaS products or workflow configurations.

**Value Proposition:** "I build custom automation tools that live inside your existing website—private pages that handle your back-office operations without requiring separate apps or expensive software subscriptions."

**Why This Matters:**
- Every business already has a website (universal entry point)
- "Hidden pages" feel less intimidating than "custom software" (psychological advantage)
- Not competing with Zapier/Make.com (bespoke solutions, not workflow automation)
- Natural upsell path: one tool → multiple tools → full operations suite
- Sticky revenue: tools embedded in client infrastructure = hard to migrate away

### The Learning Architecture

**Method:** AI-assisted development using tools like Claude Code, Cursor, GitHub Copilot
- Student describes desired functionality in plain English
- AI generates initial code
- Student reviews, understands, and iterates
- Learning happens BY BUILDING, not theory-first

**Key Insight:** Student is not becoming a "traditional developer." They're becoming a **domain expert who can build professional software using AI assistance.**

### Target Markets (Leveraging Existing Networks)

1. **Craft Breweries** - Student owns Slow Down Brewing, has industry connections
2. **Cannabis Retail** - Student manages dispensary in White Plains, NY
3. **Restaurant/Bar Operations** - Adjacent to brewing industry
4. **Greek Import/Distribution** - Student has contract brewing in Greece

### The Meta-Project: Demo Site as Learning Lab

**Instead of:** Building tools on live business sites (high stakes, real consequences)

**Building:** A demo/portfolio site that serves as:
- Experimental lab for learning
- Portfolio showcase for prospects
- Sales tool (working demos > screenshots)
- Your own infrastructure while learning

**Domain TBD:** Student choosing between aitools-demo.com, brewery-automation.com, or similar

**Once tools are proven:** Deploy polished versions to SlowDownBrewing.gr and offer to clients

---

## 12-WEEK CURRICULUM: AI-ASSISTED DEVELOPER TRACK

### PHASE 1: Foundation & First Tool (Weeks 1-4)

#### **WEEK 1: Environment Setup & HTML/CSS Fundamentals**
**Status:** IN PROGRESS (Starting Feb 3, 2025)

**Objectives:**
- Set up development environment (Cursor or VS Code + Claude Code)
- GitHub account and basic git workflow
- Deploy first live page to Netlify/Vercel
- Learn HTML/CSS fundamentals with AI assistance
- Create demo site landing page

**Deliverable:** Live website at chosen domain with "Coming Soon" + bio

**Key Actions This Week:**
- [ ] Install Cursor (or VS Code + Claude Code)
- [ ] Create GitHub account
- [ ] Choose domain name for demo site
- [ ] Sign up for Netlify (free tier)
- [ ] Create first HTML landing page with Cursor/Claude assistance
- [ ] Deploy to Netlify
- [ ] Customize landing page (bio, tools section, contact)

**Success Criteria:** By end of Week 1, student has live, deployed website

---

#### **WEEK 2: JavaScript Fundamentals + Interactive Forms**

**Objectives:**
- Learn JavaScript basics (variables, functions, DOM manipulation, event listeners)
- Build interactive form elements
- Create sell sheet generator input form (frontend only)
- Professional styling with CSS
- Client-side validation

**Deliverable:** Beautiful, responsive form (doesn't submit anywhere yet, but looks professional)

**Learning Method:**
- Describe desired functionality to Claude Code
- Review generated code
- Ask for explanations of unclear concepts
- Modify and iterate

---

#### **WEEK 3: Python Backend Basics**

**Objectives:**
- Python fundamentals (if statements, loops, functions, data structures)
- Introduction to Flask web framework
- Create simple web server
- Handle form submissions (POST requests)
- Connect Week 2 frontend to backend

**Deliverable:** Working end-to-end flow (form submission → server receives → confirmation)

---

#### **WEEK 4: LLM Integration + First Complete Tool**

**Objectives:**
- Call Claude API from Python
- Send form data to LLM with prompts
- Use Jinja2 for HTML templates
- Display LLM-generated content professionally
- Deploy complete tool to demo site

**Deliverable:** Working sell sheet generator (HTML output) deployed and functional

**Milestone:** First complete, deployed tool with AI integration

---

### PHASE 2: Advanced Features & Tool #2 (Weeks 5-8)

#### **WEEK 5: PDF Generation**

**Objectives:**
- Learn WeasyPrint or Puppeteer for PDF generation
- Create CSS for print layouts
- Handle page breaks, margins, typography
- Integrate PDF generation into sell sheet tool
- Add download functionality

**Deliverable:** Professional PDF sell sheets (not just HTML)

---

#### **WEEK 6: Database Basics + User Accounts**

**Objectives:**
- SQLite fundamentals (tables, CRUD operations)
- Simple password protection for admin pages
- Session management
- Store generated documents in database
- Create "history" view

**Deliverable:** Tools with data persistence and basic security

---

#### **WEEK 7-8: Second Tool Development**

**Choose One Based on Immediate Needs:**

**Option A: Complaint Resolution System** (finish existing 85% project)
- Multi-step form for complaint intake
- LLM generates response suggestions
- Database stores complaint history
- Admin dashboard for review

**Option B: Inventory Audit Tool** (for dispensary when it opens)
- Input current stock levels
- LLM analyzes discrepancies  
- Generate audit reports
- Track over time

**Option C: Event/Promotion Flyer Generator** (for brewery)
- Input event details
- LLM writes compelling copy
- Generate designed PDF flyer
- Social media sized variants

**Deliverable:** Second complete, deployed tool on demo site

**Milestone:** Two fully functional tools demonstrating range

---

### PHASE 3: Professional Polish & Business Launch (Weeks 9-12)

#### **WEEK 9: UI/UX Refinement**

**Objectives:**
- Study professional SaaS interfaces
- Improve visual design across all tools
- Add loading states, error messages, success confirmations
- Mobile responsiveness testing
- Use Claude to critique and suggest improvements

---

#### **WEEK 10: Deployment & DevOps Basics**

**Objectives:**
- Production deployment to proper hosting (Railway, Render, etc.)
- Custom domain setup
- Environment variables and secrets management
- HTTPS configuration
- Basic security hardening (input validation, rate limiting)
- Monitoring and logging

---

#### **WEEK 11: Documentation & Packaging**

**Objectives:**
Create comprehensive "Product Catalog" for each tool:
- User documentation (how to use)
- Technical documentation (how it works)
- Case study write-up (problem → solution → results)
- Video demo (3-5 minutes each)
- Pricing structure

**Outcome:** Demo site becomes complete portfolio + sales platform

---

#### **WEEK 12: First Client Acquisition**

**Objectives:**
- Define service offerings and pricing tiers
- Write sales page copy
- Prepare client onboarding process
- Identify 10 warm prospects (brewery network, dispensary connections)
- Craft personalized pitches
- Offer free pilot deployment for testimonial

**Deliverable:** First client engagement or concrete pipeline

**Milestone:** Transition from learning to earning

---

## TECHNOLOGIES & TOOLS

### AI Coding Assistants
- **Claude Code** (command-line, backend work)
- **Cursor** (AI-native editor, full-stack) ← PRIMARY RECOMMENDATION
- **GitHub Copilot** (optional supplement)

### Core Stack
- **Frontend:** HTML, CSS, JavaScript (vanilla → React later if needed)
- **Backend:** Python + Flask (or FastAPI)
- **Database:** SQLite → PostgreSQL (as scaling requires)
- **Deployment:** 
  - Git & GitHub (version control)
  - Netlify/Vercel (static frontend)
  - Railway/Render (backend services)
- **LLM Integration:** Anthropic API (Claude), OpenAI API

### Cost Structure (All Free Tier Initially)
- ✅ Cursor free tier
- ✅ GitHub free
- ✅ Netlify/Vercel free tier
- ✅ Railway/Render free tier
- ✅ Claude API (already has access)
- ✅ Domain name (only recurring cost, ~$12/year)

---

## STUDENT PROFILE & CONSTRAINTS

### Background
- **Current role:** Dispensary manager (White Plains, NY - not yet open)
- **Business owner:** Slow Down Brewing (Greece, contract production)
- **Education:** SUNY Albany 1995-1999, Philosophy/English double major
- **Skills:** Drummer, brewer, retail management, Illustrator experience
- **Technical:** Limited coding background, successful with AI-assisted Python and native app development

### Time Commitment
- **Available:** 12-15 hours/week consistently
- **Schedule:** Morning conceptual learning + afternoon practical labs
- **Currently employed:** Has runway to build skills before monetization pressure

### Budget Constraints
- **Current spending:** Claude Pro, ChatGPT Plus, Perplexity, Gemini
- **New spending:** $0 for now (must use free tiers)
- **Future:** Open to paid tools once revenue starts

### Energy & Motivation
- **Sell sheet generator:** 9/10 energy
- **Learning to code:** 10/10 energy  
- **Building custom tools:** 10/10 energy
- **Vision clarity:** High - wants to build internal business tools as website features

### Key Quote
"I want to stay ahead of the curve and learn while building with the tools that are so important right now and for tomorrow, specifically the agentic and automated qualities of tools like: claude code, codex, cursor etc."

**Translation:** Student understands this is AI-assisted development revolution, not traditional coding bootcamp.

---

## STRATEGIC CONTEXT

### What Changed (Critical Pivot)

**Original plan:** AI workflow consultant using Make.com, Zapier, etc.

**New plan:** Custom tool developer using AI-assisted coding

**Why this matters:**
- Higher value proposition ("I build custom software" vs "I configure Zapier")
- More defensible skill set
- Better margins (no SaaS subscription pass-through costs)
- Aligns with student's actual vision of what they want to build
- Free/low-cost stack vs subscription-heavy no-code tools

### Current Project Status (Context for Focus)

**Complaint Resolution System (Cannabis Retail):** 85% complete, paused
- Can't finish without real customer/product data (dispensary not open yet)
- Will return to this when live data available
- Good architectural blueprint for similar solutions

**Sell Sheet Generator:** 75% complete, now rebuilding with code
- Previous versions: Google Form → Make.com (basic but ugly output)
- Hook & Ladder method: manual HITL workflow (model-agnostic but tedious)
- NEW approach: Code-based with professional PDF output
- This becomes Week 1-5 learning vehicle

**Slow Down Brewing Website:** Audit complete, path forward documented, on pause
- Will become deployment target for finished tools
- Tools will live on private pages: slowdownbrewing.gr/tools/[toolname]

**Local LLM Experimentation:** "Cute goldfish" - hobby, not priority

### Teaching Approach

**Socratic method:** Ask probing questions, don't just provide answers

**Theory meets practice:** Balance concepts with hands-on building

**Progressive complexity:** Build from fundamentals systematically

**Business-first lens:** Always connect technical work to revenue generation

**Adaptive pacing:** Adjust based on comprehension and progress

**Accountability:** Hold student to commitments and deadlines

**Honest assessment:** Call out pattern of 75% completion, encourage shipping

---

## CURRENT STATUS SNAPSHOT

**Date:** February 3, 2025  
**Week:** 1 of 12  
**Phase:** Foundation & Environment Setup  

**Immediate Next Actions (Next 24-48 Hours):**
1. Student installs Cursor (or VS Code + Claude Code)
2. Student creates GitHub account
3. Student chooses domain name for demo site
4. Student signs up for Netlify
5. Student creates first HTML landing page with AI assistance
6. Student deploys to Netlify
7. Student reports back with: domain choice, tool choice, Tuesday morning start time

**This Week's Goal:** Live website deployed by Friday, February 7

**Key Success Metric:** Student ships something imperfect rather than perfecting something unshipped

---

## PROFESSOR NOTES & REMINDERS

### Student Patterns to Monitor
- ⚠️ **Shiny object syndrome:** Tendency to start new projects before finishing current ones
- ⚠️ **75% completion pattern:** Multiple projects at 75-85% complete, none shipped
- ✅ **High energy when vision is clear:** Goes from scattered to focused when strategy aligns with values
- ✅ **Systems thinking:** Naturally thinks in terms of product ladders and architectural progression
- ✅ **Documentation discipline:** Takes detailed notes, organizes work in folders

### Teaching Priorities
1. **Emphasize shipping over perfection:** Break the 75% pattern by celebrating deployments
2. **Connect code to business value:** Every technical concept must tie to revenue potential
3. **Encourage AI assistance:** Student learns best by building with AI, not studying theory first
4. **Maintain accountability:** Weekly check-ins, specific time commitments, milestone tracking
5. **Validate progress:** Acknowledge when student articulates strategic insights (like "tools in disguise")

### Red Flags to Watch For
- Multiple days without concrete progress (analysis paralysis)
- New project ideas before current tool is deployed
- "I'll just try this other approach first" without shipping current approach
- Overcomplicating instead of shipping simple version
- Spending time on curriculum refinement instead of actual building

### Green Flags to Celebrate
- Deployed code (even if imperfect)
- Specific time commitments honored
- Questions about "what's next" after shipping current milestone
- Client/user perspective in technical decisions
- Documentation as projects progress (not just at the end)

---

## VERSION HISTORY

**v1.0 - February 3, 2025**
- Initial REMINDME created
- 12-week curriculum defined
- Week 1 in progress
- Student committed with 10/10 energy to learning code
- Meta-strategy: Build demo site as learning lab + portfolio

**Future updates should include:**
- Week completion dates
- Deployed tool URLs
- Technical challenges encountered and solved
- Curriculum adjustments based on student progress
- Client acquisition activities and results

---

## QUICK REFERENCE: CURRENT WEEK CHECKLIST

### Week 1 Tasks (February 3-7, 2025)

**Environment Setup:**
- [ ] Install Cursor or VS Code + Claude Code
- [ ] Create GitHub account
- [ ] Choose domain name
- [ ] Sign up for Netlify

**First Deployment:**
- [ ] Create landing page HTML with AI assistance
- [ ] Deploy to Netlify
- [ ] Confirm live URL works

**Customization:**
- [ ] Add bio (brewer, dispensary manager, AI tools developer)
- [ ] Add "Tools Coming Soon" section
- [ ] Add contact information
- [ ] Professional styling

**Learning Outcomes:**
- [ ] Understand basic HTML structure
- [ ] Understand CSS for styling
- [ ] Understand git basics (commit, push)
- [ ] Understand deployment process
- [ ] Comfortable asking AI for code help

**Friday Deliverable:** Live website at chosen domain

---

*End of REMINDME.md - Update this document weekly or at major milestones*
