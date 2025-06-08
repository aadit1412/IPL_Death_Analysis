# IPL Death Overs Bowling Analysis (2022–2025)

This repository contains a contextual analytics project on bowling performance in the death overs (overs 16–20) of IPL matches between 2022 and 2025.

## Project Context

This project was built as a data-driven deep dive into how IPL bowlers perform under pressure in the final overs of a T20 innings. Instead of relying solely on traditional metrics like economy or wickets, the analysis introduces a **Pressure Index**—a custom scoring model that evaluates bowlers based on context-sensitive situations.

Key aspects of the project include:

- Cleaning and merging IPL ball-by-ball data
- Engineering a ‘closeness’ metric to judge match intensity
- Assigning dynamic weights to wickets, dots, extras, and boundaries, and creating a pressure index based on them
- Aggregating scores at the bowler level and normalizing them
- Creating visualizations to compare and interpret bowler performance

The aim was to create a more holistic picture of who the real impact bowlers are in high-stakes moments.

## What's Included

- `death_overs.ipynb`: Final Jupyter Notebook with analysis, visualizations, and commentary
- `death_overs.py`: Clean script version of the project workflow
- `Images`: Visualizations
- `data`: 2022-25 ball-by-ball data, 2022-25 match data
- `README.md`: Project overview and documentation

## Pressure Index Overview

The Pressure Index is designed to reflect not just performance, but **timing and match impact**. It is calculated per delivery and aggregated by bowler. Key features:

- **Dynamic weights**: Higher value given to wickets and dot balls in tense run chases
- **Over multipliers**: Later overs (19–20) weighted more heavily
- **Closeness scaling**: Performances in “Nailbiter” or “Very Close” matches count more
- **Normalized scores**: All bowler scores scaled from 1 to 100 for fair comparison

## Metrics Included

Each bowler is evaluated based on the following:

- Economy Rate
- Strike Rate
- Dot Ball %
- Boundary %
- Wickets Taken
- Contextual Pressure Score (1–100)

## Visualizations

- Matplotlib bar charts for static comparisons
- Plotly line charts for over-wise pressure progression
- Plotly tree map for wicket-type distribution
- Filtering by bowler, over, or match context

## Contact

If you want to discuss the project, give feedback, or explore ideas in cricket analytics, feel free to reach out!

- [LinkedIn](https://www.linkedin.com/in/your-profile)
- 📧 aaditpahuja@gmail.com
