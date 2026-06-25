# Skills Repository

My custom curated collection of custom agentic skills following the Skills standard convention.

## Overview

This repository serves as a centralized hub for specialized skills designed to extend agent capabilities. Each skill is self-contained, follows a consistent structure, and is independently versioned to ensure modularity and maintainability.

## Repository Structure

```
skills/
├── .skills/                    # Global configuration
│   └── config.yaml            # Repository-level settings
├── [skill-name]/              # Individual skill directory
│   ├── SKILL.md               # Skill definition with metadata
│   ├── scripts/               # Executable implementations
│   ├── references/            # Documentation and schemas
│   └── assets/                # Static resources
└── README.md
```

## Skill Convention

Each skill directory adheres to the following specifications:

### `SKILL.md` (Required)
- Contains YAML frontmatter with metadata (`name`, `description`, `version`, `author`, `tags`, `dependencies`)
- Includes comprehensive documentation covering usage, examples, and configuration
- Serves as the primary entry point for skill discovery

### `scripts/` (Optional)
- Executable scripts or source code implementing the skill's logic
- Language-agnostic; may include shell scripts, Python modules, or compiled binaries
- Must be self-contained with all required dependencies documented

### `references/` (Optional)
- Supplementary documentation, API references, or data schemas
- Used for contextual information that supports skill operation
- May include markdown files, JSON schemas, or other structured data

### `assets/` (Optional)
- Static resources such as templates, images, or configuration files
- Provides reusable components that skills can reference

## Skills Index

| Skill | Description | Version |
|-------|-------------|---------|
| *Add your skills here* | *Brief description* | *Semantic version* |

## Governance

- Each skill is independently versioned using semantic versioning (MAJOR.MINOR.PATCH)
- Skills are validated against the standard convention to ensure compatibility
- Updates are managed through standard Git workflows with proper review

## License

This repository and its contents are licensed under the [MIT License](LICENSE) unless otherwise specified per skill.

---
