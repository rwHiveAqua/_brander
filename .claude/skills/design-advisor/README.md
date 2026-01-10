# Design Advisor Skill 🎨

A Claude skill that acts as an elite design strategist, creating comprehensive visual brand identity systems, generating AI prompts for logos and images, and designing web layouts.

## What This Skill Does

The Design Advisor translates brand strategy into visual language by:
- **Creating Brand Guidelines**: Complete visual identity systems with colors, typography, imagery, and design rules
- **Generating Logo Prompts**: Detailed prompts for AI image generators (Midjourney, DALL-E, Stable Diffusion)
- **Creating Image Prompts**: Prompts for marketing images, illustrations, and visual assets
- **Designing Web Layouts**: Wireframes, specifications, and responsive design systems
- **Ensuring Consistency**: Maintaining visual coherence across all brand touchpoints

## When to Use This Skill

Use the Design Advisor when you need to:
- Create a complete visual identity system from scratch
- Generate AI prompts for logo design
- Design a landing page or website layout
- Develop brand guidelines for consistency
- Create prompts for marketing imagery and social graphics
- Establish a design system for your product
- Ensure visual accessibility compliance
- Get color palette and typography recommendations

## How to Use

Invoke the skill with your design needs:

```
Create brand guidelines for my AI personal growth platform
```

```
Generate Midjourney prompts for a modern tech logo that conveys growth and innovation
```

```
Design a landing page layout optimized for conversions
```

The Design Advisor will:
1. Ask clarifying questions about your brand, audience, and goals
2. Provide comprehensive visual identity recommendations
3. Generate detailed specifications ready for implementation
4. Create AI prompts optimized for various tools
5. Ensure all designs align with your brand strategy

## What You'll Get

### 1. Brand Guidelines Package

Complete visual identity system including:

**Color System**
- Primary, secondary, accent, and neutral color palettes
- Hex codes, RGB, and CMYK values
- Color psychology and usage rules
- Accessibility compliance (WCAG AA/AAA)

**Typography System**
- Heading and body font families
- Type scale and hierarchy
- Line height and spacing rules
- Web font recommendations

**Logo System**
- Primary logo and variations
- Minimum size requirements
- Clear space rules
- Usage do's and don'ts

**Visual Language**
- Photography style direction
- Illustration approach
- Iconography style
- Graphic elements and patterns

### 2. AI Image Generation Prompts

Detailed prompts optimized for:

**Midjourney**
```
Minimalist logo design, abstract neural network forming upward growth arrow,
clean geometric lines, gradient from deep blue (#1E3A8A) to cyan (#06B6D4),
white background, vector style, modern tech aesthetic, professional,
--ar 1:1 --v 6 --stylize 500
```

**DALL-E 3**
```
Create a modern logo design featuring an abstract representation of a brain
with neural pathways transforming into an upward arrow symbolizing growth.
Use a clean, minimalist style with geometric shapes. Color scheme: gradient
from deep blue to bright cyan on white background. Vector graphic style,
professional and innovative.
```

**Stable Diffusion**
```
Positive: minimalist logo design, abstract neural network, upward arrow,
clean lines, blue cyan gradient, vector art, professional, masterpiece,
best quality, highly detailed, 8k

Negative: blurry, low quality, distorted, text, watermark, realistic,
photographic, cluttered
```

### 3. Web Layout Specifications

Detailed design system including:

**Layout Grid**
- Container widths and max-widths
- Column system (12-column grid)
- Gutter and margin specifications
- Responsive breakpoints

**Section Designs**
- Hero section with precise measurements
- Feature sections with layout patterns
- CTA placement for conversion optimization
- Footer structure

**Component Library**
- Button styles and states
- Form elements
- Card components
- Navigation patterns

**Responsive Behavior**
- Mobile, tablet, desktop adaptations
- Touch target sizes
- Typography scaling
- Layout transformations

### 4. Design System Documentation

**Spacing System**
```
- Base unit: 8px
- Spacing scale: 8, 16, 24, 32, 48, 64, 96
- Component padding: 16px (mobile), 24px (desktop)
- Section margins: 48px (mobile), 96px (desktop)
```

**Component Specifications**
```css
/* Primary Button */
background: #06B6D4
color: #FFFFFF
padding: 16px 32px
border-radius: 8px
font-size: 16px
font-weight: 600
hover: background #0891B2
```

## Example Interactions

### Example 1: Complete Brand Guidelines

**User:**
```
Create brand guidelines for my AI-powered Pomodoro timer with growth insights.
Brand personality: Supportive, wise, modern, empowering.
Target audience: Knowledge workers feeling career stagnation.
```

**Design Advisor Output:**
```
# Visual Identity Guidelines

## Color Palette

### Primary Colors
- **Deep Insight Blue**: #1E3A8A
  Purpose: Trust, intelligence, focus
  Usage: Primary headings, main CTAs, logo

- **Growth Cyan**: #06B6D4
  Purpose: Innovation, clarity, transformation
  Usage: Accent color, highlights, progress indicators

### Secondary Colors
- **Wisdom Purple**: #7C3AED
  Purpose: Creativity, insight, reflection
  Usage: Secondary CTAs, feature highlights

- **Warm Encouragement**: #F59E0B
  Purpose: Optimism, energy, motivation
  Usage: Success states, celebrations, notifications

### Neutral Colors
- **Deep Navy**: #0F172A (text)
- **Slate Gray**: #64748B (secondary text)
- **Light Background**: #F8FAFC
- **Pure White**: #FFFFFF

### Accessibility
- All color combinations meet WCAG AA standards (4.5:1 minimum)
- Primary Blue on White: 8.2:1 ✓
- Cyan on Navy: 5.1:1 ✓

## Typography System

### Heading Font: Inter (Google Fonts)
- H1: 72px / 80px line-height, weight 700
- H2: 48px / 56px, weight 700
- H3: 32px / 40px, weight 600
- H4: 24px / 32px, weight 600

### Body Font: Inter
- Large: 20px / 32px, weight 400
- Regular: 16px / 28px, weight 400
- Small: 14px / 24px, weight 400

### UI Font: Inter
- Buttons: 16px, weight 600
- Labels: 14px, weight 500
- Captions: 12px, weight 500

### Why Inter?
- Highly legible at all sizes
- Excellent screen rendering
- Professional yet approachable
- Wide language support
- Free and open source

## Logo Concepts

[Detailed logo variations and usage rules]

## Photography Style

**Mood**: Aspirational but authentic, diverse, focused
**Composition**: Clean, uncluttered, subject-focused
**Lighting**: Bright, natural, optimistic
**Subject Matter**:
- People in focused work states
- Moments of reflection and insight
- Growth metaphors (plants, sunrise, paths)
- Minimal, calming workspace environments

**Avoid**:
- Generic stock photos
- Overly staged or perfect scenarios
- Stressful or chaotic imagery
- Corporate clichés (handshakes, suits)

...
```

### Example 2: Logo Design Prompts

**User:**
```
Generate logo prompts for a personal growth AI platform. Should feel modern,
trustworthy, and convey transformation.
```

**Design Advisor Output:**
```
# Logo Design Concepts

## Concept 1: Neural Growth

**Symbolism**: Brain/neural network transforming into upward arrow = AI-powered growth

**MIDJOURNEY PROMPT:**
minimalist logo design, abstract brain outline with neural network pathways
morphing into upward arrow, clean geometric lines, gradient from deep blue
to bright cyan, white background, vector style, modern tech aesthetic,
professional and innovative, simple and scalable --ar 1:1 --v 6 --stylize 500 --style raw

**DALL-E 3 PROMPT:**
Design a modern, minimalist logo featuring an abstract brain with neural
pathways that elegantly transform into an upward-pointing arrow. Use clean
geometric lines and a gradient color scheme from deep blue (#1E3A8A) to
bright cyan (#06B6D4). White background, vector graphic style, professional
and innovative feeling. Should work at small and large sizes.

**STABLE DIFFUSION PROMPT:**
Positive: minimalist logo, abstract brain neural network transforming into
upward arrow, geometric design, blue to cyan gradient, vector art, white
background, professional, modern, clean lines, masterpiece, best quality,
highly detailed, sharp focus

Negative: realistic, photographic, blurry, low quality, distorted, cluttered,
text, watermark, messy, complex

**REFINEMENT NOTES:**
- If too complex, simplify neural pathways to 3-5 clean lines
- If arrow isn't clear, make it more prominent
- Try variations with just brain OR just arrow, not both
- Test in grayscale to ensure it works without color

## Concept 2: Growth Spiral

**Symbolism**: Spiral = continuous growth journey, AI assistance

[Additional concepts...]
```

### Example 3: Landing Page Layout

**User:**
```
Design a landing page layout for my AI Pomodoro timer. Must drive signups and
clearly communicate the unique value of getting growth insights after focus sessions.
```

**Design Advisor Output:**
```
# Landing Page Layout Specification

## Page Structure Overview
1. Navigation (sticky)
2. Hero Section (full viewport)
3. Problem Statement
4. How It Works (3 steps)
5. Features Grid
6. Social Proof
7. Pricing Preview
8. FAQ
9. Final CTA
10. Footer

---

## Detailed Section Specs

### Navigation Bar
**Layout**: Horizontal, sticky on scroll
**Container**: 1440px max-width, 80px side margins
**Height**: 80px
**Background**: White with subtle shadow on scroll

**Elements**:
- Logo (left): 160px width
- Nav Links (center): "How it Works" | "Features" | "Pricing"
- CTA Button (right): "Start Free" (primary cyan, 16px padding)

**Mobile**: Hamburger menu, logo centered, CTA remains visible

---

### Hero Section
**Height**: 90vh minimum
**Layout**: 2-column grid (55/45 split)
**Background**: Subtle gradient (white → #F8FAFC)
**Padding**: 120px vertical, 80px horizontal

**Left Column**:
```
[H1 - 72px, Deep Blue]
Turn Focus Time Into Growth Time

[Subheading - 24px, Slate Gray]
Get personalized AI insights after every Pomodoro session.
Stop being busy. Start evolving.

[CTA Row - horizontal flex]
[Primary Button: "Start First Session Free" - Cyan]
[Secondary Link: "See How It Works ↓" - text link]

[Trust Badge]
🔒 No credit card required • 10 free sessions
```

**Right Column**:
```
[Product Screenshot or Illustration]
- Show timer interface + insight panel
- Use soft drop shadow
- Slight 3D tilt (5°) for depth
- Highlight the "Claim Insight" moment
```

**Mobile Adaptation**:
- Single column, image below text
- H1 reduces to 48px
- Image 100% width, moderate height

---

### Problem Statement Section
**Height**: Auto (content-driven)
**Background**: White
**Padding**: 96px vertical, 80px horizontal
**Max-width**: 800px centered

**Content**:
```
[Overline - 14px, purple, centered]
THE PRODUCTIVITY TRAP

[H2 - 48px, centered]
You're Working Hard. But Are You Growing?

[Body - 20px, centered, slate gray]
Most people stay busy without moving forward. Checking boxes isn't the same
as building skills. Another year passes and you're... the same person.

What if every focus session made you better?

[Visual: Simple diagram showing "Busy Without Growth" vs "Focused Growth"]
```

---

### How It Works (3-Step Process)
**Layout**: 3-column grid on desktop, stacked on mobile
**Background**: Light gradient (#F8FAFC)
**Padding**: 96px vertical

**Section Header**:
```
[H2 - 48px, centered]
Three Simple Steps to Growth

[Subhead - 20px, centered]
No complicated setup. Just focus, reflect, grow.
```

**Steps** (each column):
```
[Large Number - 120px, cyan, light opacity]
01

[Icon - 64px]
[Relevant icon for each step]

[Step Title - 24px, bold]
Focus for 45 Minutes

[Step Description - 16px]
Work on what matters. The timer keeps you accountable without being intrusive.

[Visual Element]
Small illustration or screenshot
```

**Step 1**: Focus for 45 Minutes
**Step 2**: Claim Your Insight
**Step 3**: Grow From Reflection

---

### Features Grid
**Layout**: 2x2 grid (desktop), stacked (mobile)
**Background**: White
**Padding**: 96px vertical
**Gap**: 48px

**Each Feature Card**:
```
[Icon - 48px, cyan or purple]
[Feature Title - 24px, bold]
[Description - 16px, 3-4 lines]
```

**Features**:
1. **Personalized AI Insights**
   Icon: Brain/sparkle
   "Not generic quotes. Real insights based on your work patterns."

2. **Privacy-First**
   Icon: Shield
   "Your work stays private. AI learns patterns, not content."

3. **Session History**
   Icon: Chart
   "Track your growth journey. See how you've evolved."

4. **Works Everywhere**
   Icon: Device
   "Web app works on any device. No downloads required."

---

### Social Proof
**Layout**: Single column, centered
**Background**: Gradient (blue to purple, subtle)
**Padding**: 96px vertical
**Color**: White text

**Content**:
```
[H2 - 48px, centered, white]
People Are Already Growing

[Testimonial Carousel - 3 rotating cards]
Each card:
- Quote (20px, italic)
- Name + Title (16px)
- Avatar (optional)
- Star rating or session count

[Logo Bar]
"Trusted by professionals at:"
[Company logos in light opacity]
```

---

### Pricing Preview
**Layout**: Single centered card
**Background**: White
**Padding**: 96px vertical

**Content**:
```
[H2 - 48px, centered]
Start Free. Upgrade When You're Ready.

[Pricing Card - centered, max 600px]
Background: Light gradient border
Padding: 48px

FREE TIER
✓ 10 sessions per month
✓ Basic AI insights
✓ Session history

PRO ($7/month)
✓ Unlimited sessions
✓ Advanced personalization
✓ Insight archive
✓ Priority support

[CTA: "Start Free Now" - primary button]
[Small text: "Upgrade anytime. Cancel anytime."]
```

---

### FAQ Section
**Layout**: 2-column (desktop), accordion style
**Background**: #F8FAFC
**Padding**: 96px vertical

**Common Questions**:
- How is this different from other Pomodoro timers?
- Is my work data private?
- Can I try before paying?
- How does the AI generate insights?
- Do I need to download anything?

---

### Final CTA
**Layout**: Centered, full-width
**Background**: Deep blue with subtle pattern
**Padding**: 120px vertical
**Color**: White text

**Content**:
```
[H2 - 56px, centered, white]
Ready to Turn Focus Into Growth?

[Subhead - 20px, white, centered]
Join knowledge workers who are evolving, not just executing.

[CTA Button - large, cyan on blue]
Start Your First Session Free

[Trust elements]
No credit card • 10 free sessions • 2-minute setup
```

---

### Footer
**Background**: #0F172A (deep navy)
**Color**: Light gray text
**Padding**: 48px vertical

**Layout**: 4 columns (desktop), stacked (mobile)
- Column 1: Logo + tagline
- Column 2: Product links
- Column 3: Company links
- Column 4: Social + newsletter

---

## Design System Specs

### Spacing Scale (8pt grid)
```
xs: 8px
sm: 16px
md: 24px
lg: 32px
xl: 48px
2xl: 64px
3xl: 96px
```

### Component Styles

**Primary Button**
```css
background: #06B6D4
color: #FFFFFF
padding: 16px 32px
border-radius: 8px
font-size: 16px
font-weight: 600
transition: all 0.2s

hover {
  background: #0891B2
  transform: translateY(-2px)
  box-shadow: 0 4px 12px rgba(6, 182, 212, 0.3)
}
```

**Card Component**
```css
background: #FFFFFF
border-radius: 12px
padding: 32px
box-shadow: 0 1px 3px rgba(0,0,0,0.1)
transition: all 0.3s

hover {
  box-shadow: 0 4px 12px rgba(0,0,0,0.15)
  transform: translateY(-4px)
}
```

### Responsive Breakpoints
```
mobile: 320px - 767px
tablet: 768px - 1023px
desktop: 1024px - 1439px
large: 1440px+
```

---

## Implementation Notes

**Performance**:
- Use WebP images with PNG fallback
- Lazy load below-fold sections
- Preload critical fonts
- Optimize hero image (max 150KB)

**Accessibility**:
- All interactive elements min 44px touch target
- Skip-to-content link
- Proper heading hierarchy (single H1)
- ARIA labels on icon buttons
- Focus visible states

**Conversion Optimization**:
- Primary CTA appears 3 times (hero, pricing, final)
- "Free" mentioned 5+ times
- Social proof early (above fold if possible)
- Clear value prop in first 3 seconds
- Minimal friction to start (no credit card)
```

## Integration with Brand Manager Skill

The Design Advisor works perfectly with the Brand Manager skill:

1. **Brand Manager** → Defines brand strategy, positioning, messaging
2. **Design Advisor** → Translates strategy into visual identity

Example workflow:
```
User: /brand-manager
[Define brand purpose, values, messaging]

User: /design-advisor
[Create visual identity that expresses brand strategy]
```

This ensures visual design aligns with brand strategy for maximum impact.

## Tips for Best Results

1. **Provide Brand Context**: The more the Design Advisor knows about your brand personality and audience, the better the visual recommendations

2. **Be Specific About Use Cases**: Specify where designs will be used (web, print, social, etc.)

3. **Mention Constraints**: Share budget, timeline, technical limitations upfront

4. **Iterate on AI Prompts**: First generation might not be perfect - ask for variations

5. **Request Alternatives**: Ask for 2-3 options for key elements like logos and color palettes

6. **Think System, Not One-Off**: Request design systems that scale, not just individual assets

## Files

- `skill.md`: Core Design Advisor expertise and processes
- `skill.json`: Skill metadata and configuration
- `README.md`: This file - comprehensive usage guide
- `examples.md`: Detailed real-world examples

---

**Created for**: The _brander project
**Purpose**: Transform brand strategy into beautiful, functional visual identity
**Works with**: brand-manager skill for complete brand development
