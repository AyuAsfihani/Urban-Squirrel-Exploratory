# Urban Squirrel Behaviour — Exploratory Analysis \& Early Clustering

**© 2026 Ayu Asfihani. All rights reserved.** This repository is a portfolio summary shared for
recruitment and professional-review purposes only. No part of the content or figures below may
be reproduced, redistributed, or reused without written permission from the author. This project
was completed as part of a university team; the summary below focuses on the author's own
analysis of the shared team dataset.

> 🔒 \*\*This is a summary-only repository.\*\* No source code, no data, and no scripts are published
> here, see \ [Access the full pipeline](#access-the-full-pipeline) at the bottom.

## Summary

[Urban Squirrel Behaviour — Exploratory Analysis Pipeline](squirrel\_exploratory\_poster.png)

The poster above covers the full scope: problem/goal, data resource, tools, the 4-stage
methodology (data cleaning, fur colour \& behaviour charts, temporal \& text analysis, first-pass
clustering \& spatial density), and results.

## Why this project is in the portfolio

Before any formal hypothesis testing is worth attempting, an analyst needs to understand what's
actually in the data including distributions, obvious patterns, and whether naive clustering finds
anything at all. This project is that exploratory phase, run on the 2018 Central Park Squirrel
Census (3,023 sightings), and it directly motivated the rigorous, leakage-safe pipeline in the
companion [Urban Squirrel Environment](#) project in this portfolio, which formally tested and
confirmed the null result these exploratory patterns had only hinted at.

## Headline findings

* Grey squirrels dominated observed activity in every shift (\~1,400 PM sightings vs. \~200
Cinnamon and \~50 Black), read as a population-share effect, not a behavioural difference.
* Sightings peaked sharply on Saturday (\~800) and Sunday (\~780), roughly double any weekday,
consistent with observer availability rather than squirrel behaviour itself.
* First-pass k-Means (k=3) produced three visually separated clusters, but with meaningful
overlap, an early signal, not a robust conclusion.

## Limitations

No statistical significance testing was performed at this stage, these are exploratory
patterns and hypotheses, not confirmed findings. That rigour is exactly what the follow-up
Environmental Factors project adds.

\---

## Access the Full Pipeline

The full exploratory scripts, cleaned dataset, output charts, and a detailed written
interpretation of every finding live in a private repository, shared selectively with
recruiters and hiring teams evaluating me for a Business Analyst / Data Analyst role. **Get in
touch and I'll grant access**, reach me via the contact details on my LinkedIn/CV.

*Ayu Asfihani · Master of Data Science, University of Melbourne · July 2026*

