# CLAUDE.md

This file provides guidance to AI assistants working with this repository.

## Project Overview

This is a minimal example/documentation repository created in 2017. It serves as a simple "Hello World" reference and contains a single README file with a Java code example. The README is written in Russian.

**Primary language**: Java (code snippets only — no compiled source files)
**Type**: Documentation/example repository
**No build system, test framework, or package manager is present.**

## Repository Structure

```
hello-world/
└── README.md    # Project description with a Java Hello World snippet (in Russian)
```

There are no source files, configuration files, or build artifacts in this repository.

## Branches

- `master` — main branch, contains the original commits from 2017
- `claude/*` — feature branches used by AI assistants for automated tasks

## Development Workflow

Since this repository contains only documentation, the typical workflow is:

1. Make changes to `README.md` (or add new documentation files)
2. Commit with a descriptive message
3. Push to the appropriate branch

```bash
git add README.md
git commit -m "Describe your change here"
git push -u origin <branch-name>
```

## Key Conventions

- **Branch naming**: AI-generated branches follow the pattern `claude/<description>-<id>`
- **Commit messages**: Use plain English, imperative mood, concise descriptions
- **No build steps**: There is nothing to compile, test, or lint
- **Language**: The README is in Russian; maintain that convention if editing it

## README Content Summary

The current `README.md` contains:
- **Header**: "Список интерфейсов" (List of interfaces)
- **Subheader**: "Получение описания интерфейса" (Getting interface description)
- **Code example**: A Java `System.out.println("Hello, World!");` snippet

## Notes for AI Assistants

- This repository has no automated tests, linters, or CI pipelines — skip any steps that assume those exist
- Do not add unnecessary build tooling or scaffolding unless explicitly requested
- All commits should go to the designated `claude/*` branch, never directly to `master`
- Keep changes minimal and focused on what was requested
