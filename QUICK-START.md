# 🚀 odt-cdmm-result-dashboard Skill - Quick Start Guide

**Everything you need to install & use in 5 minutes**

---

## 📥 INSTALL (2 steps)

### Step 1: Download Skill File
```
File: odt-cdmm-result-dashboard.skill
From: ลิงก์ที่เพื่อน/team lead ส่งให้
```

### Step 2: Install in Claude
**Cowork Desktop App:**
1. Open Cowork
2. Settings → Skills → "+ Add Skill"
3. Choose `odt-cdmm-result-dashboard.skill`
4. Click "Install"
5. ✅ Done!

**Claude.ai / Claude Code:**
1. Upload skill folder
2. Tell Claude: "Install this skill"
3. ✅ Ready to use

---

## 💬 USE (Copy & Send)

### Step 1: Prepare Your Data
```
✓ Organization Name
✓ Team Name(s)
✓ Assessment URL (format: https://cdmm.odt.co.th/group-assessment/[ID]/report)
✓ Mode: A / B / C
```

**Where to get Assessment URL?**
1. Go: https://cdmm.odt.co.th/
2. Find your team's assessment
3. Click "Report"
4. Copy URL from browser

### Step 2: Copy Your Prompt

**Choose 1 of 3:**

#### OPTION A: Single Team
```
I want to analyze our team's CDMM maturity

Organization: ABC Corp
Mode: A
Team: Backend
Assessment URL: https://cdmm.odt.co.th/group-assessment/abc123/report
```

#### OPTION B: Multiple Teams (Comparison)
```
Create CDMM comparison dashboard

Organization: XYZ Bank
Mode: B
Dashboard Title: XYZ Bank CDMM 2026

Teams:
- Backend: https://cdmm.odt.co.th/group-assessment/back111/report
- Frontend: https://cdmm.odt.co.th/group-assessment/front222/report
- DevOps: https://cdmm.odt.co.th/group-assessment/dev333/report
```

#### OPTION C: Add Team to Existing
```
Add new team to dashboard

Organization: 7Solutions
Mode: C
Existing Dashboard: 7Solutions_CDMM_Dashboard.html
New Team: Infrastructure
Assessment URL: https://cdmm.odt.co.th/group-assessment/infra999/report
```

### Step 3: Send to Claude
1. Open Claude (Cowork / Claude.ai)
2. Paste your prompt
3. Send!
4. ✅ Claude creates dashboard

---

## 📊 WHAT YOU GET

**Output:** `[YourCompany]_CDMM_Dashboard.html`

**Open it in browser and see:**

**Mode A (Single Team):**
- Assessment Results table (6 dimensions)
- CDMM Level Analysis (6 cards, clickable)
- Priority Recommendations (P1-P3 action items)

**Mode B (Multiple Teams):**
- Everything from Mode A
- PLUS Executive Summary with:
  - 📊 CDMM Scores comparison chart
  - 📊 Critical Bottlenecks chart
  - 💡 Key Insights per team
  - 🎯 Organizational Strengths
  - 📅 12-Week Implementation Timeline
  - ⚠️ Risks & Mitigation
  - 📋 Executive Recommendation

**Mode C (Add Team):**
- Updated dashboard with new team tab

---

## ✨ FEATURES

✅ Interactive tabs (click to switch teams)
✅ Expandable cards (click for details)
✅ Scrollable tables
✅ Mobile responsive (phone/tablet/desktop)
✅ Standalone (offline-ready after download)
✅ Shareable (email/Teams/Slack)
✅ Printable (save as PDF)

---

## 🔥 QUICK EXAMPLES

### Example 1 (Easiest)
```
I want CDMM dashboard for our QA team

Organization: Tech Company
Mode: A
Team: QA
Assessment URL: https://cdmm.odt.co.th/group-assessment/qa123/report
```

### Example 2 (Compare Teams)
```
Create CDMM dashboard comparing 3 teams

Organization: StartUp Inc
Mode: B

Teams:
- Backend: https://cdmm.odt.co.th/group-assessment/back111/report
- Frontend: https://cdmm.odt.co.th/group-assessment/front222/report
- DevOps: https://cdmm.odt.co.th/group-assessment/dev333/report
```

---

## 🎯 MODE SELECTION GUIDE

| Need | Mode | Output | Teams |
|------|------|--------|-------|
| Quick analysis of 1 team | **A** | Single dashboard | 1 |
| Compare maturity across teams | **B** | Dashboard + Executive Summary | 2+ |
| Add team to existing dashboard | **C** | Updated dashboard | 1 new |

---

## ❓ COMMON QUESTIONS

**Q: Skill ไม่เห็น?**
A: Reinstall → Settings > Skills > "+ Add Skill" > Choose file

**Q: Assessment URL ที่ไหน?**
A: cdmm.odt.co.th → Find assessment → Click "Report" → Copy URL

**Q: ต้องเตรียมอะไร?**
A: Organization name, Team name(s), Assessment URL

**Q: Output ไฟล์ไหน?**
A: Claude จะให้ link download หรือ save ใน Downloads folder

**Q: Share ยังไง?**
A: Email HTML file เลย (standalone, no dependencies)

**Q: Course links ไม่ work?**
A: Check internet → training.odt.co.th ต้องเปิดอยู่

**Q: Dashboard update ยังไง?**
A: Run skill ใหม่เมื่อ assessment update

---

## 📋 CHECKLIST

**Before you start:**
- [ ] Skill installed ✅
- [ ] Assessment URL(s) ready ✅
- [ ] Organization name ✅
- [ ] Mode selected (A/B/C) ✅

**After Claude finishes:**
- [ ] Download HTML file ✅
- [ ] Open in browser ✅
- [ ] Review analysis ✅
- [ ] Share with team ✅

---

## 🚀 READY?

Just follow these 3 steps:

1. **Install** skill (see above ⬆️)
2. **Copy** one of the 3 prompts
3. **Send** to Claude
4. **Get** dashboard!

### Copy-Paste Template:
```
I want CDMM analysis for our team

Organization: [Your Company Name]
Mode: A
Team: [Team Name]
Assessment URL: https://cdmm.odt.co.th/group-assessment/[ID]/report
```

---

## 💡 TIPS

- ✅ Use clear team names (not "team 1", use "Backend")
- ✅ Double-check Assessment URL format
- ✅ Mode B gives most insights (if you have 2+ teams)
- ✅ Share dashboard as PDF for meetings
- ✅ Run skill again when assessment updates

---

**Questions? Check each section above or ask Claude!**

---

*Version 1.0 | odt-cdmm-result-dashboard Skill*
