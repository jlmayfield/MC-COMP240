---
layout: page
title: COMP240 - Tufte's Visualization of MLB Game Data
permalink: /teaching/COMP240/projects/tufteMLB
---

## The Goal

Generate Tufte graphics as a Poster/Document.
* Original Graphic: Paragraph = Division for one season. Document = MLB for the season
* Variation 1: 1 Team over a series of years. Paragraph = group by decade (or some number of years)
* Variation 2: World Series for a series of years. Paragraph = season for the WS teams
* Variation 3: {t} teams, for seasons [a,b), grouped by year.

Design a library that provides top-level functions that produce the requested graphic as
high-res image (maybe user specfied size)

## The Tools

Retrosheet Data (MySQL) + Python + SQLAlchemy + Pandas + MatPlotLib + pylint + pytest
