# Truck Logistics Route Optimization (A* Search)

## Project Overview
This project uses the A* Search algorithm to find the most efficient route between **Disaneng** and **Coligny** while considering both road distance (weight) and city traffic (heuristics).

## Results
- **Optimal Path:** Disaneng -> Mahikeng -> Bakerville -> Lichtenburg -> Coligny
- **Total Cost:** 110 km
- **Visited Nodes:** Disaneng, Mahikeng, Mmabatho, Slurry, Bakerville, Lichtenburg, Coligny

## Analysis
The algorithm chose **Bakerville** over **Slurry** because Bakerville had a lower traffic heuristic (30 vs 45), which reduced the overall $f(n)$ score.
