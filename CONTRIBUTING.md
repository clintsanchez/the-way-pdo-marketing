# Contributing to The Way PDO Marketing Repository

Thank you for helping organize and develop The Way PDO's marketing strategy! This guide explains how to contribute effectively.

---

## Before You Start

1. **Read the documentation:**
   - [README.md](README.md) — Repository overview
   - [SETUP.md](SETUP.md) — How to get started
   - [01-Foundation/brand-voice.md](01-Foundation/brand-voice.md) — Brand voice guide

2. **Understand the structure:**
   - All files organized into 12 main folders
   - 01-Foundation contains core strategy docs
   - 06-Marketing contains campaigns and content
   - 11-Analytics-and-Performance contains tracking

3. **Get GitHub access:**
   - Clone the repo: `git clone https://github.com/clintsanchez/the-way-pdo-marketing.git`
   - Create your own branch for changes
   - See "Git Workflow" section below

---

## What Can You Contribute?

### Content & Strategy
- ✓ Blog posts, email copy, social media content
- ✓ Campaign plans and creative briefs
- ✓ Email sequences and nurture campaigns
- ✓ Content calendars and editorial plans
- ✓ Research and competitive intelligence
- ✓ Case studies and testimonials

### Brand & Design
- ✓ Brand guideline refinements
- ✓ Design assets (logos, photos, graphics)
- ✓ Website copy and structure updates
- ✓ Email templates and design systems
- ✓ Social media graphics and video

### Analytics & Performance
- ✓ Tracking setups and dashboards
- ✓ Performance reports and analysis
- ✓ ROI calculations and optimization recommendations
- ✓ Competitive benchmarking
- ✓ A/B test results and learnings

### Strategy & Planning
- ✓ Marketing strategy updates
- ✓ Campaign planning and brief templates
- ✓ Quarterly reviews and adjustments
- ✓ Budget allocation recommendations
- ✓ Process improvements and best practices

---

## Git Workflow

### 1. Create a Branch

**For small changes (typos, minor updates):**
```bash
git checkout -b fix/brand-voice-typo
git add .
git commit -m "Fix typo in brand-voice.md"
git push origin fix/brand-voice-typo
```

**For new content (campaigns, blog posts):**
```bash
git checkout -b feature/vbs-email-campaign
git add .
git commit -m "Add VBS email campaign sequence

- Create 5-email nurture series
- Add subject lines and preview text
- Include send schedule recommendations"
git push origin feature/vbs-email-campaign
```

**For strategy updates (goals, research):**
```bash
git checkout -b update/quarterly-goals-q3
git add .
git commit -m "Update Q3 goals and KPIs based on H1 performance

- Adjust enrollment targets based on actual data
- Update budget allocation
- Revise marketing tactics based on learnings"
git push origin update/quarterly-goals-q3
```

### 2. Commit Messages

Write clear, descriptive commit messages using this format:

```
[Type] Short description (under 60 characters)

Body explaining what changed and why:
- What was added or changed
- Why this change was made
- Any related files or context
- Results or expected outcomes

Co-Authored-By: Your Name <your.email@example.com>
```

**Commit Types:**
- `feat:` — New feature or content
- `fix:` — Bug fix or error correction
- `docs:` — Documentation updates
- `update:` — Strategic updates or revisions
- `archive:` — Moving content to archive
- `refactor:` — Reorganizing structure

**Example:**
```
feat: Add summer camp marketing campaign

- Create 2-week email sequence for camp promotion
- Write landing page copy
- Design social media ad templates
- Set up conversion tracking
- Expected to drive 20+ registrations

Co-Authored-By: Clint Sanchez <clint@clintsanchez.com>
```

### 3. Create a Pull Request (for significant changes)

After pushing your branch, create a PR:

1. Go to https://github.com/clintsanchez/the-way-pdo-marketing
2. Click "Pull Requests" → "New Pull Request"
3. Select your branch
4. Write a description:
   ```
   ## What Changed
   - Added complete summer camp marketing campaign
   - Created email sequences, landing page copy, ads

   ## Why This Matters
   - Drives enrollment for seasonal program
   - Executes Q3 marketing strategy

   ## Files Changed
   - 06-Marketing/Campaigns/summer-camp-2026.md
   - 06-Marketing/Email Marketing/summer-camp-sequence.md
   - 06-Marketing/Advertising/facebook-ads-summer-camp.md

   ## Testing/Validation
   - Reviewed brand voice guide ✓
   - Checked against ICP and messaging ✓
   - Verified campaign dates align with calendar ✓
   ```

5. Request review if needed
6. Merge once approved

---

## Content Guidelines

### File Organization

**Naming:**
- Use kebab-case: `summer-camp-email.md` not `Summer Camp Email.md`
- Be descriptive: `2026-06-vbs-email-sequence.md` not `email.md`
- Include dates: `2026-07-15-social-media-post.md`
- Keep under 60 characters

**Location:**
- Content → `06-Marketing/[subcategory]/`
- Brand assets → `04-Brand-Assets/[type]/`
- Research → `08-Research/[type]/`
- Design files → `09-Design-Files/[type]/`
- Analytics → `11-Analytics-and-Performance/`

### Writing Standards

**Follow our brand voice:**
- Read [01-Foundation/brand-voice.md](01-Foundation/brand-voice.md) first
- Write warm, professional, not corporate
- Lead with parent benefits
- Use specific, concrete examples
- Avoid jargon; use plain language

**Check your work:**
- [ ] Does it sound like us? (warm, professional, faith-centered)
- [ ] Is it clear and scannable?
- [ ] Does it include specific benefits, not generic claims?
- [ ] Would we say it in person?
- [ ] Is formatting clean and consistent?

**Link related files:**
- Use `[[01-Foundation/brand-voice.md]]` to cross-reference
- Link to relevant ICP, competitors, goals
- Help readers understand full context

---

## Before You Submit

### Checklist

- [ ] **Reviewed brand voice** — Writing sounds like us
- [ ] **Checked folder structure** — File in right location
- [ ] **Named file properly** — Descriptive, kebab-case, dated
- [ ] **Updated related docs** — Links, cross-references
- [ ] **Proofread carefully** — No typos or grammar errors
- [ ] **Followed formatting** — Markdown clean and consistent
- [ ] **Added context** — Why this matters, what it does
- [ ] **Tested links** — All internal references work
- [ ] **Considered audience** — Will people understand this?
- [ ] **Aligned with strategy** — Supports our goals?

### Quality Standards

**Documentation should:**
- Be clear and easy to understand
- Include concrete examples
- Link to related files
- Explain the WHY, not just WHAT
- Be scannable (short paragraphs, headers, bullets)
- Include templates/checklists where appropriate
- Note any dependencies or prerequisites

**Marketing content should:**
- Follow brand voice guidelines
- Target the right audience (check ICP)
- Include specific benefits (not generic claims)
- Include clear call-to-action
- Be mobile-friendly (short lines, scannable)
- Reference or link to brand strategy

**Data and analytics should:**
- Include date range
- Cite data sources
- Show methodology
- Include conclusions/implications
- Recommend actions based on data
- Note any limitations or caveats

---

## Types of Contributions

### Adding a New Campaign

1. **Create campaign doc** in `06-Marketing/Campaigns/`:
   ```
   01-Foundation/profile.md (for company context)
   01-Foundation/icp.md (for audience)
   02-Competition/positioning.md (for differentiation)
   03-Goals/goals.md (for targets)
   ↓
   Create: 06-Marketing/Campaigns/campaign-name-date.md
   ↓
   Include: Email sequences, ad copy, landing page, tracking plan
   ```

2. **Document in calendar**:
   - Add to `06-Marketing/Content Calendar/`
   - Note dates, channels, target audience
   - Link to campaign document

3. **Set up tracking**:
   - Create tracking doc in `11-Analytics-and-Performance/`
   - Define success metrics
   - Note expected outcomes

### Updating Strategic Documents

When updating profile.md, ICP, goals, etc.:

1. **Note what changed** — Specific sections/reasons
2. **Update related docs** — If ICP changes, update messaging
3. **Review for consistency** — All docs should align
4. **Commit with context** — Explain why this matters
5. **Notify stakeholders** — If changes affect planning

### Organizing Brand Assets

1. **Audit what you have** — Logos, photos, design files
2. **Organize into folders** — Follow structure in `04-Brand-Assets/`
3. **Create inventory doc** — What exists, versions, usage
4. **Archive old versions** — Move to `12-Archive/`
5. **Document standards** — Usage guidelines

### Creating Analytics Reports

1. **Define metrics** — What are we measuring?
2. **Gather data** — From Google Analytics, email platform, ads, etc.
3. **Analyze trends** — What does it mean?
4. **Make recommendations** — What should we do differently?
5. **Store in `11-Analytics-and-Performance/`** — With date range in filename

---

## Common Issues & Solutions

### "I'm not sure where to put this file"

**Ask yourself:**
- Is it strategy? → `01-Foundation/`, `02-Competition/`, `03-Goals/`
- Is it marketing content? → `06-Marketing/[subcategory]/`
- Is it a brand asset? → `04-Brand-Assets/[type]/`
- Is it research? → `08-Research/`
- Is it analytics? → `11-Analytics-and-Performance/`
- Is it something else? → Check the README.md folder guide

### "What if I need to change something existing?"

Simply edit the file and commit with a clear message:
```bash
git add 01-Foundation/profile.md
git commit -m "Update profile.md with current enrollment numbers

Current data shows [numbers], updating from outdated [old numbers]"
```

### "Should I delete old content?"

**Never delete** — Move to `12-Archive/`:
```bash
# Move old campaign to archive
git mv 06-Marketing/Campaigns/old-campaign.md 12-Archive/old-campaign.md
git commit -m "Archive old campaign - no longer in use"
```

### "Can I reorganize the folder structure?"

**Only if necessary.** If you think something should be reorganized:
1. Create an issue or discussion first
2. Propose the change
3. Get consensus
4. Then implement systematically

---

## Questions?

- **About brand voice?** → See [01-Foundation/brand-voice.md](01-Foundation/brand-voice.md)
- **About where files go?** → Check [README.md](README.md) folder structure
- **About git workflow?** → See [SETUP.md](SETUP.md) section on Git Workflow
- **About specific campaign?** → Check [06-Marketing/](06-Marketing/) for examples
- **About anything else?** → Open an issue or ask in discussions

---

## Recognition

Contributors who help develop The Way PDO's marketing repository will be recognized in:
- `CONTRIBUTORS.md` file (when created)
- Commit history (GitHub shows your contributions)
- Project milestones and updates

---

Thank you for contributing! Together, we're building The Way PDO's marketing foundation. 🎉

**Last Updated:** 2026-07-15
