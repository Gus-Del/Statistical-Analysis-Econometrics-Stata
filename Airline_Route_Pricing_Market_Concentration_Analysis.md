# Airline Route Pricing & Market Concentration

**Question:** How do distance, market concentration (HHI), low-cost carriers, and other route characteristics affect airline fares?

**Data:** U.S. airline route-level observations including fare, distance, passengers, fuel cost, capacity utilization, and the Herfindahl-Hirschman Index (HHI).

**Methods:** Summary statistics, correlations, scatterplots, log transformations, squared terms, and OLS regression.

**Key variables:**  
- `Fare` / `lnfare` — ticket price (and log)  
- `Distance` / `lndist` — route distance  
- `HHI` / `zHHI` — market concentration  
- `Lowcost` — low-cost carrier presence  
- `Passengers` / `lpassen` — passenger volume  
- `FuelCost` / `lfuelcost` — fuel cost  
- `Caputil` — capacity utilization  

**Output:** Stata log with variable creation, descriptive statistics, and regression results.
