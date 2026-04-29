# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Working Relationship

- You can push back on ideas - this can lead to better documentation. Cite sources and explain your reasoning when you do so.
- ALWAYS ask for clarification rather than making assumptions.
- NEVER lie, guess, or make up information.

## Project Overview

This is a Mintlify-based documentation site for **InsureStack**, an AI-powered automation platform for insurance brokerages. The documentation covers features including automated quoting, policy comparison, commission tracking, and submission management.

### Project Context
- **Format**: MDX files with YAML frontmatter
- **Config**: docs.json for navigation, theme, and settings
- **Components**: Mintlify components (Card, CardGroup, Accordion, Steps, etc.)

## Development Commands

### Local Development
```bash
# Install Mintlify CLI globally
npm i -g mint

# Start local development server (runs on http://localhost:3000)
mint dev

# Use custom port
mint dev --port 3333

# Update Mintlify CLI to latest version
npm mint update

# Validate all links in documentation
mint broken-links
```

### Prerequisites
- Node.js version 19 or higher required
- A valid `docs.json` configuration file must be present

## Documentation Structure

### Configuration
- **docs.json**: Central configuration file defining navigation, theme, colors, and global settings
  - Navigation organized into tabs: "Guides" and "API reference"
  - Theme color scheme: primary (#16A34A), light (#07C983), dark (#15803D)
  - Contextual options enabled for copy, view, chatgpt, claude, perplexity, mcp, cursor, and vscode

### Content Organization
The documentation follows a hierarchical folder structure:

```
/
├── index.mdx                 # Homepage/introduction
├── quickstart.mdx            # Getting started guide
├── development.mdx           # Local development setup
├── essentials/               # Core documentation guides
│   ├── settings.mdx
│   ├── navigation.mdx
│   ├── markdown.mdx
│   ├── code.mdx
│   ├── images.mdx
│   └── reusable-snippets.mdx
├── ai-tools/                 # AI integration guides
│   ├── cursor.mdx
│   ├── claude-code.mdx
│   └── windsurf.mdx
├── api-reference/            # API documentation
│   ├── introduction.mdx
│   └── endpoint/
│       ├── get.mdx
│       ├── create.mdx
│       ├── delete.mdx
│       └── webhook.mdx
└── snippets/                 # Reusable content snippets
    └── snippet-intro.mdx
```

### Key Content Files
- **DOCS.md**: Comprehensive user guide for the InsureStack platform (1000+ lines)
  - Covers all platform features, workflows, and best practices
  - Detailed sections on submissions, quoting, policy comparison, commissions, team management, and billing
  - Extensive credit system and subscription plan documentation

## File Format and Syntax

### MDX Format
All documentation pages use MDX (Markdown + JSX), allowing:
- Standard Markdown syntax
- React components embedded in markdown
- Frontmatter metadata (title, description)

### Frontmatter Requirements
Every MDX file MUST include frontmatter at the top:
```yaml
---
title: "Clear, descriptive page title"
description: "Concise summary for SEO and navigation"
---
```

**Do NOT skip frontmatter on any MDX file.**

### Common Mintlify Components
The documentation uses these Mintlify components:
- `<Card>`: Feature cards with icons, titles, and links
- `<CardGroup>`: Grid layouts for multiple cards
- `<Columns>`: Multi-column layouts
- `<Accordion>` / `<AccordionGroup>`: Collapsible content sections
- `<Steps>` / `<Step>`: Sequential instruction guides
- `<Tip>`, `<Note>`, `<Info>`, `<Warning>`: Callout boxes
- `<Frame>`: Image containers with styling

Example:
```mdx
<Card
  title="Feature Name"
  icon="rocket"
  href="/path/to/page"
>
  Feature description here
</Card>
```

## Navigation Management

Navigation is defined in `docs.json` under the `navigation` key. The structure uses:
- **Tabs**: Top-level navigation categories
- **Groups**: Sections within tabs
- **Pages**: Individual documentation pages (paths without `.mdx` extension)

To add a new page:
1. Create the `.mdx` file in the appropriate directory
2. Add frontmatter (title, description)
3. Update `docs.json` navigation to include the new page path

## Deployment

- Changes deploy automatically via Mintlify's GitHub app integration
- Install the app from: https://dashboard.mintlify.com/settings/organization/github-app
- Pushing to the default branch triggers automatic production deployment
- Local preview at `http://localhost:3000` reflects changes in real-time

## Brand and Theme

### Visual Identity
- Logo file: `/logo/insurestack-logo-only.svg` (used for both light and dark themes)
- Favicon: `/favicon.ico`

### Color Scheme
Defined in `docs.json`:
- Primary: #0066C1 (blue)
- Light: #0096EE (bright blue)
- Dark: #005098 (dark blue)

## Troubleshooting

### Common Issues

**Port 3000 already in use:**
```bash
mint dev --port 3333
```

**Sharp module error on darwin-arm64:**
1. Remove CLI: `npm remove -g mint`
2. Upgrade to Node v19+
3. Reinstall: `npm i -g mint`

**Unknown errors:**
Delete `~/.mintlify` folder and retry `mint dev`

**Preview doesn't match production:**
Update CLI: `npm mint update`

## Content Strategy

- **Document just enough for user success** - not too much, not too little
- **Prioritize accuracy and usability** of information
- **Make content evergreen** when possible
- **Search for existing information** before adding new content. Avoid duplication unless it is done for a strategic reason
- **Check existing patterns** for consistency
- **Start by making the smallest reasonable changes**

## Writing Standards

### Voice and Style
- Use **second-person voice** ("you") when addressing users
- Place **prerequisites at the start** of procedural content
- Match the style and formatting of existing pages

### Code Examples
- **Test all code examples** before publishing
- Include **language tags** on all code blocks
- Provide both **basic and advanced use cases** where applicable

Example:
```bash
# Always specify the language
mint dev --port 3333
```

### Links and Media
- Use **relative paths for internal links** (e.g., `/essentials/markdown` not `https://docs.example.com/essentials/markdown`)
- Include **alt text on all images**
- Do NOT use absolute URLs for internal links

### What NOT to Do
- Skip frontmatter on any MDX file
- Use absolute URLs for internal links
- Include untested code examples
- Make assumptions - always ask for clarification

## Git Workflow

- **NEVER use `--no-verify`** when committing
- **Ask how to handle uncommitted changes** before starting work
- **Create a new branch** when no clear branch exists for changes
- **Commit frequently** throughout development
- **NEVER skip or disable pre-commit hooks**

## Content Guidelines

### When Creating New Documentation

1. **Use proper frontmatter** on all `.mdx` files (required):
   ```yaml
   ---
   title: "Page Title"
   description: "Brief description for SEO and previews"
   ---
   ```

2. **Follow existing component patterns** from other pages

3. **Update navigation** in `docs.json` after creating new pages

4. **Use descriptive icons** from the available icon set (see other pages for examples)

5. **Test locally** with `mint dev` before committing

6. **Validate links** with `mint broken-links` before major changes

### Platform-Specific Context

This documentation is for an **insurance brokerage platform** that uses:
- Credit-based billing system
- Metronome for usage tracking
- Stripe for payments
- Multi-tenant organization structure
- AI-powered automation for quotes, policies, and commissions

When editing platform documentation:
- Maintain accuracy about credit costs and subscription plans
- Ensure technical accuracy about supported carriers and features
- Keep user flow descriptions aligned with actual platform behavior
- Cross-reference related features appropriately
