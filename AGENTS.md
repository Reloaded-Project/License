# Agent Guidelines: License Documentation

## Context
These guidelines help you write new pages that match our existing docs while allowing different content depth by topic. Prioritize adoption, clarity, and showing features in action.

## Documentation Build Guidelines

When working with the documentation:

- **Always run `mkdocs build --strict`** to validate the documentation build with strict error checking
- **Never run `mkdocs serve`** — the live server is blocking and prevents other work
- Validate your changes with the strict build before committing

## Core Invariants
- **Active voice, concise sentences**: Prefer direct, outcome-focused language.
- **Scannability**: Use headings and bullet lists to organize content.
- **Visuals with captions**: Use `.avif` where visuals add clarity; include a caption.
- **Link hygiene**: Prefer relative links for internal docs; link to official tool docs externally.
- **Admonitions for emphasis**: Use `tip`, `info`, `warning`, `example`, and collapsible `???` blocks.

## Visuals
- Prefer `.avif` images with descriptive alt text and captions.
- Include visuals when they clarify outcomes; skip them for configuration pages if not valuable.

Caption format:
```markdown
![Descriptive alt text](../assets/image.avif)
/// caption
Clear explanation of what's shown and why it matters
///
```

## Admonitions
Use for emphasis and scannability:
```markdown
!!! tip "Best Practice"
    Helpful hint for optimal usage.

!!! info "Additional Context"
    Extra useful information.

!!! warning "Important Note"
    Critical information.

!!! example "Real World Use"
    Practical example.

??? info "Advanced Details"
    Collapsible technical details.
```

## Annotations
Inline and list annotations are allowed:
```markdown
Text with annotation (1)
{ .annotate }

1.  This is the annotation content.
```

For lists:
```markdown
<div class="annotate" markdown>

1. item one (1)
2. item two

</div>

1. annotation for item one
```

## Linking Conventions
- **Internal**: Relative links (e.g., `../index.md#getting-started`).
- **Anchors**: In "Key Features", link to sections like `#license-terms`.
- **GitHub file links**: Use direct links to repository files when instructing users to copy.
- **External**: Link to official documentation and standards (SemVer, GitHub, etc.).

## Authoring Snippets
- **Hero image with caption**
```markdown
![License Information](../assets/license-info.avif)
/// caption
Overview of license terms and conditions
///
```

- **Key Features with anchors**
```markdown
## Key Features
- **[License Terms](#license-terms)**: Clear conditions and permissions
- **[Attribution Requirements](#attribution-requirements)**: How to give credit
- **[Usage Guidelines](#usage-guidelines)**: Best practices for use
```
