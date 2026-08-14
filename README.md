# A Latent Profile Analysis of Attachment Dimensions and Their Associations with Sleep, Mood, and Fatigue

## Overview

This project uses latent profile analysis (LPA) to identify person-centered attachment profiles from the 12-item Experiences in Close Relationships Questionnaire (ECR-12), then tests whether those profiles differ in sleep quality, sleep hygiene, mood symptoms, and fatigue. A four-profile solution was selected: **Dismissive-leaning**, **Fearful-avoidant**, **Anxious-preoccupied**, and **Secure**. The Fearful-avoidant and Anxious-preoccupied profiles generally showed the most sleep and mood difficulties, while the Secure profile showed the most adaptive pattern overall.

Full write-up, method, and results are in the paper. See the abstract on page 1 for the short version.

## Contents

| File | Description |
|---|---|
| `project.qmd` | Quarto document with the full analysis pipeline: data cleaning, correlation analysis, descriptive statistics, latent profile analysis (`tidyLPA`), profile visualization, and group comparisons (Welch's ANOVA / Games-Howell post hoc) across sleep, mood, and demographic variables. |
| [project.html](https://iChenhahahahahaha.github.io/lpa_attachment_sleep/) | Rendered output of `project.qmd` — open this to view all code, tables, and figures without needing to install R/Quarto or the raw data. |
| `ichen01_practicum26_paper.pdf` | Final written report (APA-style), including the abstract, introduction, method, results, discussion, and references. |
| `ichen01_practicum26_presentation.pdf` | Slide deck summarizing the project. |

## Data

The analysis uses secondary data (`SleepHygiene.csv`) from a study on adult attachment, sleep hygiene, and sleep quality by Samii, Rowe, and Banissy (School of Psychological Science, University of Bristol; 2026, *Psychology & Health*). Participants were 220 adults recruited via Prolific who completed questionnaires via Qualtrics.

**The raw data file is not included in this repo.** Per the original authors' data availability statement, the data are available from the corresponding author upon reasonable request — they are not posted for open/public download.

## Key findings

- **Dismissive-leaning** (13.2%): low anxiety, moderate avoidance — independent, less reassurance-seeking.
- **Fearful-avoidant** (23.2%): high on both anxiety and avoidance — wants closeness but pulls away; the most consistently negative pattern across sleep and mood outcomes.
- **Anxious-preoccupied** (21.4%): low avoidance, high anxiety — open to closeness but worried about the relationship; more sleep problems and poorer mood.
- **Secure** (42.3%): low anxiety and avoidance — the most adaptive pattern, with fewer sleep problems, better mood, and lower fatigue.

Profiles also differed significantly in gender composition and ethnicity, but not in age, relationship duration, or living with a partner.

## Citation

Original data source:

> Samii, J., Rowe, A., & Banissy, M. J. (2026). Adult attachment, sleep hygiene and sleep quality: A cross-sectional mediation analysis. *Psychology & Health*. https://doi.org/10.1080/13548506.2026.2628977
