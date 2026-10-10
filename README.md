# Beyond the Cards

**From the Art of the Cards to the Story of You.**

An AI-assisted experience that helps you interpret visual symbols and turn them into personal narratives.

Version **1.2.2** · Mobile interactive prototype · English interface

## What is Beyond the Cards

Beyond the Cards builds on an existing tarot curriculum and learning structure to connect visual exploration, personal reflection, and storytelling. Users explore symbols, develop their own interpretations, and turn their ideas into creative works they can edit, save, and share.

The experience is designed for AI-assisted learning and self-expression. The current prototype uses local rules and templates; a live AI model has not yet been integrated.

## Problem

Traditional tarot learning asks beginners to memorize isolated card meanings, but offers little support for connecting visual symbols, spread positions, upright and reversed perspectives, relationships between cards, and personal context. Learning often stops at looking up answers, leaving limited room for observation, self-expression, and creation.

## Solution

The core journey is **See → Understand → Connect → Express**. Users draw one or three cards, explore visual details, record personal associations, and add a question or emotion. The experience then provides editable interpretations and creative drafts.

Interpretations support personal reflection rather than presenting card meanings as certain predictions of the future.

## Key Features

- **Visual exploration:** Browse, filter, and search an English library of 78 cards. Explore card scenes, with interactive symbol hotspots on selected cards.
- **Upright and reversed comparison:** Explore both perspectives on the same card while preserving the original draw and user input.
- **Personal expression:** Connect observations, associations, questions, and emotions through single-card and three-card narrative structures.
- **Multiple creative formats:** Create personal stories, visual storyboards, journal entries, poems or short texts, character stories, and Tarot Story Cards.
- **Editing and saving:** Edit titles and text, automatically save local drafts, revisit saved works, copy text, and export SVG story cards.

## AI Architecture

**Current implementation**

```text
Card knowledge + Spread positions + Upright/reversed perspectives + User input
    → Local rules and narrative templates
    → Editable creative output
```

The prototype does not call external models and requires no API key. Drafts and saved works are stored in the current browser.

**Planned integration**

```text
Frontend input
    → Server-side AI endpoint
    → Tarot knowledge retrieval
    → Model-generated structured interpretations and creative suggestions
    → User selection, editing, and saving
```

Model interpretations will reference visual evidence and distinguish observations from inferences. API keys will remain on the server. User feedback will help refine interpretations, while users retain control over the final expression.

## Tech Stack

HTML, CSS, and vanilla JavaScript; local card data and images; browser localStorage; and SVG export. The application is static, requires no build step, and uses a mobile layout.

## How to Run

With Python 3 installed, run the following command from the project root:

```bash
python3 -m http.server 4173 --directory dist
```

Open http://localhost:4173 in your browser. No frontend dependencies or AI credentials are required. Use a mobile viewport for the intended experience. Drafts and saved works do not sync across devices.

## Screenshots

| Card Exploration | Full Creative Workflow |
| --- | --- |
| <img src="docs/screenshots/mobile-exploration.jpg" width="260" alt="Card exploration in the English mobile interface"> | <img src="docs/screenshots/mobile-workflow.jpg" width="260" alt="The creative workflow in the English mobile interface"> |

## What We Built During ForgeHacks

| Phase | Work |
| --- | --- |
| **Pre-existing work** | Tarot curriculum, card library, journal and learning structure. |
| **Built during ForgeHacks** | AI Interpretation Coach interaction prototype, AI narrative reasoning workflow prototype, personalized reflection system, and AI interaction workflow. |

The work completed during ForgeHacks connects visual exploration, upright and reversed comparison, personal context input, and creative editing and saving into a complete interaction journey. AI interpretation and narrative reasoning are currently demonstrated through local rules and templates; live model integration remains future work.

## Future Work

- Integrate a live AI model and knowledge retrieval, and evaluate visual grounding, relevance, and narrative quality.
- Expand symbol hotspots and learning feedback to help users develop independent interpretation skills.
- Introduce generative visual narratives to enrich storyboards and story cards.
- Add cross-device saving and work sharing, with clear data management options.
