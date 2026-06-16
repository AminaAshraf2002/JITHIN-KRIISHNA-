---
name: Cinematic Avant-Garde
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#ccc3d9'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#958da2'
  outline-variant: '#4a4456'
  surface-tint: '#d1bcff'
  primary: '#d1bcff'
  on-primary: '#3d0090'
  primary-container: '#7b2fff'
  on-primary-container: '#ede1ff'
  inverse-primary: '#721ff6'
  secondary: '#d3fbff'
  on-secondary: '#00363a'
  secondary-container: '#00eefc'
  on-secondary-container: '#00686f'
  tertiary: '#ffb690'
  on-tertiary: '#542100'
  tertiary-container: '#aa4a00'
  on-tertiary-container: '#ffdfd1'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#eaddff'
  primary-fixed-dim: '#d1bcff'
  on-primary-fixed: '#24005b'
  on-primary-fixed-variant: '#5700c8'
  secondary-fixed: '#7df4ff'
  secondary-fixed-dim: '#00dbe9'
  on-secondary-fixed: '#002022'
  on-secondary-fixed-variant: '#004f54'
  tertiary-fixed: '#ffdbca'
  tertiary-fixed-dim: '#ffb690'
  on-tertiary-fixed: '#331100'
  on-tertiary-fixed-variant: '#783200'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-xl:
    fontFamily: spaceGrotesk
    fontSize: 120px
    fontWeight: '700'
    lineHeight: 110%
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: spaceGrotesk
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 115%
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: spaceGrotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 110%
  headline-md:
    fontFamily: spaceGrotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 120%
  body-lg:
    fontFamily: sora
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 160%
  body-md:
    fontFamily: sora
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 160%
  label-sm:
    fontFamily: sora
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 100%
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  stack-sm: 16px
  stack-md: 48px
  stack-lg: 96px
---

## Brand & Style

The design system is engineered for high-impact visual storytelling, catering to the intersection of motion graphics and static design. The aesthetic is "Cyber-Premium"—combining the technical precision of a video editor's suite with the sophisticated minimalism of a high-end design agency. 

The visual language leverages **Glassmorphism** and **High-Contrast** elements to create a sense of depth and immersion. Expect heavy use of negative space, allowing high-fidelity media to breathe, punctuated by sharp, neon-infused accents that guide user attention. The emotional response is one of awe, technical mastery, and forward-thinking creativity.

## Colors

The palette is anchored in a true-black background to maximize OLED contrast and ensure video content remains the focal point. 

- **Primary (Electric Violet):** Used for primary actions, active states, and high-energy highlights.
- **Secondary (Neon Cyan):** Used for technical details, secondary interactions, and data visualization.
- **Neutral:** A deep black foundation with subtle grey variations for tiered information hierarchy.

Gradients should be used sparingly, primarily as "background glows" (large, blurred radial circles) behind glass containers to provide a sense of atmospheric depth.

## Typography

The typography system relies on a "Technical-Humanist" pairing. **Space Grotesk** provides a geometric, futuristic edge for headlines, utilizing tight tracking and bold weights to command the page. 

**Sora** serves as the body typeface, chosen for its exceptional legibility at small sizes and its slightly wide character set, which maintains the premium feel of the design system. Large display headers should be treated as graphic elements, often using "Outline" variants or overlapping with imagery to create a sense of three-dimensional space.

## Layout & Spacing

The design system utilizes a **Fixed Grid** on desktop (12 columns) and a **Fluid Grid** on mobile (4 columns). The layout philosophy is "Cinematic Asymmetry"—breaking the grid intentionally with oversized media or floating glass elements to create a dynamic flow.

Spacing is generous to evoke a premium gallery feel. Section transitions should use significant vertical "Stack" spacing to allow the user to focus on one project or concept at a time. Gutters are kept tight to maintain a sense of structural tension.

## Elevation & Depth

Depth is not communicated through traditional shadows, but through **Tonal Layering and Backdrop Blurs**. 

- **Level 0 (Base):** Pure #0A0A0A.
- **Level 1 (Glass):** Semi-transparent surfaces (3-5% opacity) with a 20px backdrop blur and a 1px solid border (10% white) to define edges.
- **Glows:** Instead of drop shadows, "Electric Violet" or "Neon Cyan" radial gradients sit *behind* active elements, creating a neon under-glow effect.

When an element is hovered, the backdrop blur intensity increases, and the border opacity rises, making the element appear to "float" closer to the user.

## Shapes

The shape language is "Modern Geometric." While the core of the layout is built on a rigid grid, containers and interactive elements utilize **Rounded (0.5rem)** corners to soften the technical edge and provide a more polished, contemporary feel. 

Media containers (Video players/Image galleries) should always follow the standard `rounded-lg` (1rem) rule to differentiate content from structural UI.

## Components

### Buttons
- **Primary:** Solid Electric Violet with white text. No shadow; instead, use a 10px violet glow on hover.
- **Secondary:** Ghost style with a 1px Neon Cyan border and Sora Bold text. 
- **Interaction:** Smooth 300ms transitions for all states.

### Cards (Glass)
- Used for project previews. Features a 1px inner border for "light-catching" edges. 
- Typography inside cards uses Sora SemiBold for titles.
- Image content within cards should have a subtle zoom-in effect on hover.

### Inputs & Fields
- Darkest grey background (#141414) with a 1px border that turns Neon Cyan on focus.
- Labels use the `label-sm` style, positioned above the field.

### Video Controls
- Custom, minimalist UI. Thin progress bars in Electric Violet.
- Icons are stroke-based (1.5pt weight) to match the technical aesthetic.

### Chips/Tags
- Small, rounded-pill shapes with low-opacity Neon Cyan backgrounds and full-opacity Cyan text for categorization (e.g., "Motion Design," "3D," "Case Study").