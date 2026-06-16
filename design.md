---
name: Precision & Logic
colors:
  surface: '#101417'
  surface-dim: '#101417'
  surface-bright: '#353a3e'
  surface-container-lowest: '#0a0f12'
  surface-container-low: '#181c20'
  surface-container: '#1c2024'
  surface-container-high: '#262a2e'
  surface-container-highest: '#313539'
  on-surface: '#dfe3e8'
  on-surface-variant: '#bec8d1'
  inverse-surface: '#dfe3e8'
  inverse-on-surface: '#2d3135'
  outline: '#88929b'
  outline-variant: '#3e4850'
  surface-tint: '#88ceff'
  primary: '#88ceff'
  on-primary: '#00344d'
  primary-container: '#149ddd'
  on-primary-container: '#003048'
  inverse-primary: '#006590'
  secondary: '#bfc7d4'
  on-secondary: '#29313b'
  secondary-container: '#3f4752'
  on-secondary-container: '#aeb6c3'
  tertiary: '#c7c6c7'
  on-tertiary: '#2f3031'
  tertiary-container: '#949495'
  on-tertiary-container: '#2c2d2e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c8e6ff'
  primary-fixed-dim: '#88ceff'
  on-primary-fixed: '#001e2f'
  on-primary-fixed-variant: '#004c6e'
  secondary-fixed: '#dbe3f1'
  secondary-fixed-dim: '#bfc7d4'
  on-secondary-fixed: '#141c26'
  on-secondary-fixed-variant: '#3f4752'
  tertiary-fixed: '#e3e2e3'
  tertiary-fixed-dim: '#c7c6c7'
  on-tertiary-fixed: '#1b1c1d'
  on-tertiary-fixed-variant: '#464748'
  background: '#101417'
  on-background: '#dfe3e8'
  surface-variant: '#313539'
  slate-gray: '#272829'
  deep-navy: '#040B14'
  vibrant-blue: '#149DDD'
  ice-white: '#FFFFFF'
typography:
  headline-xl:
    fontFamily: Raleway
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Raleway
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Raleway
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Raleway
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  code-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The design system is engineered for a Quality Assurance professional where precision, reliability, and technical clarity are paramount. The brand personality is "The Meticulous Architect"—someone who sees the underlying structure of complex systems and ensures every edge case is handled. 

The aesthetic is a blend of **Minimalism** and **Corporate Modernism**. It prioritizes extreme clarity and functional density without clutter. The UI should evoke a sense of "bug-free" serenity: organized, logical, and highly legible. We use generous whitespace not just for aesthetics, but as a functional tool to separate concerns and guide the eye through technical documentation, project case studies, and skill matrices. The visual language is intentional, avoiding decorative elements that do not serve a communicative purpose.

## Colors

The palette is anchored in a professional, "Obsidian" dark mode to reflect a technical, terminal-inspired environment often used by QA engineers. 

- **Primary:** A vibrant, high-energy blue (#149DDD) used for call-to-actions, status indicators, and highlighting key success metrics. It represents "Active/Passing" states.
- **Secondary/Neutral Deep:** The deep navy (#040B14) provides the foundational canvas, offering high contrast against text for maximum readability.
- **Surface Tones:** Slate gray (#272829) is used for container backgrounds and card surfaces to create depth.
- **Accents:** Ice white (#FFFFFF) and off-white (#F5F8FD) are reserved for primary body text and high-level headings to maintain a "crisp" feel.

## Typography

The typography strategy leverages **Raleway** for headlines to provide a touch of geometric elegance and distinction, while **Inter** is used for all functional body and label text due to its exceptional legibility in technical contexts.

- **Headlines:** Use tight letter-spacing on larger sizes to maintain a "locked-in" professional look.
- **Body:** Paragraphs utilize a slightly increased line height (1.5x) to ensure long case studies are easy to parse.
- **Labels:** Small caps or increased tracking should be applied to labels and category tags to differentiate them from prose.
- **Technical Content:** For bug reports or code snippets, Inter's neutral character suffices, but ensure consistent 13px sizing for a "data-grid" feel.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to maintain a controlled, professional presentation of information. A 12-column system is used for project galleries, while a focused 8-column layout is preferred for reading-heavy case studies.

The spacing rhythm is strictly based on an **8px linear scale**. All component padding, margins, and vertical rhythm must be multiples of 8. This mathematical consistency reflects the QA engineer's attention to detail. 

- **Mobile:** Single column with 16px margins; components stack vertically.
- **Desktop:** Generous 64px margins and 24px gutters to allow the content "breath" and emphasize the minimalist aesthetic.

## Elevation & Depth

To maintain a clean, tech-forward look, we avoid heavy drop shadows in favor of **Tonal Layers** and **Low-Contrast Outlines**.

- **Surface Levels:** The base layer is `#040B14`. Cards and secondary sections sit on `#272829`.
- **Borders:** Use 1px solid borders using a low-opacity version of the Primary color (e.g., `#149DDD` at 20% opacity) to define boundaries without adding visual weight.
- **Interaction Depth:** On hover, elements may use a subtle "glow" effect—a primary-tinted ambient shadow with a large 32px blur but very low (10%) opacity—simulating a screen's backlight.

## Shapes

The shape language is **Soft (0.25rem)**. We avoid fully sharp corners to keep the UI approachable, but we also avoid large "bubbly" radii which can feel too casual for a technical professional. 

- **Components:** Buttons and input fields use a consistent 4px (0.25rem) radius.
- **Cards:** Larger containers like project cards use `rounded-lg` (8px) to create a clear structural containment.
- **Status Pills:** Small status indicators (e.g., "Passed", "In Progress") may use a "Pill" shape to distinguish them from interactive buttons.

## Components

- **Buttons:** Primary buttons are solid vibrant blue (#149DDD) with white text. Secondary buttons use the low-contrast outline style.
- **Chips/Tags:** Used for tech stacks (e.g., "Selenium", "Cypress"). These should have a `#272829` background with primary blue text.
- **Cards:** Project cards feature a 1px border. They should include a "test result" style metadata row at the bottom (e.g., "Coverage: 98%").
- **Input Fields:** Dark background (#040B14) with a slate border. Focus state switches the border to primary blue with a subtle inner glow.
- **Lists:** Use custom icons for bullets (like checkmarks or terminal prompt symbols `>`) to reinforce the technical theme.
- **Status Indicators:** Crucial for a QA portfolio. Use small, circular dots: Green (Pass), Yellow (Warning), Blue (Info) to categorize testing outcomes within case studies.