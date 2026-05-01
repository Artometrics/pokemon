# Pokémon: The Artometrics of the World's Biggest Franchise

A data analysis of 1,028 Pokémon entries across nine generations, drawn
from the TidyTuesday 2025-04-01 dataset (sourced from PokéAPI). Built
as part of the Artometrics content series — data-forward analysis of
creative industries.

## What's in this repo

- `pokemon.qmd` — Quarto markdown file containing all R code, analysis,
  and write-up
- `artometrics.css` — custom HTML theme (same across all Artometrics
  reports)
- `art-head.html` — header injection for fonts and nav
- `art-body.html` — body injection for site chrome
- `charts/chart1_stat_heatmap.png` — median base stat by primary type
  (heatmap)
- `charts/chart2_generation_ridgeline.png` — base experience
  distributions by generation (ridgeline)
- `charts/chart3_size_scatter.png` — height vs. weight across all
  Pokémon, colored by primary type (scatter)

## What the analysis covers

Three charts examining the design infrastructure underneath the
world's highest-grossing media franchise:

1. **Stat Identity by Type** — Does each type actually play
   differently? Median base stats across all 18 primary types reveal
   intentional design specialization, from Dragon's generalist elite
   profile to Bug's across-the-board undertuning.

2. **Generation Creep** — Has Game Freak been inflating Pokémon power
   over time? Ridgeline distributions by generation show a stable median
   but a rising ceiling — each generation adds extreme outliers at the
   top end without dramatically shifting the average.

3. **Built Different** — What does physical size reveal about design
   intent? A height vs. weight scatter on log scale exposes the implicit
   size grammar of the franchise, and the outliers (Cosmoem at 999.9 kg,
   Wailord at 14.5 m) that deliberately break it.

## Data source

Data Science Learning Community. (2025). *TidyTuesday: A weekly social
data project.* Week 13, 2025 — Pokémon.
https://tidytues.day

Original data sourced from PokéAPI: https://pokeapi.co

## Tools

- R / Quarto
- tidyverse · ggplot2 · ggtext · ggridges · ggrepel · scales

## Disclosure

This analysis was researched, written, and produced in active
collaboration with Claude AI (Anthropic). The research questions,
editorial framing, and brand vision are the author's own. Code, analysis,
and prose were developed through a directed human–AI partnership.
All data is publicly available via TidyTuesday and PokéAPI.
