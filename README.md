# Writing & Marketing Content Hub

A spec-driven development structure for managing writing and marketing content, designed to enable AI-assisted content creation.

## Structure Overview

```
├── specs/              # Specifications for all content pieces
│   ├── articles/       # Article specs
│   ├── social/         # Social media post specs
│   └── campaigns/      # Marketing campaign specs
├── content/            # Published/final content
│   ├── articles/       # Written articles
│   ├── social/         # Social media posts
│   └── campaigns/      # Campaign materials
├── ideas/              # Content ideas and brainstorming
│   ├── articles/       # Article ideas
│   ├── social/         # Social post ideas
│   └── campaigns/      # Campaign ideas
├── drafts/             # Work in progress
├── templates/          # Spec templates and content templates
├── context/            # Background info for AI agents
│   ├── brand-voice.md  # Brand voice and tone guidelines
│   ├── style-guide.md  # Writing style guide
│   └── audience.md     # Target audience information
└── archive/            # Completed/archived content
```

## Workflow

1. **Ideation**: Start with ideas in `/ideas`
2. **Specification**: Create a spec in `/specs` based on the idea
3. **Development**: Write content in `/drafts` following the spec
4. **Publication**: Move final content to `/content`
5. **Archive**: Move old content to `/archive`

## Using with AI Agents

The `/context` folder contains essential information about your brand, voice, and audience. AI agents should reference these files when generating new content based on your specs.

## Getting Started

1. Fill out the context files in `/context/` with your brand information
2. Use templates in `/templates/` to create new specs
3. Start adding ideas to `/ideas/`
4. Create specs from your ideas
5. Generate content based on specs
