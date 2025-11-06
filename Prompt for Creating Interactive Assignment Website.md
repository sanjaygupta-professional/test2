# Prompt for Creating Interactive Assignment Website

You are an expert web designer creating an elegant, minimalist educational website in the style of Steve Jobs' Apple presentations. Design a single-page interactive web application that transforms a complex assignment document into an intuitive, beautiful learning experience.

## Design Philosophy

- **Aesthetic**: Clean, spacious, primarily white background with strategic use of blue (#007AFF Apple blue) and gold (#FFD700) accents
- **Typography**: Use SF Pro Display or similar elegant sans-serif fonts; hierarchy through size and weight, not decoration
- **Layout**: Generous white space, clear visual hierarchy, smooth scrolling sections
- **Interaction**: Subtle animations, hover effects, progress indicators
- **Mobile-first**: Fully responsive, touch-friendly

## Content Structure

Transform the following assignment content into 8 distinct sections with smooth scroll navigation:

### Section 1: Hero/Overview

**Title**: "AI/ML Algorithm Playbook" **Subtitle**: "Final Group Assignment - Foundations of ML & AI" **Key Info Display**:

- Deadline: November 26, 2025, 11:59 PM IST
- Format: Group Project
- Deliverable: Industry-Specific Algorithm Playbook (10-15 pages)

**Design Notes**:

- Full viewport height
- Large, bold typography
- Floating deadline countdown timer (elegant, minimal)
- Soft gradient background (white to very light blue)

### Section 2: Purpose & Context

**Content**: "As senior leaders, your job is not to tune hyperparameters but to identify high-value business problems, match them to appropriate AI/ML algorithms, and evaluate risks, KPIs, and governance implications."

**Key Elements**:

- 10 Classical Algorithms covered (display as elegant grid/cards):
    - Linear Regression
    - Logistic Regression
    - Decision Trees
    - KNN
    - Apriori Algorithm
    - K-Means/K-Medians/K-Modes Clustering
    - Hierarchical Clustering
    - AdaBoost
    - Random Forests
    - ARIMA

**Design Notes**:

- Algorithm cards with subtle hover effects
- Icons or simple visualizations for each algorithm
- Blue accent color for interactive elements

### Section 3: Learning Objectives

**Display as**: 5 elegant cards with icons

1. 🎯 Map business problems to appropriate algorithms
2. 🧠 Explain why an algorithm fits (data type, problem type, interpretability)
3. 📊 Link models to concrete business KPIs
4. ✓ Describe evaluation metrics and validation strategies
5. ⚠️ Discuss risks, limitations, and governance

**Design Notes**:

- Grid layout (2-3 columns depending on screen size)
- Each card: icon, title, description
- Gold accent for icons

### Section 4: Task Breakdown

**Interactive 3-Step Process**:

**Step 1: Choose Your Industry**

- Display as clickable tiles/cards
- Industries: Banking, Insurance, Retail/e-Commerce, Healthcare, Telecom, Manufacturing, Logistics, Energy, Public Sector
- Visual: Industry icons with hover effects

**Step 2: Algorithm Assignment**

- "Each member picks ONE algorithm"
- Visual: Team member slots → Algorithm pairing diagram

**Step 3: Core Requirements** Display as expandable accordion or tabs:

1. Identify strong use case (real-world or realistic)
2. Explain business problem and data used
3. Justify algorithm selection
4. Define KPIs and evaluation approach
5. Discuss limitations

**Design Notes**:

- Progressive disclosure (expand/collapse)
- Visual flow diagram showing process
- Blue progress indicators

### Section 5: Deliverables

**Two-Column Layout**:

**Left: Group Report (10-15 pages)**

- Executive Summary (1 page)
- Industry & Data Landscape (1-2 pages)
- Algorithm Playbook (6-9 pages)
- Cross-Algorithm Comparison (1-2 pages)
- References & Appendices (8-10 sources + contribution matrix)

**Right: Individual Reflection (1-2 pages)**

- Algorithm owned
- Key learnings
- Application to own organization
- Reflections on evaluation and bias-variance

**Design Notes**:

- Visual document mockups
- Page count indicators
- Expandable details for each section

### Section 6: Team Collaboration

**Contribution Matrix Example** (Interactive Table):

|Task/Section|Primary Owner|Secondary Contributors|
|---|---|---|
|Industry & Data Landscape|A|B|
|Linear Regression|B|-|
|Logistic Regression|C|-|
|Decision Trees|D|-|

**Design Notes**:

- Clean, minimal table design
- Gold header row
- Hover effects on rows
- "Download Template" button

### Section 7: Assessment Criteria

**Visual Rubric** - Two parallel sections:

**Group Component (70%)** Display as 6 cards with point values:

- Quality & relevance of use cases (20 pts)
- Correct problem-to-algorithm mapping (10 pts)
- Evaluation & metrics treatment (10 pts)
- Bias-variance & validation (10 pts)
- Cross-algorithm insight (10 pts)
- Clarity & executive communication (10 pts)

**Individual Component (30%)**

- Quality of individual sections (15 pts)
- Individual reflection note (15 pts)

**Design Notes**:

- Progress bars showing point distribution
- Blue/gold color coding
- Circular progress indicators

### Section 8: Quality Standards

**Side-by-Side Comparison**:

**❌ Weak Example** | **✓ Strong Example** (Show the credit card default prediction examples from the document)

**Design Notes**:

- Two-column comparison
- Red (weak) vs Green/Gold (strong) color coding
- Collapsible full-text with highlights
- Key differences annotated

### Section 9: Submission Guidelines

**Checklist Format** with icons:

✓ Single submission per group (PDF only) ✓ Multiple files? Use shared drive + access link ✓ Submit 30 minutes before deadline ✓ No changes after submission ✓ Contact support for issues

**Deadline Reminder** (prominent):

- Date: November 26, 2025
- Time: 11:59 PM IST
- Countdown timer

**Design Notes**:

- Large checkboxes
- Warning callouts for critical items
- Support contact button

### Section 10: GenAI Policy

**Simple Icon-Based Guide**:

**Allowed ✓**

- Identify use cases
- Brainstorm & outline
- Discover sources

**Required ✓**

- Verify all facts independently
- Cite sources properly
- Write in your own words
- Understand every sentence

**Design Notes**:

- Icon grid (green checkmarks, blue requirements)
- Prominent warning about accountability

## Technical Requirements

### Navigation

- Fixed top navigation bar with section links
- Smooth scroll behavior
- Progress indicator showing current section
- "Back to top" button (appears on scroll)

### Interactions

- Fade-in animations on scroll (subtle, performant)
- Hover effects on all interactive elements
- Expandable/collapsible sections where appropriate
- Modal overlays for detailed content

### Responsive Design

- Mobile: Single column, stacked sections
- Tablet: Two-column hybrid
- Desktop: Full layout with sidebars

### Typography Hierarchy

- H1: 48-56px (Hero titles)
- H2: 36-42px (Section headers)
- H3: 24-28px (Subsections)
- Body: 16-18px (Readable, generous line-height)
- Caption: 14px (Metadata, labels)

### Color Palette

- Primary: #FFFFFF (white)
- Accent 1: #007AFF (Apple blue)
- Accent 2: #FFD700 (gold)
- Text: #1D1D1F (near black)
- Gray: #86868B (secondary text)
- Background: Linear gradient (white → #F5F5F7)

### Fonts

- Primary: SF Pro Display / Inter / -apple-system
- Monospace: SF Mono / Menlo (for code/data)

## Implementation Notes

Create a single HTML file with embedded CSS and JavaScript. Use:

- CSS Grid and Flexbox for layout
- CSS animations (transform, opacity)
- Vanilla JavaScript for interactions (no heavy frameworks)
- Intersection Observer API for scroll animations
- LocalStorage for saving user progress/notes (optional)

## Accessibility

- Semantic HTML
- ARIA labels where needed
- Keyboard navigation support
- Sufficient color contrast (WCAG AA)
- Alt text for all images/icons

## Final Output

A single, self-contained HTML file that is:

- Beautiful and inspiring
- Easy to navigate
- Information-dense yet uncluttered
- Print-friendly (optional print stylesheet)
- Fast-loading (<3 seconds)

**Goal**: Create an assignment guide that students actually WANT to read and reference throughout their project.