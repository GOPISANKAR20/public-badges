# Public Badge Repository

This repository hosts badge assets generated automatically from private GitHub repositories.

## Purpose

Private repositories cannot expose badges publicly.

GitHub Actions generate badges during every build and publish them here.

Only badge assets (SVG files) are stored.

No source code is ever copied.

## Repository Structure

```
public-badges/
│
├── private-project/
│   ├── build.svg
│   ├── release.svg
│   ├── coverage.svg
│   ├── security.svg
│   └── deployment.svg
```

## Workflow

Private Repository

↓

GitHub Actions

↓

Generate Badges

↓

Publish to Public Badge Repository

↓

README / Dashboards

## Security

- Source code is never published.
- Uses GitHub Personal Access Token.
- Repository contains only SVG badge files.
