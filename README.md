# DS Pulse Design System

## Overview

DS Pulse is a markdown-based design system documentation used as the **single source of truth** for UI generation, frontend development, and AI/LLM integration.

This design system is optimized for:

* UI consistency
* AI-assisted frontend generation
* Vibecode / LLM integration
* Reusable component architecture
* Accessibility compliance

---

# Purpose

This repository provides:

* Global design tokens
* Semantic tokens
* Component specifications
* Interaction rules
* Accessibility guidelines
* Asset references (SVG / Sticker / Logo)

The goal is to ensure generated UI output maintains **high consistency (>90%)** with the intended design system.

---

# Design Philosophy

DS Pulse uses a:

```text id="9yhohy"
STRICT TOKEN SYSTEM
```

Meaning:

* Do NOT modify token values
* Do NOT create new tokens
* Do NOT infer missing values
* Use ONLY values defined in the design system

---

```text id="1jlwmn"
DS-Pulse/
│
├── DS Pulse Component.md
│
├── Asset/
│   ├── sticker_patient/
│   ├── sticker_vitalsigns/
│   ├── sticker_disease/
│
├── Siloam Logo 16_9.svg
│
└── README.md
```

---

# Main Documentation

Main design system source:

```text id="gr8w5r"
DS Pulse Component.md
```

Contains:

* Design tokens
* Semantic tokens
* Component specifications
* Usage rules
* Accessibility
* Do & Don't guidelines

---

# Design Token Categories

## Global Tokens

* Color
* Typography
* Spacing
* Border
* Opacity
* Effects
* Icon
* Sizing

## Semantic Tokens

* Background
* Border / Stroke
* Text / Icon
* Accent

---

# Components

Example components included:

* Accordion
* Alert
* Avatar
* Badge
* Breadcrumb
* Button
* Card
* Chart
* Dropdown
* Dropzone
* Header Navigation Bar
* Input
* Modal
* Pagination
* Progress Bar
* Radio
* Range
* Side Navigation Bar
* Switch
* Table
* Tabs
* and more

Each component contains:

* Color
* Size
* Usage
* Anatomy
* Properties
* Accessibility
* Do & Don't

---

# SVG & Asset Usage

SVG assets are stored in:

```text id="bhftf3"
Asset/
```

Assets include:

* Patient stickers
* Disease stickers
* Vital signs stickers
* Logo assets

Assets are referenced using:

```html
<img src="https://raw.githubusercontent.com/..."/>
```

---

# LLM / AI Integration

This design system is optimized for:

* ChatGPT
* Claude
* Figma Make
* Gemini
* Cursor AI
* Copilot
* Vibecode

---

# How to Use with LLM

## Step 1 — Attach Markdown File

Upload:

```text id="3opuxr"
DS Pulse Component.md
```

to your LLM platform.

---

## Step 2 — Use Structured Prompt

Recommended prompt:

```text id="v3vdrd"
Use the attached design system markdown as the source of truth.

Generate UI components based on:
- design tokens
- semantic tokens
- component specifications
- accessibility rules
- interaction behavior

Do NOT create new values.
Do NOT modify existing tokens.
Maintain >90% similarity with the design system.
```

---

# Recommended Workflow

```text id="hgjc9m"
1. Update markdown documentation
2. Attach markdown to LLM
3. Generate UI/component
4. Validate against design system
5. Iterate if necessary
6. Push to production
```

---

# Best Practices

## ✅ Do

* Keep component naming consistent
* Follow defined tokens exactly
* Use semantic colors properly
* Maintain accessibility support
* Keep component structure consistent

## ❌ Don't

* Add arbitrary spacing values
* Modify color definitions
* Create undefined variants
* Ignore accessibility rules
* Infer missing values

---

# Accessibility

This design system includes:

* Keyboard interaction support
* ARIA guidelines
* Touch target sizing
* WCAG color contrast consideration

---

# Technology Recommendation

Recommended stack:

* React
* TypeScript
* TailwindCSS
* Storybook
* MD Documentation


---

# Repository Goal

This repository aims to create:

```text id="mteq9l"
LLM-ready Design System Documentation
```

that enables:

* scalable frontend development
* reusable UI architecture
* AI-assisted implementation
* high UI consistency

---

# License

Internal Design System — Siloam / DS Pulse.
