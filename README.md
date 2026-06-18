# PromptForge

PromptForge is a React-based prompt engineering toolkit designed for writers, creators, and AI artists who want greater control over prompt generation and character consistency.

The application helps users generate structured prompts for AI image models by combining text descriptions, image references, scene information, and reusable prompt components into a single workflow.

> ⚠️ Work in Progress — PromptForge is actively being developed and new features are added regularly.

---

## Why PromptForge?

Creating consistent characters and scenes across multiple AI-generated images can be difficult. Small changes in wording often produce dramatically different results.

PromptForge was built to solve this problem by providing tools that help users:

* Generate structured prompts from descriptions
* Extract character details from image references
* Build complex scene prompts
* Reuse prompt components
* Improve consistency across generations
* Reduce repetitive prompt writing

---

## Current Features

### Builder (Text → Prompt)

Generate AI image prompts from written descriptions.

Users can define:

* Character name
* Appearance
* Outfit
* Personality traits
* Environment
* Art style
* Additional prompt instructions

The system converts these inputs into a structured AI-ready prompt.

---

### Character (Images → Prompt)

Upload up to 6 reference images and generate prompts from visual references.

Features:

* Multiple image uploads
* AI-powered image analysis
* Additional custom descriptions
* Automatic prompt generation
* Reference image management

This helps creators maintain visual consistency when generating recurring characters.

---

### Scene Builder (Prompt Stacking)

Combine multiple prompt sources into a single scene.

The Scene Builder can:

* Generate scene descriptions
* Combine character prompts
* Stack prompts from other tabs
* Build larger multi-character scenes
* Create more detailed AI image instructions

This is the core feature that connects the entire application together.

---

## AI Integration

PromptForge currently integrates with Google's Gemini API for image-to-text analysis.

The AI can:

* Describe uploaded images
* Identify visual traits
* Extract useful prompt details
* Assist with character creation

Users can also manually provide descriptions if they prefer not to use AI features.

---

## Tech Stack

Frontend:

* React
* Vite
* JavaScript
* CSS

Storage:

* LocalStorage

AI:

* Google Gemini API

Deployment:

* Netlify

---

## Planned Features

### Character Library

Save and manage reusable character profiles.

Features planned:

* Character presets
* Character editing
* Character categories
* Character consistency controls

---

### Prompt History

Store generated prompts for later reuse.

Features planned:

* Saved prompts
* Search functionality
* Prompt collections
* Prompt favourites

---

### Export / Import

Backup and transfer project data.

Features planned:

* JSON export
* JSON import
* Character backups
* Scene backups

---

### Secure AI Architecture

Current AI requests are handled directly from the browser for development purposes.

Future versions will move AI requests behind secure serverless functions to protect API credentials and improve deployment security.

---

### Future Vision

PromptForge aims to evolve into a complete AI-assisted creation platform capable of:

* Character management
* Prompt engineering
* Scene generation
* Visual consistency tracking
* AI image generation integration
* Multi-character composition planning

---

## Running Locally

```bash
npm install
npm run dev
```

The application will run locally using Vite.

---

## Project Status

Current Version: Active Development

Recent additions:

* Prompt Builder
* Character Image Analysis
* Scene Builder
* Prompt Stacking
* Gemini Integration
* Local Storage Persistence

Planned focus:

* Character Library
* Prompt History
* Secure AI Backend
* Export / Import System
* Advanced Scene Planning

---

Built by Joseph Egbejule

