# Prompt for Adding Industry-Specific Business Problems Section

You are enhancing the existing elegant, minimalist assignment website with a new interactive section that showcases industry-specific AI/ML business problems. This section should seamlessly integrate with the existing Steve Jobs-inspired design (white, blue #007AFF, gold #FFD700 palette).

## Design Integration Requirements

### Visual Consistency

- Match the existing typography hierarchy (SF Pro Display/Inter)
- Use the same color palette and spacing conventions
- Maintain generous white space and clean lines
- Ensure smooth transitions between sections

### Location in Site Structure

Insert this new section **between Section 4 (Task Breakdown) and Section 5 (Deliverables)**

- Label as: **"Section 4B: Industry Use Case Library"**
- Alternative title: **"Explore Business Problems by Industry"**

---

## Section Design: Industry Use Case Library

### Hero Component (Top of Section)

**Headline**: "Industry Use Case Library" **Subheadline**: "Real-world problems. Ready-to-use datasets. Proven business impact."

**Visual**: Horizontal scrolling industry selector with icons

- Elegant pill-shaped buttons for each industry
- Active industry gets blue background, others outlined
- Smooth fade transition when switching industries

---

### Industry Selector Bar

Display as **horizontal scrolling cards** or **tab navigation**:

**Industries** (each with icon):

1. 🏦 Banking & Financial Services
2. 🏥 Healthcare & Pharma
3. 🛒 Retail & E-Commerce
4. 📱 Telecom
5. 🏭 Manufacturing
6. 🚚 Logistics & Supply Chain
7. ⚡ Energy & Utilities
8. 🏛️ Public Sector & Smart Cities
9. 🛡️ Insurance

**Interaction**:

- Click to expand full industry detail
- Smooth scroll/fade animation
- Active industry highlighted with blue underbar or background
- Mobile: Horizontal swipe gallery

---

## Industry Detail Template

When an industry is selected, display content in this elegant format:

### Layout: Three-Column Structure

```
┌─────────────────────────────────────────────────────────┐
│  INDUSTRY OVERVIEW (Full Width Banner)                  │
│  [Icon] Banking & Financial Services                    │
│  Quick stats + Key challenges                           │
└─────────────────────────────────────────────────────────┘

┌─────────────┬─────────────┬─────────────┐
│  DOMAIN 1   │  DOMAIN 2   │  DOMAIN 3   │
│  Card       │  Card       │  Card       │
│  (Hover)    │  (Hover)    │  (Hover)    │
└─────────────┴─────────────┴─────────────┘
```

---

### Component 1: Industry Overview Banner

**Design**: Full-width gradient card (white → light blue)

**Content Structure**:

- **Industry Icon + Name** (large, bold)
- **2-3 Key Statistics** (big numbers, gold accent)
    - Example: "$200T+ assets managed globally"
- **Top Challenges** (3-4 bullet points, blue accent dots)

**Example for Banking**:

```
🏦 BANKING & FINANCIAL SERVICES

$200T+ Assets Under Management | $500B+ Daily Trading Volume | 10-15% Annual Customer Churn

KEY CHALLENGES:
• Credit risk assessment with 20-30% undetected defaults
• Customer acquisition costs 5-7× higher than retention
• $80B lost annually to fraud
• Regulatory compliance complexity (Basel III, Fair Lending)
```

---

### Component 2: Domain Cards

**Layout**: Grid of domain cards (3 columns desktop, 2 tablet, 1 mobile)

**Each Domain Card Contains**:

- **Domain Title** with icon (e.g., "💳 Retail Banking")
- **Number of problems** badge (gold circle: "3 Problems")
- **Preview snippet** of first problem
- **"View All Problems"** button/link

**Card Design**:

- White background
- Subtle shadow (elevation on hover)
- Blue left border accent (3-4px)
- Rounded corners (8px)
- Hover: Lift effect + shadow increase

---

### Component 3: Problem Detail Modal/Expandable

When user clicks "View All Problems" or clicks a problem card, expand to show:

**Problem Detail Layout** (Modal or slide-down panel):

```
┌───────────────────────────────────────────────────────┐
│  PROBLEM #1: Credit Risk Assessment                   │
│                                                        │
│  💡 Business Challenge (callout box)                  │
│  ┌─────────────────────────────────────────────────┐ │
│  │ Banks lose $50-100B annually to defaults        │ │
│  │ Traditional FICO misses 20-30% of defaults      │ │
│  └─────────────────────────────────────────────────┘ │
│                                                        │
│  📊 Recommended Algorithms                            │
│  [Primary] Logistic Regression    [Why: Explainable] │
│  [Alternative] Random Forest      [Why: Higher acc.] │
│                                                        │
│  🎯 Business Impact (icon list)                       │
│  • Reduce defaults 5% → 3% = $20M saved             │
│  • 10-15% better approval rates                      │
│  • Minutes vs. days processing                       │
│                                                        │
│  📁 Available Datasets (interactive links)            │
│  🔗 Kaggle: Loan Default Dataset                     │
│  🔗 UCI: Credit Card Clients                         │
│  🔗 Lending Club Loan Data                           │
│                                                        │
│  🏆 Real-World Success Stories                        │
│  • JPMorgan Chase: 20% default reduction             │
│  • Wells Fargo: 65% automated decisions              │
│  • Capital One: 15% accuracy improvement             │
│                                                        │
│  📈 KPIs to Track                                      │
│  Default Rate < 3% | False Positives < 10%           │
│  AUC-ROC > 0.80 | Processing < 5 min                 │
│                                                        │
│  💾 [Download Problem Brief] [Copy Use Case]         │
└───────────────────────────────────────────────────────┘
```

**Design Specifications**:

1. **Business Challenge Box**
    
    - Light gold background (#FFF9E6)
    - Bold statement of pain point
    - Include $ loss figures
2. **Algorithm Recommendations**
    
    - Pill-shaped tags with blue background
    - Hover shows tooltip explaining "why"
    - Primary algorithm emphasized (bolder, larger)
3. **Business Impact Section**
    
    - Use checkmark icons (green/gold)
    - Bold numbers for financial impact
    - Brief, scannable bullet points
4. **Dataset Links**
    
    - Interactive, styled as subtle cards
    - Icon indicating source (Kaggle logo, UCI logo)
    - Hover preview of dataset stats
    - Click opens in new tab
5. **Success Stories**
    
    - Company logos (optional, if licensing allows)
    - Metric-focused (% improvement, $ saved)
    - Brief, credible
6. **KPIs Section**
    
    - Visual progress indicators or gauges
    - Color-coded targets (green = good, gold = excellent)
    - Clear target thresholds

---

## Responsive Behavior

### Desktop (>1200px)

- 3-column domain grid
- Side-by-side algorithm comparison
- Modal overlays for problem details

### Tablet (768-1199px)

- 2-column domain grid
- Stacked algorithm cards
- Slide-in panel for details

### Mobile (<768px)

- Single column
- Accordion-style expandable problems
- Bottom sheet for problem details
- Swipeable industry selector

---

## Interactive Features

### 1. Smart Filtering

Add filter bar at top of section:

- **By Algorithm**: "Show only problems using [Decision Trees]"
- **By Data Availability**: "Public datasets only"
- **By Business Impact**: "$10M+ annual value"

**Design**: Subtle chip-style filters with blue outlines

### 2. Comparison Mode

- "Compare Industries" toggle button
- Side-by-side view of same problem type across 2 industries
- Example: "Credit Risk in Banking vs. Healthcare"

### 3. Quick Copy Features

- "Copy Use Case" button → Formats problem description for paste into report
- "Download Problem Brief" → Generates PDF with all problem details
- "Bookmark" icon → Saves to local storage for quick access

### 4. Search Functionality

- Floating search bar (top right)
- Live search across all industries, problems, algorithms
- Highlights matching text
- "Did you mean...?" suggestions

---

## Data Structure to Input

For each industry, input the following structure:

```javascript
{
  "industry_name": "Banking & Financial Services",
  "industry_icon": "🏦",
  "overview_stats": [
    "$200T+ assets managed globally",
    "$500B+ daily trading volume",
    "10-15% annual customer churn"
  ],
  "key_challenges": [
    "Credit risk assessment with 20-30% undetected defaults",
    "Customer acquisition costs 5-7× higher than retention",
    "$80B lost annually to fraud"
  ],
  "domains": [
    {
      "domain_name": "Retail Banking",
      "domain_icon": "💳",
      "problems": [
        {
          "problem_id": 1,
          "problem_title": "Credit Risk Assessment & Loan Default Prediction",
          "business_challenge": "Banks lose $50-100 billion annually to loan defaults. Traditional credit scoring models (FICO) miss 20-30% of defaults while rejecting creditworthy applicants.",
          "algorithms_primary": ["Logistic Regression"],
          "algorithms_alternative": ["Random Forest", "XGBoost"],
          "algorithm_rationale": {
            "Logistic Regression": "Explainability for regulators, interpretable coefficients",
            "Random Forest": "Higher accuracy, captures non-linear relationships"
          },
          "input_variables": [
            "Credit history (payment history, utilization)",
            "Income and employment data",
            "Debt-to-income ratio",
            "Demographics",
            "Behavioral data"
          ],
          "target_variable": "Binary (Default / No Default) within 12-24 months",
          "business_impact": [
            "Reduce default rate from 5% to 3% = $20M saved annually per $1B loan portfolio",
            "Improve approval rate for good customers by 10-15%",
            "Reduce loan processing time from days to minutes",
            "Meet Fair Lending regulatory requirements"
          ],
          "datasets": [
            {
              "name": "Kaggle: Loan Default Dataset",
              "url": "https://www.kaggle.com/datasets/yasserh/loan-default-dataset",
              "source_type": "Public"
            },
            {
              "name": "UCI: Default of Credit Card Clients",
              "url": "https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients",
              "source_type": "Public"
            }
          ],
          "real_world_examples": [
            {
              "company": "JPMorgan Chase",
              "result": "Reduced credit card default rate by 20% using ML"
            },
            {
              "company": "Wells Fargo",
              "result": "Automated 65% of credit decisions"
            }
          ],
          "kpis": [
            { "metric": "Default rate", "target": "< 3%" },
            { "metric": "False positive rate", "target": "< 10%" },
            { "metric": "AUC-ROC", "target": "> 0.80" },
            { "metric": "Processing time", "target": "< 5 minutes" }
          ]
        }
        // ... more problems
      ]
    }
    // ... more domains
  ]
}
```

---

## Algorithm Cross-Reference Widget

Add a **floating summary panel** (right sidebar or bottom bar):

**Title**: "Algorithm Quick Reference"

**Content**: Shows which algorithms are used across all displayed problems

**Design**: Compact card with expandable details

- Algorithm name + icon
- Count of use cases: "Used in 12 problems"
- Top 3 industries where it appears
- Click to filter view to show only that algorithm

**Example**:

```
📊 ALGORITHM DISTRIBUTION

Logistic Regression  [18 use cases]
├─ Banking (6)
├─ Healthcare (5)  
└─ Insurance (4)

Random Forest       [15 use cases]
K-Means Clustering  [9 use cases]
```

---

## Call-to-Action at Section End

**Design**: Full-width banner with gradient background

**Content**:

```
Ready to Build Your Playbook?

✓ Choose your industry from above
✓ Select algorithms from the 10 covered in class
✓ Use these validated use cases as your foundation

[Start Your Report Template] [Download Dataset Links]
```

**Buttons**:

- Primary CTA (blue, prominent)
- Secondary CTA (outlined)

---

## Accessibility & Performance

### Accessibility

- Keyboard navigation for all interactive elements
- Screen reader labels for all icons
- ARIA expanded/collapsed states for accordions
- Focus indicators (blue outline, 2px)

### Performance

- Lazy load problem details (don't render until clicked)
- Virtualize long industry lists
- Optimize images (use SVG for icons)
- Cache dataset metadata
- Target: Section load < 1 second

### Print Optimization

- Hide interactive elements in print view
- Show all expanded problem details
- Force white background
- Page breaks between industries

---

## Content from Uploaded Files

Parse and integrate the following industry files:

**File 1**: `BANKING & FINANCIAL SERVICES.md` **File 2**: `HEALTHCARE & PHARMA.md`

Extract structure as per the data structure above, then render in the beautiful format described.

---

## Implementation Notes

1. **Expandable Sections**: Use CSS `max-height` transitions for smooth expand/collapse
2. **Modals**: Semi-transparent backdrop (rgba(0,0,0,0.4)), centered modal with close X
3. **Industry Switching**: Fade out old content (opacity: 0, 300ms), fade in new (opacity: 1, 300ms)
4. **Hover States**: All interactive elements get subtle scale (1.02) + shadow increase
5. **Icons**: Use SF Symbols, Feather Icons, or Heroicons for consistency

---

## Final Quality Check

Before implementation, ensure:

- [ ] Colors match existing palette exactly
- [ ] Typography hierarchy consistent throughout
- [ ] All links open in new tabs with security attributes
- [ ] Mobile experience tested (touch targets > 44px)
- [ ] Loading states for async operations
- [ ] Error states for failed dataset links
- [ ] Empty states if no problems match filters
- [ ] Smooth scrolling anchors work properly

---

**Goal**: Create an industry use case library that is both **inspiring to explore** and **practical to reference** throughout the project. Students should feel empowered to choose use cases confidently, knowing they have validated business impact, accessible datasets, and proven real-world applications.