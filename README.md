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
- Created visualizations

## Key Findings

One of the most interesting findings was that 11 vs 6 upsets actually occurred more often than 12 vs 5 upsets in this dataset. Even though 12 vs 5 matchups are usually the most talked-about upset games during March Madness, the data showed that 11 vs 6 upsets were slightly more common.

12 vs 5 upsets were still one of the most frequent upset patterns and appeared consistently throughout the dataset.

## Bootstrap Analysis

I also used bootstrapping to estimate uncertainty for the proportion of 12 vs 5 upsets in the dataset. By repeatedly resampling the data with replacement, I created a bootstrap distribution and estimated a confidence interval.

The bootstrap results showed that the estimated proportion of 12 vs 5 upsets usually stayed around 12% across the resampled datasets. Most of the values fell between about 8% and 17% which gives a reasonable range for where the true proportion of these upsets may fall.

## Limitations

One limitation of this project is that the dataset only includes upset games instead of all tournament games. Because of this, the analysis cannot estimate the actual probability of a 12-seed beating a 5-seed. Instead, the project focuses on how often certain upset matchups appear compared to others.  "Upset Seed Info.csv" was the dataset used on this project.

## Sources

- Kaggle March Madness Dataset:
  https://www.kaggle.com/datasets/nishaanamin/march-madness-data

- NCAA March Madness historical information:
  https://www.ncaa.com/march-madness-live

- Course materials and previous class exercises from SEIS 631 – Data Prep & Analysis
