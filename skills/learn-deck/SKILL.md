---
name: learn-deck
description: |
  Creates a PowerPoint presentation on a Microsoft technology topic using Learn documentation.
  Use when user asks to "create a deck", "make a presentation", "build slides",
  "PowerPoint about", "slide deck on", or wants a presentation summarizing
  a Microsoft technology, service, or concept.
license: MIT
metadata:
  author: Daniel Laskewitz
  version: "1.0"
---

# Learn Deck

A skill for creating PowerPoint presentations based on thorough research from Microsoft Learn documentation.

## Workflow

### Step 1: Clarify the Topic

Ask the user what topic they want a presentation on. Help them narrow it down:

- "What Microsoft technology or topic would you like me to create a deck about?"
- If the topic is broad (e.g., "Azure"), ask them to be more specific (e.g., "Azure Functions" or "Microsoft Copilot Studio")
- Ask about the target audience (technical, business, mixed)
- Ask about the desired length (5-10 slides, 10-15 slides, etc.)

### Step 2: Research the Topic

Use the `microsoft-learn` connector to thoroughly research the topic. Perform **multiple searches** to gather comprehensive information:

- Search for the main topic overview
- Search for key features and capabilities
- Search for architecture or how it works
- Look for code samples and practical examples
- Search for best practices and common patterns
- Look for getting started guides and prerequisites

**Important:** Perform at least 3-5 searches to ensure thorough coverage. Each search should explore a different angle.

### Step 3: Structure the Presentation

Organize your research into a logical slide structure:

1. **Title Slide** — Topic name and subtitle
2. **Overview** — What it is and why it matters
3. **Key Features/Capabilities** — Main highlights (use bullet points)
4. **How It Works** — Architecture or workflow (suggest a diagram if applicable)
5. **Getting Started** — Prerequisites and first steps
6. **Demo/Example** — Code samples or walkthrough
7. **Best Practices** — Tips and recommendations
8. **Resources** — Links to key documentation pages

### Step 4: Create the Deck

Use the PowerPoint skill to generate the presentation with:

- Clear, concise bullet points (not walls of text)
- One key idea per slide
- Speaker notes with additional detail from the research
- Links to source documentation in the notes

## Guidelines

- Always let the user choose the topic — never assume
- Be thorough in research: multiple searches are better than one
- Keep slides concise — detail goes in speaker notes
- Include source links for credibility
- Ask if they want any specific sections added or removed
- Prioritize official Microsoft documentation
