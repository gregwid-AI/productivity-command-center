# Personal Productivity Command Center

A self-updating command center that discovers every automation in an agent workspace,
classifies each one into the productivity subject area it protects, scores its
reliability from run history, and surfaces the coverage gaps worth automating next.

**Live demo:** https://gregwid-ai.github.io/productivity-command-center/

## What you are looking at

- An animated neural core rendered on canvas, with drifting particles and
  proximity-linked synapses, sitting at the center of the operating model
- KPI stats flanking the core in a three-column stage
- Click the brain to reveal functional areas; click an area to pop it out in a
  responsive quarter-width grid
- Three tabs: Command center, Recommendations & gaps, and How it works & reuse
- The third tab contains a portable prompt to rebuild the whole system

## Data notice

This is a **portfolio build**. Automation names are replaced with their generic
subject-area role and all run output is stripped. Structure, health, reliability and
counts are real; nothing customer-, financial- or calendar-specific is published.

## How it is built

A single PowerShell generator reads the local automation store and emits one
self-contained HTML file - no external assets, no CDN, no build step. It runs
nightly and republishes automatically.
