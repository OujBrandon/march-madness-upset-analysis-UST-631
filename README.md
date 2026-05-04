# March Madness Upset Analysis (12 vs 5)

## Project Overview

In this project, I look at upset patterns in the NCAA March Madness tournament. I focus on the 12 vs 5 matchup, which is known for producing upsets, to see how often it shows up in the data compared to other matchups.

## Research Question

How common are 12-seed upsets compared to other seed matchups in March Madness?

## Motivation

The 12 vs 5 matchup is one of the most talked-about parts of March Madness. It feels like 12-seeds win pretty often, so I wanted to check if that idea actually shows up in real data.

## Data Source

The dataset includes historical March Madness upset games. Each row represents a game where a lower-seeded team beat a higher-seeded team.

Key columns used:

- `SEED WON` – seed of the team that won
- `SEED LOST` – seed of the team that lost
- `YEAR` – year of the tournament
- `SEED DIFF` – difference between the two seeds

## What I Did (EDA)

For the exploratory data analysis, I:

- Loaded and looked through the dataset
- Identified the important columns
- Filtered for 12 vs 5 matchups
- Counted how often different upset matchups occur
- Created a visualization to compare them

## Repository Structure
