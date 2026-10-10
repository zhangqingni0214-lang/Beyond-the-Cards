# Beyond the Cards — Submission Details

## Short description

Beyond the Cards is an interactive tarot experience designed for AI-assisted learning and expression, helping users turn visual symbols and personal context into stories.

## Built with

HTML5 · CSS3 · JavaScript · SVG · localStorage · GitHub Pages · GitHub Actions

The current prototype uses local rules and narrative templates; a live AI model has not yet been integrated.

## Inspiration

Tarot cards are a rich visual language, yet beginners often start by memorizing fixed meanings. Connecting imagery, spread positions, upright and reversed perspectives, and a personal question can be difficult. We want AI assistance to make tarot learning a process of observation, understanding, and creation: starting with the art of the cards and moving toward the user's own story.

## What it does

Beyond the Cards connects tarot learning and personal expression in one experience. Users draw one or three cards, explore scenes and symbols, compare upright and reversed perspectives on the same card, and add their observations, associations, questions, and emotions.

These elements become starting points for personal stories, storyboards, journal entries, poems, character stories, or Tarot Story Cards. Users can edit, save, and export their work. Interpretations inspire reflection and creativity; users decide what the imagery means to them.

## How we built it

We built on an existing tarot curriculum, 78-card library, journal, and learning structure to design a mobile journey: **See → Understand → Connect → Express**.

The frontend uses HTML, CSS, and vanilla JavaScript. Local rules and templates produce creative drafts, localStorage saves drafts and works, and SVG supports story-card export. GitHub Pages hosts the experience, with automatic deployment through GitHub Actions.

During ForgeHacks, we focused on the interpretation coach interaction prototype, narrative workflow, personalized reflection system, and creative interaction journey. Live AI model integration remains future work.

## Challenges we ran into

Our first challenge was continuity. Scrolling after a draw, controls covering card artwork, and scattered actions interrupted visual exploration. We brought drawing and interpretation into the same visual area and refined the mobile interaction hierarchy. Reversed perspectives became a comparison on the same card, preserving the object users were exploring.

We also needed to distinguish visual observations, teaching interpretations, and personal associations, and to clearly communicate the boundary between the rule-based prototype and live AI capabilities.

## Accomplishments that we're proud of

We completed a journey from visual exploration to editing, saving, and exporting creative work. The experience includes a complete English library of 78 cards, single-card and three-card exploration, and upright and reversed comparison on the same card. We also published the repository, a GitHub Pages demo, and an English demo video.

What we value most is that the user's observations and words are central to the creative process: the cards offer inspiration, and the user writes the story.

## What we learned

We learned that tarot learning is about more than remembering meanings: it involves understanding how visual clues connect. Inviting users to observe first and then compare interpretations supports active learning.

Creative experiences also need room for editing and disagreement, so users retain control of their expression. Clear knowledge structures, continuous interaction, and editable outputs are important foundations to establish before integrating a live AI model.

## What's next

Next, we plan to integrate a live AI model and tarot knowledge retrieval, grounding interpretations in specific visual evidence and generating more varied creative suggestions based on personal context.

We also plan to expand symbol hotspots and learning feedback, explore generative visual narratives, add cross-device saving and work sharing, and evaluate the relevance, grounding, and narrative quality of AI outputs.
