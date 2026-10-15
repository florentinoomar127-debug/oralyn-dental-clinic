---
name: Kinetic Logic
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#434655'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#515659'
  on-tertiary: '#ffffff'
  tertiary-container: '#696e71'
  on-tertiary-container: '#edf1f5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#dfe3e7'
  tertiary-fixed-dim: '#c3c7cb'
  on-tertiary-fixed: '#171c1f'
  on-tertiary-fixed-variant: '#43474b'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
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
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  section-padding: 120px
---

## Brand & Style

This design system embodies a **Corporate / Modern** aesthetic tailored for the high-stakes world of logistics and supply chain management. It prioritizes clarity, efficiency, and industrial precision. The visual narrative is built on the concept of "orchestrated movement"—where complex data and physical goods are transformed into streamlined, automated workflows.

The target audience consists of operations managers and logistics executives who value reliability and data-driven insights. To evoke trust, the UI utilizes generous whitespace, a structured grid, and high-fidelity 3D isometric illustrations that make abstract software concepts feel tangible and manageable. The emotional response is one of calm control amidst industrial complexity.

## Colors

The palette is anchored by a vibrant **Electric Blue** primary color, symbolizing technology and action. This is balanced against a sophisticated **Midnight Navy** for deep backgrounds and high-contrast text, ensuring an authoritative tone. 

- **Primary:** Used for call-to-actions, active states, and key navigational elements.
- **Secondary (Midnight):** Used for dark-themed section backgrounds and primary headings to provide visual weight.
- **Surface Tints:** A range of cool grays and off-whites are used to create subtle containment for cards and data modules.
- **Functional Colors:** Success (Green), Warning (Amber), and Error (Red) should be desaturated to maintain the professional, industrial palette.

## Typography

The typography system uses a tiered approach to balance modern tech aesthetics with readability. 

- **Manrope** serves as the primary headline face. Its geometric yet slightly condensed nature feels architectural and modern.
- **Inter** provides high legibility for body copy and long-form descriptions, essential for data-heavy logistics interfaces.
- **JetBrains Mono** is utilized for small eyebrow labels and technical metadata, nodding to the precision of automated systems and developer-grade reliability.

Headlines should use tight letter spacing to appear "locked-in" and sturdy. Body copy requires generous line height (1.5x - 1.6x) to maintain a clean, airy feel.

## Layout & Spacing

The system follows a **12-column fluid grid** for desktop, transitioning to a **4-column grid** for mobile. A strict 8px base unit governs all spatial relationships.

- **Vertical Rhythm:** Sections are separated by significant vertical padding (120px on desktop) to allow the 3D illustrations to "breathe" and prevent the interface from feeling cluttered.
- **Containment:** Content is housed in a max-width container of 1280px. 
- **Alignment:** Use asymmetrical layouts where text blocks are balanced by large isometric imagery. Text should generally be left-aligned for professional readability, though section headers may be centered for editorial emphasis.

## Elevation & Depth

Depth is conveyed through **Tonal Layering** and **Soft Ambient Shadows**. 

1. **Surface Tiers:** Use subtle background shifts (e.g., White to Light Gray #F8FAFC) to separate content blocks without using heavy lines.
2. **Shadows:** Elements like cards use an "Industrial Shadow"—highly diffused (20-40px blur), low opacity (4-8%), with a slight blue tint (#0F172A) to ground the elements on the page.
3. **Dark Mode Transitions:** When using dark sections, depth is achieved through "Inner Glows" (1px subtle border) rather than shadows, making components appear recessed or slightly raised from the midnight background.

## Shapes

The shape language is **Structured & Approachable**. 

- **Standard Radius:** 8px (0.5rem) is the default for buttons, input fields, and small cards. This provides a modern touch while maintaining a serious, professional edge.
- **Large Radius:** 16px (1rem) is reserved for primary feature cards and image containers to create a distinct "container" feel.
- **Interactive Elements:** Buttons and tags use the standard radius. Avoid pill-shapes for primary CTAs to maintain the "modular/industrial" theme; pill-shapes should be reserved exclusively for small status indicators or badges.

## Components

### Buttons
- **Primary:** Solid blue background, white text. No gradients. High-contrast hover state (slight darken).
- **Secondary:** Transparent background with a 1.5px blue or slate border. 
- **Tertiary/Ghost:** No border, blue text, used for low-priority navigation.

### Cards
- **Feature Cards:** White background, 1px subtle border (#E2E8F0), and an 8px corner radius. Feature cards should always lead with either a 3D icon or a specific "functional" icon in a tinted circular container.

### Input Fields
- **Design:** Outlined style with a 1px slate-200 border. Focus state utilizes a 2px blue ring with 4px offset to ensure accessibility and high visibility.

### Chips & Badges
- **Technical Badges:** Utilize the label-caps typography (JetBrains Mono). Use light gray backgrounds with dark slate text for a "label maker" aesthetic.

### 3D Illustrations
- **Style:** All illustrations must follow a consistent isometric projection. Lighting should be consistent (top-left source), and the color palette of the illustrations must strictly adhere to the brand blues and grays to ensure they feel like part of the UI rather than external stock assets.