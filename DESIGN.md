---
name: Nutricare Catering
description: Institutional catering presented with directness, calm and professional warmth.
colors:
  action-deep-green: "#143b2f"
  action-hover-green: "#245b47"
  supporting-green: "#2f7258"
  focus-gold: "#e9b949"
  charcoal: "#1c2622"
  muted-charcoal: "#43534c"
  mineral-green: "#edf3ef"
  deep-green: "#0d241c"
  canvas: "#fbfcfa"
  surface: "#ffffff"
  border: "#cbd8d0"
  dark-action-green: "#8fd0ad"
  dark-supporting-green: "#6bb78f"
  dark-focus-gold: "#f0c45e"
  dark-text: "#eff7f2"
  dark-muted: "#b7c9bf"
  dark-mineral: "#132d24"
  dark-canvas: "#0b1c16"
  dark-surface: "#11271f"
  dark-border: "#315144"
typography:
  display:
    fontFamily: "Archivo, sans-serif"
    fontSize: "clamp(3.2rem, 6.5vw, 5.8rem)"
    fontWeight: 700
    lineHeight: 0.98
    letterSpacing: "-0.035em"
  headline:
    fontFamily: "Archivo, sans-serif"
    fontSize: "clamp(2.4rem, 4.5vw, 4.5rem)"
    fontWeight: 700
    lineHeight: 1
    letterSpacing: "-0.035em"
  title:
    fontFamily: "Archivo, sans-serif"
    fontSize: "clamp(1.5rem, 2.5vw, 2.35rem)"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "-0.025em"
  body:
    fontFamily: "Archivo, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "-0.01em"
  label:
    fontFamily: "Archivo, sans-serif"
    fontSize: "0.94rem"
    fontWeight: 700
    lineHeight: 1.2
rounded:
  control: "10px"
  button: "12px"
  surface: "14px"
spacing:
  xs: "6px"
  sm: "14px"
  md: "24px"
  lg: "32px"
  xl: "48px"
components:
  button-primary:
    backgroundColor: "{colors.action-deep-green}"
    textColor: "{colors.surface}"
    typography: "{typography.label}"
    rounded: "{rounded.button}"
    padding: "14px 24px"
    height: "50px"
  button-primary-hover:
    backgroundColor: "{colors.action-hover-green}"
    textColor: "{colors.surface}"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.action-deep-green}"
    typography: "{typography.label}"
    rounded: "{rounded.button}"
    padding: "14px 24px"
    height: "50px"
  field:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.charcoal}"
    typography: "{typography.body}"
    rounded: "{rounded.control}"
    padding: "12px 14px"
    height: "48px"
---

# Design System: Nutricare Catering

## Overview

**Creative North Star: "Institutional Directness"**

Nutricare is a calm, decisive institutional world: white and mineral-green surfaces, deep-green actions, charcoal type and professional food photography at meaningful scale. Restrained rounding and generous spacing keep rigor approachable without turning proof into spectacle.

The system gives clinics and schools equal visual weight. It shares the finish level of established collective-catering brands such as Compass Group France and Restalliance without borrowing their identities.

**Key Characteristics:**
- Direct hierarchy and factual, neutral proof language.
- Archivo throughout, with compact oversized headings.
- Decisive food photography balanced by quiet surfaces.
- Deep-green actions, mineral-green sections and restrained gold focus cues.
- Equivalent prominence for clinical and educational audiences.

## Colors

The palette is predominantly mineral and neutral; green carries action and institutional confidence, while gold is reserved for focus and selection.

### Primary
- **Deep Action Green:** Primary calls to action, active controls and high-authority surfaces.
- **Supporting Green:** Links, icons, field focus and secondary emphasis.

### Secondary
- **Focus Gold:** Keyboard focus and selection contrast; never a decorative wash.

### Neutral
- **Charcoal:** Primary text on light surfaces.
- **Muted Charcoal:** Supporting copy and descriptive text.
- **Mineral Green:** Alternating section background and low-emphasis controls.
- **Canvas:** Main page background.
- **White Surface:** Cards, forms and the hero message panel.
- **Deep Green:** Footer and deepest brand surface.
- **Border:** Quiet separators and field outlines.

**The Green Carries Meaning Rule.** Deep green marks action, authority or audience context; it is not ambient decoration.

## Typography

**Display Font:** Archivo (sans-serif fallback)

**Body Font:** Archivo (sans-serif fallback)

**Character:** A single practical grotesk creates institutional clarity. Large, tightly tracked headings make the page decisive; regular-weight body copy remains neutral and readable.

### Hierarchy
- **Display:** Bold, compact and balanced; reserved for the hero promise with a maximum width of 12 characters.
- **Headline:** Bold section statements with tight leading and a maximum width of 18 characters.
- **Title:** Service and audience titles; compact without competing with section headlines.
- **Body:** Regular text with generous leading; explanatory lines stay near 58–68 characters.
- **Label:** Bold navigation, controls and form labels.

**The One-Family Rule.** Use Archivo for every interface and editorial role; hierarchy comes from scale, weight and spacing.

## Layout

Content sits in a fluid container capped at 1240px, with 20px side clearance on larger screens and 14px on small screens. Major sections use generous fluid vertical spacing. The hero pairs a larger message panel with a narrower clinic/school context panel; content sections use asymmetric two-column compositions and decisive imagery.

At 860px the hero, service grid and process steps collapse to one column and navigation becomes a full-width dropdown. At 620px the header and gutters tighten. Clinics and schools remain two equal audience tabs at every width.

**The Equal Audiences Rule.** Clinic and school entry points receive identical area, hierarchy and interaction weight.

## Elevation & Depth

Depth is selective. Major floating surfaces and decisive images use one substantial ambient shadow; service cards use a quieter green-tinted shadow. Lists and proof points stay flat and separate with borders.

### Shadow Vocabulary
- **Decisive Lift** (`0 18px 48px rgba(0, 0, 0, 0.18)`): Hero panels, contact form, modals and key photography.
- **Quiet Card Lift** (`0 14px 40px rgba(15, 48, 37, 0.1)`): Service cards only.
- **Header Separation** (`0 8px 30px rgba(15, 48, 37, 0.08)`): Fixed navigation.

**The Selective Lift Rule.** Elevate only decision surfaces and primary imagery; factual rows remain flat.

## Shapes

Surfaces use restrained curves: 14px for cards and major panels, 12px for buttons and 10px for fields, tabs and image insets. Circular geometry is limited to the theme control. Borders are thin and quiet; proof rows prefer straight separators over containers.

## Components

### Buttons
- **Shape:** Compact rounded rectangle with a 12px radius and a 50px minimum height.
- **Primary:** Deep green with white bold text and 14px × 24px padding.
- **Hover / Focus:** Hover shifts to a lighter green and rises 2px over 180ms; keyboard focus uses a 3px gold outline with 3px offset.
- **Secondary:** Transparent with a deep-green border and text; hover fills deep green and reverses to white.

### Cards / Containers
- **Corner Style:** 14px outer radius with 10px image inset.
- **Background:** White on mineral-green section fields.
- **Shadow Strategy:** Quiet lift for services; decisive lift only for primary surfaces.
- **Internal Padding:** 8px frame and fluid 24–42px content padding.

### Inputs / Fields
- **Style:** White surface, quiet 1px border, 10px radius, 48px minimum height.
- **Focus:** Border shifts to supporting green; the global gold focus-visible outline remains present.

### Navigation
- Fixed white/canvas header with a quiet border and shadow. Links are bold, charcoal and underlined in deep green on hover. On mobile, navigation becomes a full-width dropdown below the header.

### Audience Selector
- Two equal tabs sit on a deep-green panel. The active tab reverses to white; content changes with a restrained 260ms fade-and-rise, removed under reduced-motion preferences.

## Do's and Don'ts

### Do:
- **Do** use professional food photography at decisive scale with functional crops.
- **Do** keep claims factual and neutral; let composition and imagery carry confidence.
- **Do** preserve the light/dark token mapping and visible keyboard focus.
- **Do** give clinics and schools equal prominence.

### Don't:
- **Don't** accumulate generic cards when a flat list or separator communicates the content.
- **Don't** invent badges, metrics, certifications or testimonials.
- **Don't** use gold as a broad decorative accent.
- **Don't** copy competitor branding, layouts or visual signatures.
