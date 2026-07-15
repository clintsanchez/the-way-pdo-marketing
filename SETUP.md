# The Way PDO Marketing Repository — Setup & Getting Started

Welcome! This repository is your centralized hub for The Way PDO's marketing strategy, branding, and operational documentation.

---

## Quick Start (5 minutes)

### 1. Understand the Structure
The repository is organized into 12 main folders:
- **00-Dashboard** — Quick reference and performance tracking
- **01-Foundation** — Brand guidelines, company profile, target audience
- **02-Competition** — Competitive analysis and market positioning
- **03-Goals** — Business objectives and success metrics
- **04-Brand-Assets** — Logos, colors, photography, design files
- **05-Website** — Website copy, structure, SEO strategy
- **06-Marketing** — Campaigns, email, social media, advertising
- **07-Forms-and-Documents** — Registration forms, policies, parent comms
- **08-Research** — Market research, customer insights
- **09-Design-Files** — Design projects (Adobe, Figma)
- **10-Video-and-Media** — Video scripts, renders, testimonials
- **11-Analytics-and-Performance** — Campaign tracking and ROI
- **12-Archive** — Old assets and deprecated campaigns

### 2. Read These First
- [README.md](README.md) — Full repository overview and usage guide
- [01-Foundation/profile.md](01-Foundation/profile.md) — Company profile
- [01-Foundation/brand-voice.md](01-Foundation/brand-voice.md) — How to write in our voice
- [01-Foundation/icp.md](01-Foundation/icp.md) — Who we're targeting

### 3. Start Adding Content
Pick one of these based on your role:
- **Marketing Lead** → Start with [06-Marketing/Content Calendar](06-Marketing/Content%20Calendar/)
- **Designer** → Organize [04-Brand-Assets](04-Brand-Assets/)
- **Social Manager** → Create content in [06-Marketing/Social Media](06-Marketing/Social%20Media/)
- **Analyst** → Set up tracking in [11-Analytics-and-Performance](11-Analytics-and-Performance/)

---

## First-Time Setup Checklist

### Week 1: Foundation
- [ ] Read README.md completely
- [ ] Review all files in 01-Foundation/
- [ ] Understand our target audience (01-Foundation/icp.md)
- [ ] Familiarize with brand voice guidelines (01-Foundation/brand-voice.md)
- [ ] Meet with leadership to fill in [TBD] sections in goals.md

### Week 2: Strategy
- [ ] Complete competitive research (02-Competition/competitors.md)
- [ ] Finalize business goals (03-Goals/goals.md)
- [ ] Determine budget allocation (03-Goals/goals.md)
- [ ] Establish KPIs and tracking (03-Goals/goals.md)

### Week 3: Organization
- [ ] Audit existing brand assets (migrate to 04-Brand-Assets/)
- [ ] Extract website copy (05-Website/website-copy.md)
- [ ] Organize all forms and documents (07-Forms-and-Documents/)
- [ ] Set up Analytics dashboard (11-Analytics-and-Performance/)

### Week 4: Launch
- [ ] Create content calendar (06-Marketing/Content Calendar/)
- [ ] Plan first month of campaigns (06-Marketing/Campaigns/)
- [ ] Develop email strategy (06-Marketing/Email Marketing/)
- [ ] Launch social media plan (06-Marketing/Social Media/)

---

## How to Use This Repository

### For Content Creation
1. Check [01-Foundation/brand-voice.md](01-Foundation/brand-voice.md) for tone/style
2. Review [01-Foundation/icp.md](01-Foundation/icp.md) for audience
3. Check [06-Marketing/Content Calendar](06-Marketing/Content%20Calendar/) for what's planned
4. Create content in appropriate folder
5. Link related documents for context

### For Marketing Campaigns
1. Review [03-Goals/goals.md](03-Goals/goals.md) for target audience & budget
2. Check [02-Competition/competitors.md](02-Competition/competitors.md) for positioning
3. Create campaign doc in [06-Marketing/Campaigns](06-Marketing/Campaigns/)
4. Document results in [11-Analytics-and-Performance](11-Analytics-and-Performance/)

### For Website Updates
1. Review [05-Website/website-copy.md](05-Website/website-copy.md)
2. Check [05-Website/seo-strategy.md](05-Website/seo-strategy.md) for keywords
3. Use [01-Foundation/brand-voice.md](01-Foundation/brand-voice.md) for tone
4. Update website section in 05-Website/
5. Track changes and results

### For Tracking Performance
1. Set up metrics in [11-Analytics-and-Performance](11-Analytics-and-Performance/)
2. Reference targets in [03-Goals/goals.md](03-Goals/goals.md)
3. Report monthly results
4. Adjust strategy based on data

---

## Document Naming Conventions

**All files follow these rules:**
- Use kebab-case (like-this, not like_this)
- Be descriptive: `2026-Q2-content-calendar.md` not `calendar.md`
- Include dates in YYYY-MM-DD format
- Use markdown (.md) for documentation
- Keep file names under 60 characters

**Example:**
```
✓ 2026-06-email-nurture-sequence.md
✓ facebook-ads-summer-camp.md
✓ vbs-campaign-2026.md

✗ email_sequence.md (use kebab-case)
✗ Campaign (too vague)
✗ 6-29-2026-stuff.md (use YYYY-MM-DD)
```

---

## Git Workflow

### Making Changes
1. **Create a branch** (if working on significant changes):
   ```bash
   git checkout -b feature/summer-camp-campaign
   ```

2. **Make your changes** — Edit files, add content

3. **Stage your changes**:
   ```bash
   git add .
   ```

4. **Commit with a clear message**:
   ```bash
   git commit -m "Add summer camp email sequence and landing page copy"
   ```

5. **Push to GitHub**:
   ```bash
   git push origin feature/summer-camp-campaign
   ```

6. **Create a Pull Request** (optional, for team review)

### Commit Message Format
Use clear, descriptive commit messages:

```
Add summer camp marketing campaign

- Create email sequence template
- Write landing page copy
- Add Facebook ad creative guidelines
- Include tracking plan

Co-Authored-By: Claude Haiku 4.5 <noreply@anthropic.com>
```

---

## Filling in [TBD] Sections

Throughout the repository, you'll see [TBD] placeholders. Here's what to do:

### [TBD] in profile.md
**Action:** Interview leadership about:
- Founding date and years in business
- Specific program details and pricing
- Unique selling points
- Current enrollment numbers

### [TBD] in icp.md
**Action:** Research and validate:
- Interview current parents
- Survey target audience
- Analyze website traffic
- Review inquiry sources

### [TBD] in competitors.md
**Action:** Conduct competitive research:
- Visit competitor websites
- Read their reviews
- Check social media presence
- Call and inquire about programs

### [TBD] in goals.md
**Action:** Gather business data:
- Current enrollment numbers
- Budget allocation
- Past performance metrics
- Leadership's strategic priorities

---

## Collaboration Tips

### For Team Members
- **Ask before deleting** — Someone else might need it
- **Update files when things change** — Keep everything current
- **Link related documents** — Use [[filename]] to cross-reference
- **Document your decisions** — Explain the WHY behind strategies
- **Archive, don't delete** — Move old campaigns to 12-Archive/

### For Leadership Review
- Monthly: Review KPIs and analytics
- Quarterly: Review goals progress
- Annually: Refresh strategy documents
- As needed: Update profile, ICP, brand voice if anything changes

---

## Key Documents to Review First

| Document | Time | What It Contains |
|----------|------|-----------------|
| [README.md](README.md) | 10 min | Overview and usage guide |
| [01-Foundation/profile.md](01-Foundation/profile.md) | 10 min | Company overview |
| [01-Foundation/brand-voice.md](01-Foundation/brand-voice.md) | 15 min | How to write like us |
| [01-Foundation/icp.md](01-Foundation/icp.md) | 10 min | Target audience details |
| [03-Goals/goals.md](03-Goals/goals.md) | 15 min | Our goals and targets |

**Total:** ~1 hour to get up to speed

---

## Frequently Asked Questions

**Q: Where do I find [asset type]?**  
A: Check [04-Brand-Assets](04-Brand-Assets/) for logos, colors, typography, photos. If you can't find it, check [12-Archive](12-Archive/) for older versions.

**Q: How should I write about the program?**  
A: Review [01-Foundation/brand-voice.md](01-Foundation/brand-voice.md) for tone and examples. All marketing should sound warm, professional, and faith-centered.

**Q: Who should we target with campaigns?**  
A: See [01-Foundation/icp.md](01-Foundation/icp.md) for detailed persona. Bottom line: Parents in Denham Springs area seeking faith-centered early education.

**Q: What are our goals?**  
A: See [03-Goals/goals.md](03-Goals/goals.md). Primary goal: Increase enrollment while building strong reputation.

**Q: How do I track campaign results?**  
A: Set up tracking in [11-Analytics-and-Performance](11-Analytics-and-Performance/). Reference KPIs in [03-Goals/goals.md](03-Goals/goals.md).

**Q: Should I update something I find outdated?**  
A: Yes! If you notice a document is outdated, update it and commit with a clear message explaining what changed.

**Q: Can I delete old campaigns?**  
A: Don't delete — move to [12-Archive](12-Archive/) instead. We might need to reference old campaigns for patterns and learnings.

---

## Next Steps

### Immediate (This Week)
1. ✅ Clone or pull this repository
2. ✅ Read README.md and foundation documents
3. ✅ Understand the folder structure
4. ✅ Set up your GitHub access if needed

### Short-term (This Month)
1. Fill in all [TBD] sections in foundation docs
2. Complete competitive research
3. Create first month of content
4. Set up analytics tracking
5. Launch initial campaigns

### Medium-term (This Quarter)
1. Build full quarterly content calendar
2. Execute seasonal campaigns (VBS, Summer Camp)
3. Grow email subscriber list
4. Increase website traffic
5. Track and optimize results

---

## Support & Questions

If you need help:
- **Documentation questions** → See README.md or relevant folder README
- **Brand/voice questions** → Review 01-Foundation/brand-voice.md
- **Strategy questions** → Check 03-Goals/goals.md and 02-Competition/competitors.md
- **Process questions** → This SETUP.md file

---

**Welcome to The Way PDO Marketing Hub!**

Let's build something amazing together. 🎉

---

**Repository:** https://github.com/clintsanchez/the-way-pdo-marketing  
**Last Updated:** 2026-07-15  
**Version:** 1.0
