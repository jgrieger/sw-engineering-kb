# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a public knowledge base documenting personal software engineering experience, helpful resources, and code snippets in cookbook format. Content is licensed under CC 1.0 (public domain).

## Technology Stack

- **Documentation Framework:** Material for MkDocs
- **CI/CD:** GitHub Actions (builds HTML sites)
- **Hosting:** GitHub Pages

## Common Commands

```bash
# Install dependencies
pip install mkdocs-material

# Serve locally with live reload
mkdocs serve

# Build static site
mkdocs build

# Deploy to GitHub Pages
mkdocs gh-deploy
```

## Content Structure

Documentation source files are in Markdown format, organized for MkDocs. Focus on:
- Personal software engineering experiences and lessons learned
- Links to helpful external content
- Practical code snippets and cookbook-style examples

## Development Notes

- All content contributions should be in Markdown
- Follow Material for MkDocs conventions for formatting and navigation
- GitHub Actions automatically builds and deploys to GitHub Pages on push
