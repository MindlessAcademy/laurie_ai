# CRM LEAD LIST - DATA REFINEMENT ACTION PLAN

**Last Updated:** October 16, 2025  
**Total Leads:** 1,456  
**Status:** Ready for refinement before CRM import

---

## 📊 CURRENT DATA QUALITY

### ✅ Strong Areas (90%+ Complete)
- **Contact Names:** 92.2% (1,342/1,456)
- **University Names:** 92.0% (1,339/1,456)
- **Job Titles:** 91.6% (1,334/1,456)
- **Probability & Target:** 100% (now populated with defaults)

### ⚠️ Needs Work
- **LinkedIn Profiles:** 58.4% (850/1,456)
- **Owner Assignment:** 33.8% assigned, 66.2% = TBC (964 leads)
- **Priority Classification:** 33.7% assigned, 66.3% = TBC (965 leads)
- **Email Addresses:** Critical gap - needs enrichment

---

## 🎯 IMMEDIATE ACTIONS (THIS WEEK)

### Priority 1: Lead Assignment & Triage
**Goal:** Assign all 964 "TBC" leads to owners

**Manual Actions in Spreadsheet:**

1. **Filter & Sort Strategy**
   - Filter by Owner = "TBC"
   - Sort by "University Name" to group by institution
   - Assign leads based on territory/existing relationships

2. **Quick Assignment Rules**
   ```
   Georgia's Territory: [Define universities]
   Laurie's Territory: [Define universities]
   Amanda's Territory: [Define universities]
   ```

3. **Track Progress**
   - Create a column: "Assigned Date"
   - Mark as you go to track completion

**Time Estimate:** 2-3 hours

---

### Priority 2: Priority Classification
**Goal:** Classify all 965 "TBC" priority leads

**Manual Actions in Spreadsheet:**

1. **Priority Criteria Matrix**
   ```
   HIGH: 
   - Existing relationship/previous contact
   - Decision-maker title (Dean, Director, Head)
   - Target university on strategic list
   
   MEDIUM:
   - Warm lead (LinkedIn connection)
   - Influential role
   - Good-fit university
   
   LOW:
   - Cold lead
   - Junior role
   - Lower priority institution
   
   NON-STARTER:
   - No longer at institution
   - Wrong contact type
   ```

2. **Batch Classification**
   - Filter by "Priority = TBC"
   - Sort by "Job Title" to batch similar roles
   - Use Find & Replace for quick updates

**Time Estimate:** 3-4 hours

---

### Priority 3: Probability & Target Revenue Assessment
**Goal:** Update 1,254 leads with 0% probability

**Manual Actions in Spreadsheet:**

1. **Probability Scale**
   ```
   0%   = Not yet assessed / Non-starter
   10%  = Very cold lead, long-term nurture
   25%  = Cold lead, needs qualification
   50%  = Warm lead, active conversation
   75%  = Hot lead, proposal stage
   90%  = Very hot, negotiating
   100% = Closed/Won
   ```

2. **Target Revenue Guidelines**
   ```
   £5,000   = Workshop/short program
   £10,000  = Multiple workshops/modules
   £25,000  = Full program partnership
   £50,000+ = Strategic partnership
   ```

3. **Quick Assessment Flow**
   - Start with High Priority leads
   - Cross-reference with "Last Contact" and "Notes"
   - Update Probability and Target together

**Time Estimate:** 4-5 hours

---

## 🔍 DATA ENRICHMENT (NEXT 2 WEEKS)

### Priority 4: Email Discovery
**Goal:** Reduce missing emails from 100% to <20%

**Tools & Methods:**

1. **LinkedIn Email Extraction**
   - Use: Hunter.io, RocketReach, or Lusha
   - For 850 leads with LinkedIn profiles
   - Cost: ~$50-200/month depending on tool
   - **Action:** Export LinkedIn URLs, bulk lookup

2. **University Website Pattern**
   - Most UK universities use: firstname.lastname@university.ac.uk
   - **Action:** Create formula to generate likely emails
   - Verify with email validation tool (NeverBounce, ZeroBounce)

3. **Manual Lookup (High Priority Only)**
   - Check university staff directories
   - Check LinkedIn "Contact Info"
   - Focus on High + Medium priority leads first

**Time Estimate:** 8-10 hours + tool costs

---

### Priority 5: Data Validation & Cleanup

**Manual Actions:**

1. **Duplicate Check (Weekly)**
   - Sort by "Contact Name"
   - Look for similar names (typos, formatting)
   - Merge records, keeping most complete

2. **University Name Standardization**
   - Create master list of official university names
   - Find & Replace variations
   - Example: "UoB" → "University of Birmingham"

3. **Job Title Cleanup**
   - Standardize titles across records
   - Group similar roles for segmentation

4. **Remove Invalid Records**
   - Filter where Contact Name is empty
   - Check if salvageable (has LinkedIn/email)
   - Delete or mark "Non-Starter" if unusable

**Time Estimate:** 2-3 hours

---

## 🚀 CRM PREPARATION (WEEKS 3-4)

### Priority 6: Add Critical CRM Fields

**Add These Columns to Spreadsheet:**

1. **Lead Source** (if not already tracked)
   - Values: LinkedIn, Conference, Referral, Website, etc.

2. **Lead Stage**
   ```
   - New/Uncontacted
   - Contacted
   - Qualified
   - Proposal
   - Negotiation
   - Closed-Won
   - Closed-Lost
   ```

3. **Industry/Segment**
   - Business School
   - Engineering
   - Social Sciences
   - Widening Participation
   - etc.

4. **Tags** (comma-separated for flexibility)
   - Dean, Director, Professor
   - Russell Group, Post-92
   - Previous Client, Warm Lead

**Time Estimate:** 1-2 hours to add + ongoing updates

---

### Priority 7: Pre-CRM Import Checklist

**Before uploading to CRM:**

- [ ] All Owner fields assigned (no TBC)
- [ ] All Priority fields classified (no TBC)
- [ ] All Status fields updated (no TBC)
- [ ] Email addresses enriched (at least High priority)
- [ ] Duplicate check completed
- [ ] University names standardized
- [ ] Contact names properly formatted (First Last)
- [ ] Remove empty/invalid rows
- [ ] Backup original file
- [ ] Test import with 10-20 sample records first

---

## 📋 ONGOING MAINTENANCE (WHILE USING SPREADSHEET)

### Daily/Weekly Tasks

**Update After Each Contact:**
1. Update "Last Contact" date
2. Update "Next Contact" date
3. Add notes in "Notes" field
4. Update "Status" if changed
5. Update "Probability" if conversation advanced

**Weekly Reviews:**
1. Sort by "Next Contact" date
2. Review overdue follow-ups
3. Update priorities based on engagement
4. Archive/mark as Non-Starter if no response after X attempts

**Monthly Clean-up:**
1. Remove duplicates
2. Update job titles/universities (people move!)
3. Archive closed leads
4. Generate report: conversion rates by owner/priority

---

## 🎯 SEGMENTATION STRATEGIES

### For Better Lead Management

**Segment 1: Hot List (Immediate Action)**
- Priority = High
- Probability > 50%
- Has email
- Last Contact < 30 days ago

**Segment 2: Warm Nurture**
- Priority = Medium/High
- Probability 25-50%
- Has LinkedIn
- Schedule regular touchpoints

**Segment 3: Cold Outreach**
- Priority = Medium
- Probability < 25%
- Owner assigned
- Plan campaign sequence

**Segment 4: Research Needed**
- Owner = TBC OR Priority = TBC
- Needs qualification before outreach

---

## 🔧 RECOMMENDED TOOLS

### For Email Enrichment
- **Hunter.io** - Email finder by domain/LinkedIn
- **RocketReach** - Contact info database
- **Lusha** - LinkedIn extension
- **NeverBounce** - Email validation

### For Data Quality
- **Google Sheets/Excel** - Current solution
- **OpenRefine** - Free data cleaning tool
- **Duplicate Cleaner** - Built-in or standalone

### CRM Options (When Ready)
**Budget-Friendly:**
- **HubSpot CRM** - Free tier, great for small teams
- **Pipedrive** - Visual sales pipeline
- **Zoho CRM** - Feature-rich, affordable

**Enterprise:**
- **Salesforce** - Full-featured, scalable
- **Microsoft Dynamics** - Good for Office 365 users

---

## 📊 SUCCESS METRICS

### Track These KPIs

**Data Quality:**
- % of leads with complete information
- % of duplicates removed
- % with valid email addresses

**Lead Management:**
- Leads per owner
- Average time to first contact
- Response rate by priority tier

**Pipeline Health:**
- Total pipeline value (sum of Target £ × Probability)
- Number of leads by stage
- Conversion rate by priority
- Average deal size

**Activity:**
- Contacts made per week
- Meetings booked
- Proposals sent

---

## 🚨 RED FLAGS TO WATCH

1. **Leads sitting in TBC too long** - Indicates bottleneck
2. **Low email enrichment rate** - Blocks outreach
3. **High "Non-Starter" classification** - Source quality issue
4. **Uneven owner distribution** - Workload imbalance
5. **Old "Last Contact" dates** - Leads going cold

---

## 💡 QUICK WINS

**Can Do Today (< 1 hour each):**

1. **Sort by University** - Assign owners by territory
2. **Filter High Priority** - Focus enrichment here first
3. **LinkedIn to Email** - Check profiles for contact info
4. **Standardize 10 university names** - Start pattern for rest
5. **Update 20 probabilities** - Based on recent contacts

**This Week (< 5 hours total):**

1. Assign all TBC owners
2. Classify 100 TBC priorities
3. Enrich emails for top 50 High priority leads
4. Add "Lead Stage" column
5. Clean up duplicate "Laurie" and "Amanda" entries

---

## 📅 RECOMMENDED TIMELINE

**Week 1: Foundation**
- Day 1-2: Owner assignment (all 964)
- Day 3-4: Priority classification (all 965)
- Day 5: Data validation & cleanup

**Week 2: Enrichment**
- Day 1-3: Email discovery (focus High priority)
- Day 4: LinkedIn profile updates
- Day 5: Probability & target assessment

**Week 3: Pre-CRM Prep**
- Day 1-2: Add new CRM fields
- Day 3: University standardization
- Day 4: Final duplicate check
- Day 5: Test data structure

**Week 4: CRM Migration**
- Day 1: Choose CRM platform
- Day 2: Map fields & set up
- Day 3: Test import with sample
- Day 4: Full import
- Day 5: Train team & launch

---

## ✅ SUCCESS CHECKLIST

### Before CRM Import
- [ ] 1,456 leads reviewed and validated
- [ ] All TBC fields resolved
- [ ] High priority leads fully enriched (email + LinkedIn)
- [ ] Duplicates removed
- [ ] University names standardized
- [ ] File backed up
- [ ] CRM platform selected
- [ ] Team trained on new system

### After CRM Import
- [ ] All records imported successfully
- [ ] Fields mapped correctly
- [ ] Test outreach from CRM
- [ ] Set up automation rules
- [ ] Create dashboards/reports
- [ ] Schedule weekly pipeline reviews

---

## 🆘 NEED HELP?

**If you get stuck:**

1. **Data Quality Issues** - Use pivot tables to identify patterns
2. **Email Enrichment** - Start with free tools (Hunter.io free tier)
3. **CRM Selection** - Start with HubSpot free tier to test
4. **Large-scale Updates** - Happy to create scripts to automate

**Want me to:**
- [ ] Create a lead scoring formula
- [ ] Build import template for specific CRM
- [ ] Generate segmentation reports
- [ ] Automate email pattern generation
- [ ] Create pipeline value calculator

---

**Document Status:** Living document - update as you progress!


