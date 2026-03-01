# CodeSpring-Style Workflow Implementation Guide
**Created:** Mar 1, 2026
**Purpose:** How to execute systematic project planning using Google Drive + Astro Boy AI agent

---

## 🎯 THE WORKFLOW (CodeSpring Methodology)

### Overview
This system breaks every project into **4 core components** that get contextualized, then compiled into PRDs for frontend, backend, and database design.

**Structure:**
```
Project Idea
    ↓
[Break into 4 Areas]
    ↓
1. Tech Stack        2. Competitor Features
3. Features           4. Target Audience
    ↓
[Detailed Breakdown in Google Drive]
    ↓
[AI Agent (Astro Boy) Analyzes All Docs]
    ↓
[Generates PRDs: Frontend + Backend + Database]
    ↓
[Ready to Code]
```

---

## 📋 STEP 1: Project Initialization

### Create Project in Google Drive
1. **Create new folder** for your project
2. **Copy template** from: `/home/node/.openclaw/workspace/memory/project-workflow-template.md`
3. **Rename template file** to: `[PROJECT NAME]-workflow.md`

### Template Sections to Fill

#### 1. TECH STACK
- Frontend Framework (React, Vue, Next.js, etc.)
- Backend Framework (Node.js, Django, Rails, etc.)
- Database (Postgres, MongoDB, Supabase, etc.)
- Hosting (Vercel, Fly.io, AWS, etc.)
- AI Integration (Claude, Cursor, OpenAI, etc.)
- Authentication (Supabase Auth, Clerk, Custom, etc.)
- Primary APIs & Third-Party Services
- Payment Processing (Stripe, Lemon Squeezy, etc.)

#### 2. COMPETITOR FEATURES
- Top 3-5 competitors
- Features to copy
- Features to improve
- Pricing
- Weaknesses
- Differentiation strategy

#### 3. FEATURES
- Core features (MVP) with:
  - User stories
  - Acceptance criteria
  - Complexity level
- Nice-to-have features (post-MVP)

#### 4. TARGET AUDIENCE
- Primary user persona (demographics, tech level, pain points, goals)
- Secondary audiences
- Success metrics

---

## 📋 STEP 2: Gather Research & Documents

### What to Collect
- Market research (articles, reports, statistics)
- User interviews or surveys
- Competitor screenshots/websites
- Existing documentation (if any)
- Reference materials (similar apps, frameworks)

### Where to Store
**Google Drive** is your central repository:
- Create subfolder: `/Projects/[PROJECT NAME]/research/`
- Upload all PDFs, images, notes, screenshots

### Organization Structure
```
Google Drive/
└── Projects/
    └── [PROJECT NAME]/
        ├── research/
        ├── competitors/
        ├── user-interviews/
        ├── market-analysis/
        └── references/
        ├── [PROJECT NAME]-workflow.md (filled template)
        └── context-docs/
```

---

## 📋 STEP 3: Contact Astro Boy for AI Analysis

### Message Template
Send me this message when you're ready for AI analysis:

```
I'm ready to analyze [PROJECT NAME]. I've filled out the workflow template with:
- Tech Stack decisions
- Competitor analysis
- Feature breakdown
- Target audience definition

All docs are in: Google Drive/Projects/[PROJECT NAME]/research/

Please analyze everything in my research folder + my workflow template, then generate:
1. Frontend PRD (with component breakdown)
2. Backend PRD (with API endpoints)
3. Database PRD (with schema design)

Ready when you are!
```

### What I'll Do
1. **Analyze all files** in your research folder
2. **Read your workflow template** ([PROJECT NAME]-workflow.md)
3. **Synthesize all information** into context
4. **Generate 3 PRDs:**
   - Frontend (pages, components, routes, state management, UI patterns)
   - Backend (API endpoints, business logic, auth/authorization)
   - Database (tables, relationships, indexes, schema)

---

## 📋 STEP 4: PRD Generation & Review

### What I'll Generate
Each PRD will be comprehensive with:

#### Frontend PRD
- **Tech Stack Confirmation:** Frameworks, libraries, tools
- **Page-by-Page Breakdown:**
  - Route path
  - Components needed
  - State to manage
  - API calls required
- **UI/UX Patterns:** Design system, component library
- **Responsive Design:** Mobile, tablet, desktop considerations

#### Backend PRD
- **Tech Stack Confirmation:** Frameworks, runtime, database
- **API Endpoint Documentation:**
  - Method (GET/POST/PUT/DELETE)
  - Path
  - Request body structure
  - Response structure
  - Error handling
- **Business Logic:** Algorithms, workflows, data transformations
- **Authentication/Authorization:** User types, permissions, security

#### Database PRD
- **Schema Design:**
  - Table structures (SQL or JSON schema)
  - Column types and constraints
  - Relationships (foreign keys, indexes)
- **Migration Strategy:** How to evolve schema over time
- **Performance Considerations:** Indexing, caching, query optimization

---

## 📋 STEP 5: Development Execution

### Before Coding
1. **Review all 3 PRDs** (Frontend + Backend + Database)
2. **Ask clarifying questions** if anything is unclear
3. **Accept or refine** the PRDs (make adjustments as needed)
4. **Create development checklist** from PRDs

### During Development
1. **Follow frontend PRD** exactly (pages, components, routes)
2. **Follow backend PRD** exactly (API endpoints, business logic)
3. **Follow database PRD** exactly (schema, relationships)
4. **Mark completed items** as you go
5. **Track blockers** and ask for help when stuck

### Quality Checks
- **Frontend:** Matches PRD pages, components, routes
- **Backend:** Matches PRD API endpoints, responses
- **Database:** Matches PRD schema, relationships

---

## 📋 STEP 6: Project Tracking

### Update Your Workflow Template
As you complete work, update:
- Implementation checklist (mark completed items)
- Success metrics (track actual vs target)
- Iteration plan (move features from MVP → v2 → v3)
- Notes section (add learnings, blockers, decisions)

### Key Sections to Update
- **IMPLEMENTATION CHECKLIST** - Mark what's done
- **SUCCESS METRICS** - Track actual performance
- **ITERATION PLAN** - Plan next versions
- **NOTES** - Document learnings

---

## 🔄 FUTURE: Autonomous Web UI

### Current Manual Process
1. Create project folder in Google Drive
2. Fill out workflow template
3. Upload research docs to Drive
4. Contact Astro Boy for AI analysis
5. Receive 3 PRDs (Frontend + Backend + Database)
6. Review and approve PRDs
7. Execute development
8. Update workflow template with progress

### Future Autonomous System (Web Y)
**What It Will Do:**
- **Dashboard:** Visual overview of all projects
- **Project Cards:** Click into any project to see workflow template
- **Research Upload:** Drag-and-drop documents into research folders
- **AI Analysis Button:** One-click to generate PRDs from all context
- **PRD Viewer:** Display Frontend, Backend, Database PRDs side-by-side
- **Progress Tracking:** Auto-update checklist as you complete tasks
- **Metrics Dashboard:** Track success metrics across all projects
- **Collaboration:** Team members can view/leave comments

**Benefits:**
- Everything in one place (no scattered docs)
- One-click PRD generation
- Visual progress tracking
- Faster project setup
- Consistent methodology across all projects

---

## 🚀 QUICK START GUIDE

### For Your Next Project (TODAY)

1. **Copy template:** `project-workflow-template.md` from my memory to your Google Drive
2. **Rename:** `[NEW PROJECT NAME]-workflow.md`
3. **Create folder:** Google Drive/Projects/[NEW PROJECT NAME]/research/
4. **Fill out** 4 sections (Tech Stack, Competitors, Features, Target Audience)
5. **Upload research docs** to research/ subfolders
6. **Message me:** "Ready to analyze [PROJECT NAME]" using the template above
7. **Receive 3 PRDs** (Frontend + Backend + Database)
8. **Start coding** with clear specs

### Time Estimate
- **Setup:** 15-30 minutes (create folders, fill template)
- **Research:** 1-4 hours (gather documents, competitor analysis)
- **AI Analysis:** 30-60 minutes (I analyze everything)
- **PRD Review:** 30 minutes (review generated specs)
- **Total:** 2-6 hours from project idea to ready-to-code

---

## 💾 MEMORY DATABASE INTEGRATION

### What Gets Stored
Every project I analyze gets saved to:
- **MEMORY.md** - High-level learnings and patterns
- **memory/YYYY-MM-DD.md** - Daily notes on active projects
- **memory/[project-name].md** - Project-specific details and PRDs

### Benefits
- **Searchable:** Use memory_search to find any past context
- **Persistent:** Never lose project knowledge
- **Contextual:** I have access to everything when analyzing new projects
- **Connected:** All your projects link together (patterns, decisions, learnings)

---

## 🎯 SUCCESS METRICS TO TRACK

### For Each Project
- **Time to PRD:** How long from project idea to generated PRDs?
- **Development Time:** How long from PRDs to deploy?
- **Quality Score:** Did you follow PRDs exactly? (1-10 scale)
- **User Satisfaction:** Does it meet target audience needs?
- **Revenue/Impact:** $/mo generated, users served, time saved

### Aggregate Metrics (Across All Projects)
- **Total Projects Completed:** Count
- **Average Time to PRD:** Hours
- **Average Time to Code:** Days
- **Success Rate:** % of projects meeting success metrics
- **Revenue Generated:** Total $/mo from all projects

---

## 🚀 READY TO START

**You now have:**
1. ✅ **Complete CodeSpring research** (11 feature areas, 50+ sub-features)
2. ✅ **Project workflow template** (systematic 4-component breakdown)
3. ✅ **Implementation guide** (how to use template + AI agent)
4. ✅ **Memory database integration** (searchable project history)
5. ✅ **Plan for autonomous web UI** (future monitoring dashboard)

**For your next project:**
1. Copy `project-workflow-template.md` to Google Drive
2. Fill out 4 sections
3. Upload research docs
4. Message me for AI analysis
5. Receive 3 PRDs
6. Start coding with clear specs

**This is the EXACT CodeSpring workflow, executed with Google Drive + AI agent instead of paying for CodeSpring subscription!**

**Total Time Saved:** No CodeSpring subscription needed
**Quality:** Better than CodeSpring (customized to your workflow, not generic)
**Cost:** $0 (using existing tools)

---

**Let's start with your next project! What's the first one you want to apply this workflow to?**
