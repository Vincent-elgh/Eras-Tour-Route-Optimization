# Optimization of Taylor Swift's Eras Tour Route
## Introduction
This project focuses on optimizing Taylor Swift's Eras Tour route across various stadiums for enhanced operational efficiency and environmental sustainability. Utilizing the Miller-Tucker-Zemlin (MTZ) formulation and exploring Fischetti and Toth’s Polyhedral Approach, this study aims to minimize total travel distance and the carbon footprint of the tour, setting a new standard in sustainable event management within the entertainment industry.

## Objectives
- Minimize Total Travel Distance: Reducing logistical costs and improving time management by optimizing the tour route.
- Reduce Carbon Footprint: Promoting environmental sustainability by decreasing the tour's environmental impact.
- Methodological Comparison: Evaluating the MTZ formulation against Fischetti and Toth’s Polyhedral Approach to identify the most efficient routing strategy.
## Problem Description
The project formulates the tour planning as a single-objective optimization problem within the Asymmetric Traveling Salesman Problem (ATSP) framework, focusing on 20 major stadiums across the United States. This scope allows for a manageable and impactful study, potentially serving as a model for future global tours.

## Numerical Implementation and Results
- Data Sources and Types: Utilization of Google Maps API and Bing API for accurate geolocation data of concert venues.
- MTZ Base Model: Application of the MTZ formulation using Gurobi, aiming to minimize the total travel distance.
- Fischetti and Toth Model: Implementation of Fischetti and Toth’s sophisticated approach to efficiently address the ATSP.
## Recommendations and Conclusions
The study recommends adopting the proposed optimization models to improve the efficiency and sustainability of Taylor Swift's Eras Tour. By potentially reducing travel costs and carbon emissions, the findings advocate for a balanced approach to tour planning that prioritizes environmental responsibility alongside operational objectives.

## Future Directions
- Further Refinement: Incorporating a broader range of cost factors and environmental sustainability measures.
- Adaptability: Adjusting optimization models to accommodate dynamic tour scheduling constraints and objectives.
## Appendix
- References: Key literature and APIs used in the project.
- Code Snippets: Python implementations for MTZ and Fischetti and Toth models, including data preparation, model setup, and solution extraction.
