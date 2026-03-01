# OpenClaw AI-PRD Templates

**Workflow:** GitHub-first systematized project planning and execution

---

## 🎯 About

This repository contains **AI-powered project templates** for CodeSpring-style software development. Use these templates to break down any project into 4 core components, research competitors, and receive complete PRDs (Frontend + Backend + Database) from Astro Boy AI.

---

## 🚀 Quick Start (For New Projects)

### Step 1: Create Project Folder
```bash
# On your Mac - create a new project folder
mkdir -p ~/my-projects/[PROJECT NAME]
cd ~/my-projects/[PROJECT NAME]

# Clone workflow templates from GitHub
git clone https://github.com/one7L/one7L-SAAS-AI-PRD-Templates.git
```

### Step 2: Start New Project
```bash
# Copy workflow template
cp one7L-SAAS-AI-PRD-Templates/project-workflow-template.md [PROJECT NAME]-workflow.md

# Commit and push
git add .
git commit -m "Start [PROJECT NAME]"
git push origin main
```

### Step 3: Fill Out 4 Sections

**Edit `[PROJECT NAME]-workflow.md` and fill in:**

#### 1. TECH STACK
- Frontend Framework: `[e.g., React, Vue, Next.js]`
- Backend Framework: `[e.g., Node.js, Django, Rails]`
- Database: `[e.g., Postgres, MongoDB, Supabase]`
- Hosting: `[e.g., Vercel, Fly.io, AWS]`
- AI Integration: `[e.g., Claude, Cursor, OpenAI]`
- Authentication: `[e.g., Supabase Auth, Clerk, Custom]`
- Primary APIs: `[List external APIs needed]`
- Third-Party Services: `[List integrations required]`
- Payment Processing: `[e.g., Stripe, Lemon Squeezy]`

#### 2. COMPETITOR FEATURES
**Top 3-5 Competitors:**

**Competitor 1:** `[NAME]`
- Features to Copy: `[List]`
- Features to Improve: `[List]`
- Pricing: `[Link or notes]`
- Weaknesses: `[List]`

**Competitor 2:** `[NAME]`
- Features to Copy: `[List]`
- Features to Improve: `[List]`
- Pricing: `[Link or notes]`
- Weaknesses: `[List]`

**Competitor 3:** `[NAME]`
- Features to Copy: `[List]`
- Features to Improve: `[List]`
- Pricing: `[Link or notes]`
- Weaknesses: `[List]`

**Differentiation Strategy:**
- Unique Value Prop: `[What makes this different?]`
- Market Position: `[Premium, Budget, Niche, etc.]`

#### 3. FEATURES

**Core Features (MVP):**

**Feature 1:** `[NAME]`
- User Story: `[As a user, I want to...]`
- Acceptance Criteria: `[How do we know it's done?]`
- Complexity: `[Low | Medium | High]`

**Feature 2:** `[NAME]`
- User Story: `[As a user, I want to...]`
- Acceptance Criteria: `[How do we know it's done?]`
- Complexity: `[Low | Medium | High]`

**Feature 3:** `[NAME]`
- User Story: `[As a user, I want to...]`
- Acceptance Criteria: `[How do we know it's done?]`
- Complexity: `[Low | Medium | High]`

**Nice-to-Have Features (Post-MVP):**
- `[List prioritized features for v2, v3, etc.]`

#### 4. TARGET AUDIENCE

**Primary User Persona:**
- Demographics: `[Age, location, profession]`
- Technical Level: `[Non-technical | Semi-technical | Technical]`
- Pain Points: `[What problems do they have?]`
- Goals: `[What are they trying to achieve?]`

**Secondary Audiences:**
- `[List other user segments]`

**Success Metrics:**
- Key Metric 1: `[e.g., 10,000 app builds/month]`
- Key Metric 2: `[e.g., 50% faster development]`
- Key Metric 3: `[e.g., 90% user satisfaction]`

---

## 📋 Step 4: Gather Research & Documentation

### What to Collect
- Market research (articles, reports, statistics)
- User interviews or surveys
- Competitor screenshots/websites
- Existing documentation (if any)
- Reference materials (similar apps, frameworks)

### Create Research Folders
```bash
cd ~/my-projects/[PROJECT NAME]
mkdir -p research/competitors
mkdir -p research/user-interviews
mkdir -p research/market-analysis
mkdir -p research/references
```

### Upload Research
Upload all PDFs, images, notes, screenshots to the appropriate research/ folder.

---

## 🤖 Step 5: Contact Astro Boy for AI Analysis

### Message Template

Send this message when you're ready for PRD generation:

```
I'm ready to analyze [PROJECT NAME]. I've filled out the workflow template with:

- Tech Stack decisions
- Competitor analysis
- Feature breakdown
- Target audience definition

All docs are in: ~/my-projects/[PROJECT NAME]/research/

Please analyze everything in my research folder + my workflow template, then generate:

1. Frontend PRD (with component breakdown)
2. Backend PRD (with API endpoints)
3. Database PRD (with schema design)

Ready when you are!
```

---

## 📄 Step 6: Receive 3 Complete PRDs

Astro Boy will analyze all your research and generate:

### Frontend PRD
- Tech Stack Confirmation
- Component Breakdown (Page 1, Page 2, Page 3)
- State Management
- UI/UX Patterns

### Backend PRD
- Tech Stack Confirmation
- API Endpoints (GET, POST, PUT, DELETE)
- Business Logic
- Authentication/Authorization

### Database PRD
- Schema Design
- Relationships
- Indexes
- Performance Considerations

---

## 📋 Step 7: Review & Approve PRDs

Review all 3 PRDs carefully:

1. Check for clarity
2. Ask clarifying questions if needed
3. Accept or refine PRDs
4. Make adjustments as necessary

---

## 📋 Step 8: Development Execution

### Follow PRDs Exactly
- Frontend PRD → Build pages, components, routes
- Backend PRD → Build API endpoints, business logic
- Database PRD → Create tables, relationships

### Track Progress
- Mark completed items as you go
- Track blockers and ask for help when stuck

---

## 📋 Step 9: Update Progress

As you complete work, update your project workflow file:

### Implementation Checklist
- Mark what's done with `[x]`
- Track what's in progress with `[ ]`

### Success Metrics
- Track actual performance vs targets

### Iteration Plan
- Plan next versions (v2, v3)

### Notes
- Document learnings, blockers, decisions

---

## 📁 Project Structure (After Setup)

```
~/my-projects/[PROJECT NAME]/
├── [PROJECT NAME]-workflow.md          # Main planning doc (4 sections)
├── research/                           # All research docs
│   ├── competitors/
│   ├── user-interviews/
│   ├── market-analysis/
│   └── references/
├── prd-frontend.md                    # Frontend specification (generated by Astro Boy)
├── prd-backend.md                     # Backend specification (generated by Astro Boy)
└── prd-database.md                    # Database design (generated by Astro Boy)
```

---

## 🔄 Step 10: Repeat for Next Project

When ready to start a new project:

1. Create new project folder
2. Clone workflow templates (or pull latest)
3. Copy template for new project
4. Repeat workflow from Steps 2-9

---

## 🎯 Benefits of This System

### Version Control
- Every change tracked automatically
- Full history of all project files
- Easy to roll back if needed

### Bi-Directional Sync
- You push updates from Mac
- Astro Boy pulls updates from GitHub
- Both stay in sync automatically

### Professional Workflow
- Industry-standard Git workflow
- Easy collaboration (team members can access repo)
- Backup protection (GitHub keeps copies)

### Organization
- All project files in one place
- Consistent structure across all projects
- Easy to search and reference

---

## 📚 Additional Templates

Available in this repository:

### Workflow Guides
- `project-workflow-template.md` - 4-component project structure
- `code-workflow-implementation-guide.md` - Step-by-step usage instructions

### CodeSpring Research
- `codespring-complete-summary.md` - Complete feature breakdown (50+ sub-features)
- `codespring-master-index.md` - Quick reference index

---

## 🚀 Get Started Now!

For your next project, follow the **Quick Start** steps above to break down any software project systematically and receive complete PRDs from AI.

**Questions?** Check `code-workflow-implementation-guide.md` for detailed step-by-step instructions.
