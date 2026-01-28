# Built By Studios (Core Site) — Landing Page Specification

## Document Overview
**Site**: BuiltByStudios.com
**Purpose**: Explain the venture studio model, build credibility, route visitors to appropriate verticals
**Last Updated**: January 28, 2026

---

## Strategic Goals

| Goal | Priority | Success Metric |
|------|----------|----------------|
| Educate visitors on the model | High | Time on page > 90s |
| Build trust and credibility | High | Scroll depth > 70% |
| Route to vertical sites | High | Click-through to verticals > 25% |
| Capture general idea submissions | Medium | PIIE start rate > 10% |
| Email capture for updates | Low | Newsletter signup > 5% |

---

## Target Audience

### Primary Personas
1. **The Curious Professional** — Has an idea, exploring whether this is legitimate
2. **The Vertical Explorer** — Looking for their industry-specific site
3. **The Researcher** — Investor, journalist, or partner evaluating the business

### Psychographic Profile
- Skeptical of "too good to be true" pitches
- Values transparency and clarity
- Wants to understand the process before committing
- May have been burned by idea-theft fears before

---

## Page Architecture

### Information Hierarchy
```
1. Hero (Above the Fold) ─────────────────── PRIMARY CONVERSION
2. Problem Statement ─────────────────────── EMPATHY/RELATABILITY
3. How It Works ──────────────────────────── EDUCATION
4. Vertical Selector ─────────────────────── NAVIGATION/ROUTING
5. What We Build ─────────────────────────── EXPECTATION SETTING
6. Social Proof & Activity ───────────────── CREDIBILITY/ACTIVITY
7. Trust & Credibility ───────────────────── OBJECTION HANDLING
8. FAQ ───────────────────────────────────── OBJECTION HANDLING
9. Final CTA ─────────────────────────────── CONVERSION RECOVERY
10. Footer ───────────────────────────────── LEGAL/SECONDARY NAV
```

---

## Section-by-Section Specification

### Section 1: Hero (Above the Fold)

**Viewport Coverage**: 100vh (full viewport height)
**Goal**: Immediate clarity + single dominant action

#### Content

| Element | Specification |
|---------|---------------|
| **Headline** | "Turn Your 'Someone Should Build This' Moment Into a Real App" |
| **Subheadline** | "You know exactly what tools your industry needs. Describe your idea in 15 minutes and walk away with a professional concept memo—yours to keep." |
| **Primary CTA** | "Get Your Free Concept Memo" → Links to PIIE or vertical selector |
| **Secondary CTA** | "Find Your Industry ↓" → Smooth scroll to vertical selector |
| **Trust Micro-copy** | "Free forever. Your memo is yours to keep—even if you never submit. No account required." |
| **Urgency Element** | "Currently reviewing ideas for 2 verticals. We select 3-5 ideas to build each quarter." |

#### Alternative Headlines (A/B Test)
- A: "Turn Your 'Someone Should Build This' Moment Into a Real App" (recommended)
- B: "You Know What Your Industry Needs Built. We'll Build It."
- C: "Submit Your Idea. Get a Concept Memo. Watch It Come to Life."
- D: "The App Your Industry Needs Doesn't Exist Yet. Let's Build It."

#### Visual Treatment
- **Background**: Subtle gradient or abstract pattern (avoid stock photos)
- **Hero Visual**: Split-screen animation or illustration showing:
  - Left: Raw idea (napkin sketch, text note, speech bubble)
  - Center: Processing animation (abstract AI visualization)
  - Right: Polished app interface mockup
- **Animation**: Subtle, looping, non-distracting (CSS/Lottie preferred)

#### Layout (Desktop)
```
┌─────────────────────────────────────────────────────────────────┐
│  [Logo]                    [Verticals ▼] [How It Works] [About] │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   Turn Your 'Someone Should                    ┌─────────────┐  │
│   Build This' Moment Into                      │             │  │
│   a Real App                                   │  [VISUAL]   │  │
│                                                │  Animation  │  │
│   You know exactly what tools your             │             │  │
│   industry needs. Describe your idea           └─────────────┘  │
│   in 15 minutes, get a professional                             │
│   concept memo instantly.                                       │
│                                                                 │
│   ┌────────────────────────────┐  Find Your Industry ↓          │
│   │  Get Your Free Concept Memo │                               │
│   └────────────────────────────┘                                │
│                                                                 │
│   Free forever. Your memo is yours to keep. No account required.│
│                                                                 │
│   ⚡ Currently reviewing ideas for 2 verticals                  │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

#### Layout (Mobile)
- Single column, stacked
- Visual moves above or below headline (test both)
- CTA button full-width, thumb-zone positioned
- Trust micro-copy directly below CTA

---

### Section 2: Problem Statement

**Goal**: Create empathy, show you understand their frustration

#### Content

| Element | Specification |
|---------|---------------|
| **Section Header** | "You Know Exactly What Tools Your Industry Needs" |
| **Pain Point 1** | "You've searched for apps that solve your specific problem—and they don't exist." |
| **Pain Point 2** | "Generic tools don't understand your workflow, your terminology, or your constraints." |
| **Pain Point 3** | "You have a dozen ideas that would help, but no way to build them yourself." |
| **Pain Point 4** | "Tech companies build for the masses. You need something built for you." |

#### Visual Treatment
- Simple icons accompanying each pain point
- Alternating layout (icon left/right) or vertical list
- Subtle background differentiation from hero
- Consider illustration: frustrated professional → hopeful professional

#### Design Notes
- Keep copy concise—no more than 2 sentences per pain point
- Use "you" language throughout
- Avoid jargon or technical terms

---

### Section 3: How It Works

**Goal**: Demystify the process, reduce uncertainty

#### Content

| Step | Title | Description | Icon Suggestion |
|------|-------|-------------|-----------------|
| 1 | "Have a Conversation" | "Spend 10-15 minutes chatting with our AI. It asks smart questions to understand your idea fully—like explaining to a colleague who really listens." | Chat bubble / Microphone |
| 2 | "Get Your Concept Memo" | "Receive a professional document summarizing your idea—problem, solution, target users, and feasibility. It's yours to keep, regardless of what happens next." | Document / Download |
| 3 | "Honest Evaluation" | "If you choose to submit, our AI vetting engine evaluates viability, technical feasibility, and market potential. We're straightforward about what can realistically be built—no runaround." | Checklist / Scale |
| 4 | "Watch It Get Built" | "The best ideas get developed into real apps for your industry's marketplace. You get early access and revenue share." | Rocket / App icon |

#### Visual Treatment
- Horizontal timeline on desktop, vertical on mobile
- Connected steps (line or arrow between)
- Numbers or icons for each step
- Consider adding "~15 min" badge on Step 1

#### CTA Placement
- After Step 4: Medium-prominence CTA "Get Your Free Concept Memo →"
- Include time indicator: "Takes about 15 minutes"

---

### Section 4: Vertical Selector

**Goal**: Route users to their industry-specific experience

#### Content

**Section Header**: "Choose Your Industry"
**Section Subhead**: "Each vertical has its own specialized AI trained on industry-specific problems."

| Card | Title | Tagline | CTA | Status |
|------|-------|---------|-----|--------|
| A | "Built By School Leaders" | "Apps built by educators, for educators. Solve the problems that EdTech ignores." | "Explore →" | Active |
| B | "Built By Trade Schools" | "Tools designed by those who know the work. Practical apps for vocational education." | "Explore →" | Active |
| C | "Have a Different Idea?" | "Working in another industry? We're always exploring new verticals." | "Tell Us →" | Links to general PIIE |

#### Visual Treatment
- **Layout**: Bento grid style—two large cards, one smaller "other" card
- **Card Design**:
  - Subtle background image or illustration representing vertical
  - Clear typography hierarchy
  - Hover state with slight lift/shadow
- **Coming Soon Cards** (future): Grayed out with "Coming Soon" badge

#### Layout (Desktop)
```
┌─────────────────────────────────────────────────────────────────┐
│                    Choose Your Industry                         │
│     Each vertical has its own specialized AI trained on         │
│              industry-specific problems.                        │
│                                                                 │
│  ┌─────────────────────────┐  ┌─────────────────────────┐       │
│  │                         │  │                         │       │
│  │    SCHOOL LEADERS       │  │    TRADE SCHOOLS        │       │
│  │                         │  │                         │       │
│  │  Apps built by          │  │  Tools designed by      │       │
│  │  educators, for         │  │  those who know         │       │
│  │  educators.             │  │  the work.              │       │
│  │                         │  │                         │       │
│  │      [Explore →]        │  │      [Explore →]        │       │
│  └─────────────────────────┘  └─────────────────────────┘       │
│                                                                 │
│  ┌───────────────────────────────────────────────────────┐      │
│  │  Have a different idea? Tell us about it. [Tell Us →] │      │
│  └───────────────────────────────────────────────────────┘      │
└─────────────────────────────────────────────────────────────────┘
```

---

### Section 5: What We Build

**Goal**: Set expectations about the types of products

#### Content

**Section Header**: "Small Tools That Solve Big Problems"
**Section Subhead**: "We specialize in focused micro-SaaS applications—not bloated platforms."

| Category | Outcome-Focused Description |
|----------|------------------------------|
| Admin Dashboards | "See what matters at a glance—stop digging through spreadsheets" |
| Data Translators | "Stop copying the same data into three different systems by hand" |
| Workflow Automators | "Turn your 10-step process into a single click" |
| Tracking & Reporting | "Know what's happening without chasing down updates manually" |
| Simple Generators | "Create in 30 seconds what used to take 30 minutes" |

#### Visual Treatment
- Grid or icon list layout
- Each category with simple icon
- Keep descriptions to one line
- Consider showing 1-2 app mockup screenshots if available

#### Key Messaging
- Emphasize: Small, Focused, Self-serve, Low-maintenance
- Avoid: Platform, Suite, Enterprise, Comprehensive

---

### Section 6: Social Proof & Activity

**Goal**: Show this is real and active, build credibility through evidence

#### Content

**Section Header**: "Join Professionals Already Sharing Ideas"

| Element | Specification |
|---------|---------------|
| **Live Counter** | "X ideas submitted this month" (dynamic, or updated weekly) |
| **Vertical Badges** | "Education: X ideas in review" / "Trade Schools: X ideas in review" |
| **Founder Statement** | Photo + brief bio + quote about mission |

#### Founder Credibility Block
```
┌─────────────────────────────────────────────────────────────────┐
│  [Founder Photo]   "We built this because we kept meeting       │
│                    professionals who knew exactly what tools    │
│  Dylan Davis       their industry needed—but had no way to      │
│  Founder           build them. Now they do."                    │
│                                                                 │
│  Previously: [Relevant experience/companies]                    │
└─────────────────────────────────────────────────────────────────┘
```

#### Visual Treatment
- Activity counter should feel live/dynamic
- Founder photo should be professional but approachable
- Consider integration logos if applicable (tools you work with)

---

### Section 7: Trust & Credibility

**Goal**: Address fears about idea theft, legitimacy

#### Content

**Section Header**: "Why Trust Built By Studios?"

| Trust Point | Explanation |
|-------------|-------------|
| "Your ideas stay yours" | "Download your concept memo before submitting anything. We don't review ideas unless you explicitly ask us to." |
| "Transparent process" | "Our AI vetting criteria are based on proven venture studio frameworks. We're honest about what's buildable." |
| "Aligned incentives" | "We make money only when your idea succeeds. Free to submit—we invest in building." |
| "Built by builders" | "Our team has shipped 50+ software products across SaaS, mobile apps, and internal tools—and automated hundreds of business processes for companies of all sizes." |
| "Your data is protected" | "We never share your idea publicly without explicit permission. Your submission is confidential and handled according to our privacy policy." |

#### Visual Treatment
- Clean list or card layout
- Checkmark or shield icons for each point
- Link "transparent process" to FAQ or separate page

---

### Section 8: FAQ

**Goal**: Handle remaining objections

#### Content

| Question | Answer |
|----------|--------|
| "What happens to my idea?" | "You receive a concept memo immediately—it's yours regardless. We only review ideas you explicitly submit. Your submission is confidential and never shared publicly." |
| "Does it cost anything?" | "Free to submit. We invest our resources in building the products. You get early access and revenue share if your idea is selected." |
| "What makes an idea 'good enough'?" | "We look for ideas that solve real daily pain, can be built as focused tools (not platforms), require low ongoing support, and have clear willingness to pay." |
| "How long does the evaluation take?" | "You'll receive your concept memo immediately. If you submit for review, evaluation typically takes 5-7 business days." |
| "What if my idea gets selected?" | "We'll reach out to discuss terms. You get early access to the product, input on development, and revenue share from marketplace sales." |
| "I'm not technical—is that okay?" | "Perfect. We want your expertise, not your coding skills. The AI interview is conversational—just talk about the problem you want solved." |

#### Visual Treatment
- Accordion/collapsible format
- Show 3-4 questions expanded by default
- "Still have questions? Contact us" link at bottom

---

### Section 9: Final CTA

**Goal**: Capture visitors who scrolled the entire page

#### Content

| Element | Specification |
|---------|---------------|
| **Header** | "Ready to Turn Your Idea Into Reality?" |
| **Subhead** | "15 minutes. One conversation. Walk away with a professional concept memo—whether we build it or not." |
| **Primary CTA** | "Get Your Free Concept Memo →" |
| **Urgency Line** | "We're actively building for Education and Trade Schools. We select 3-5 ideas per quarter." |
| **Alternative** | "Not ready yet? Get notified when we launch new verticals." + Email capture |

#### Visual Treatment
- High contrast background (darker or accent color)
- Centered layout
- Large CTA button (minimum 200px wide)
- Urgency line in smaller text, subtle highlight
- Email capture is secondary (smaller, below primary CTA)

---

### Section 10: Footer

#### Content
- Logo
- Navigation: Home, School Leaders, Trade Schools, How It Works, About, Contact
- Legal: Privacy Policy, Terms of Service
- Social links (if applicable)
- Copyright: "© 2026 Gradient Labs AI, LLC. All rights reserved."

#### Visual Treatment
- Minimal, clean
- Dark background acceptable
- Emphasize Privacy Policy link (trust signal)

---

## Design System

### Color Palette

| Role | Color | Hex | Usage |
|------|-------|-----|-------|
| Primary | Deep Blue | #1E3A5F | Headers, trust elements |
| Secondary | Slate | #475569 | Body text |
| Accent | Coral/Orange | #F97316 | CTAs, highlights |
| Background | Off-white | #FAFAFA | Page background |
| Surface | White | #FFFFFF | Cards, sections |
| Muted | Light Gray | #E5E7EB | Borders, dividers |

### Typography

| Element | Font | Size (Desktop) | Size (Mobile) | Weight |
|---------|------|----------------|---------------|--------|
| H1 (Hero) | Inter | 56px | 36px | 700 |
| H2 (Section) | Inter | 40px | 28px | 600 |
| H3 (Subsection) | Inter | 24px | 20px | 600 |
| Body | Inter | 18px | 16px | 400 |
| Small/Caption | Inter | 14px | 14px | 400 |
| CTA Button | Inter | 18px | 16px | 600 |

### Spacing

| Element | Desktop | Mobile |
|---------|---------|--------|
| Section padding | 120px top/bottom | 80px top/bottom |
| Content max-width | 1200px | 100% - 32px |
| Card gap | 24px | 16px |
| Element spacing | 16px-32px | 12px-24px |

### Components

#### Primary Button
- Background: Accent color (#F97316)
- Text: White
- Padding: 16px 32px
- Border-radius: 8px
- Hover: Darken 10%
- Min-width: 200px (desktop), full-width (mobile)
- Min-height: 48px (touch target)

#### Secondary Button
- Background: Transparent
- Border: 2px solid Primary
- Text: Primary color
- Same sizing as primary

#### Cards
- Background: White
- Border-radius: 12px
- Shadow: 0 4px 6px rgba(0,0,0,0.05)
- Hover: Shadow increases, subtle lift
- Padding: 32px

---

## Technical Requirements

### Performance
| Metric | Target |
|--------|--------|
| First Contentful Paint | < 1.5s |
| Largest Contentful Paint | < 2.5s |
| Time to Interactive | < 3.5s |
| Cumulative Layout Shift | < 0.1 |
| Total page size | < 2MB |

### Responsive Breakpoints
| Breakpoint | Width | Layout |
|------------|-------|--------|
| Mobile | < 640px | Single column |
| Tablet | 640px - 1024px | Hybrid |
| Desktop | > 1024px | Full layout |

### Browser Support
- Chrome (last 2 versions)
- Firefox (last 2 versions)
- Safari (last 2 versions)
- Edge (last 2 versions)
- iOS Safari
- Chrome for Android

### Accessibility (WCAG 2.1 AA)
- All images have alt text
- Color contrast ratio minimum 4.5:1
- Keyboard navigable
- Focus states visible
- Form labels associated
- Skip navigation link
- Semantic HTML structure

---

## Analytics & Tracking

### Events to Track
| Event | Trigger | Purpose |
|-------|---------|---------|
| `page_view` | Page load | Traffic |
| `scroll_depth` | 25%, 50%, 75%, 100% | Engagement |
| `cta_click_hero` | Hero CTA click | Primary conversion |
| `cta_click_process` | Process section CTA | Secondary conversion |
| `cta_click_final` | Final CTA click | Recovery conversion |
| `vertical_click` | Vertical card click | Routing |
| `faq_expand` | FAQ item click | Interest areas |
| `email_capture` | Newsletter signup | Lead gen |
| `time_on_page` | 30s, 60s, 120s | Engagement |

### Heatmap Tracking
- Enable scroll heatmaps
- Click heatmaps on all CTAs
- Attention tracking on hero section

---

## Email Capture & Conversion Flow

### Value-First, Gate-Second Pattern

The PIIE conversation should deliver value BEFORE asking for email. This leverages sunk-cost psychology.

#### Recommended Flow
```
1. User clicks "Get Your Free Concept Memo"
2. PIIE modal/overlay opens immediately (no login required)
3. AI begins conversation: "Let's capture your idea..."
4. 10-15 minute conversation completes
5. AI generates concept memo preview
6. User sees memo preview on screen
7. GATE: "Enter your email to download your Concept Memo"
   └── Email field + "Send My Memo" button
   └── Checkbox: "Also submit for review" (optional, unchecked by default)
8. Email captured → Memo delivered → Thank you screen
9. Thank you screen: "Want us to evaluate this for building?" (if not already checked)
```

#### Why This Works
- User has invested 15 minutes—high motivation to get the result
- Email feels like a fair exchange, not a barrier
- Optional submission checkbox reduces friction
- Captures lead even if they don't submit for review

#### Abandonment Recovery
- If user closes during PIIE conversation: No recovery (too early)
- If user abandons after memo preview but before email: Exit-intent trigger
- Store partial conversation data (with consent) for follow-up

---

## Exit-Intent Strategy

### Exit-Intent Popup Specification

**Trigger**: Mouse moves toward browser close/back (desktop) or extended inactivity (mobile)

**Conditions**:
- Only show if user has scrolled > 25% of page
- Only show once per session
- Don't show if user has already started PIIE

#### Exit-Intent Content

| Element | Specification |
|---------|---------------|
| **Header** | "Before You Go—See What a Concept Memo Looks Like" |
| **Body** | "Download a sample concept memo to see exactly what you'd get. No email required." |
| **Primary CTA** | "Download Sample Memo" → Triggers PDF download |
| **Secondary CTA** | "I'm Ready to Share My Idea" → Opens PIIE |
| **Dismiss** | Small "X" or "No thanks" link |

#### Visual Treatment
- Clean modal, not aggressive
- Sample memo thumbnail preview
- Professional, not salesy

#### Alternative Exit-Intent (A/B Test)
- **Version A**: Sample memo download (above)
- **Version B**: Email capture for updates ("Get notified when we add your industry")

---

## A/B Test Roadmap

### Priority 1: Headlines
- Variant A: "Turn Your 'Someone Should Build This' Moment Into a Real App" (current)
- Variant B: "You Know What Your Industry Needs Built. We'll Build It."
- Variant C: "The App Your Industry Needs Doesn't Exist Yet. Let's Build It."
- Variant D: "Submit Your Idea. Get a Concept Memo. Watch It Come to Life."

### Priority 2: CTA Copy
- Variant A: "Get Your Free Concept Memo" (current/recommended)
- Variant B: "Start Your Free Idea Review"
- Variant C: "Describe Your Idea (15 min)"
- Variant D: "Share Your Idea"

### Priority 3: Hero Visual
- Variant A: Animation (idea → process → app)
- Variant B: Static illustration
- Variant C: No visual (text-focused)
- Variant D: Video testimonial/explainer (if available)

### Priority 4: Urgency Messaging
- Variant A: "Currently reviewing ideas for 2 verticals. Limited build slots each quarter."
- Variant B: "X ideas submitted this month" (social proof)
- Variant C: No urgency element
- Variant D: "Now accepting ideas for Education and Trade Schools"

### Priority 5: Exit-Intent Offer
- Variant A: Sample concept memo download
- Variant B: Email capture for vertical updates
- Variant C: No exit-intent

---

## Content Checklist

- [ ] Hero headline finalized
- [ ] Hero subheadline finalized
- [ ] All pain points written
- [ ] How It Works steps complete
- [ ] Vertical card copy complete
- [ ] What We Build categories finalized
- [ ] Trust section copy complete
- [ ] All FAQ Q&As written
- [ ] Final CTA copy finalized
- [ ] Legal pages linked (Privacy, Terms)
- [ ] All copy reviewed for jargon
- [ ] Mobile copy tested for length

---

## Launch Checklist

- [ ] All sections implemented
- [ ] Responsive design tested
- [ ] Page speed optimized (< 3s load)
- [ ] Analytics tracking verified
- [ ] Forms functional
- [ ] Links tested
- [ ] Accessibility audit passed
- [ ] Cross-browser testing complete
- [ ] Meta tags and OG images set
- [ ] 404 page created
- [ ] SSL certificate active
- [ ] DNS configured

---

## Copywriting Assessment Summary

**Assessment Date**: January 28, 2026
**Overall Grade**: B+

### Strengths
- **Clarity**: Headline uses universally relatable phrase ("someone should build this") that immediately resonates
- **Zero Risk**: Strong trust signals throughout—"Free forever," "No account required," "Download before submitting"
- **Voice Consistency**: Professional-but-accessible tone maintained throughout

### Key Improvements Made
1. **Subheadline**: Simplified from three promises to two clear sentences, reducing cognitive load
2. **Step 3 Title**: Changed "Expert Evaluation" to "Honest Evaluation" to match transparency theme
3. **What We Build Section**: Added outcome-focused descriptions (e.g., "Stop copying the same data into three different systems by hand") instead of generic category labels
4. **Urgency Specificity**: Changed "Limited build slots" to "We select 3-5 ideas to build each quarter"
5. **Trust Section**: Added explicit data protection statement and expanded proof of builder credentials
6. **So What Bridges**: Each category now answers "why should I care?" with concrete outcomes

### Areas for Post-Launch Optimization
- Add specific product examples when available ("Our team has shipped 50+ products" → name 2-3)
- Define AI evaluation framework more specifically
- Consider video content to demonstrate the PIIE process

---

*Specification prepared for Gradient Labs AI, LLC / Built By Studios*
*Version 1.1 — January 28, 2026*
