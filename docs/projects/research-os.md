---
title: Research OS
description: An open, privacy-first research operating system for PhD students and researchers.
---

# Research OS v0.1

![Research OS monthly habit and focus workspace](../assets/images/research-os-dashboard.png)

> **Consistency wins.** Research is not only about reading papers and searching for a gap. It
> is also the daily practice of writing, analysing, documenting, reflecting, protecting your
> energy, and returning to difficult questions with discipline.

## Research work needs more than a to-do list

Research OS is an open, privacy-first workspace I designed and built for PhD students and
researchers. It turns small, repeatable actions into a visible system connecting focused
analysis, scientific writing, literature, experiments, datasets, supervision, deadlines,
conferences, habits, and long-term outputs.

The central design principle is simple:

> Daily action → research project → evidence → output → milestone

Instead of treating productivity as an isolated checklist, Research OS keeps the connection
between today's action and the scientific result it is intended to advance.

## What I built

- A daily research command center with a large persistent checklist and focus timer
- Project templates for theses, manuscripts, datasets, experiments, reviews, and conferences
- A scientific pipeline from idea and design through analysis, writing, review, and publication
- A research calendar, knowledge inbox, and structured weekly review
- A full monthly habit tracker with custom goals, categories, colors, streaks, and progress charts
- Versioned JSON export and validated import for portable local backups
- Responsive desktop and mobile navigation with dark and light themes
- An installable Progressive Web App with an offline application shell
- Standalone Docker packaging and an automated GitHub quality workflow

## Privacy-first architecture

The public application contains fictional example data only. In the current local-first mode,
personal workspace data stays inside the user's browser and can be exported as JSON. No account
is required. Cloud synchronization is an optional future mode and is designed to require
authentication, per-user ownership, server-side validation, and database Row Level Security.

## Engineering

`Next.js` `React` `TypeScript` `Tailwind CSS` `PWA` `Docker` `GitHub Actions`

The interface uses server components by default and limits client-side code to interactive
workspaces. The project includes strict type checking, linting, production builds, an MIT
license, contribution guidance, and a documented path toward secure multi-user deployment.

## Current status

**Version:** 0.1.0  
**Role:** Product design, research-workflow modelling, frontend engineering, and documentation  
**Status:** Functional local-first release; hosted demonstration and optional cloud mode are next

[View source on GitHub :fontawesome-brands-github:](https://github.com/ElFarchouni/Research-os){ .md-button .md-button--primary }

!!! info "Installable demonstration in progress"
    The public application build is ready. The live link will be added after GitHub Pages is
    enabled for the new repository.

[Back to all projects :material-arrow-left:](index.md){ .md-button }
