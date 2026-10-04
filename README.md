# Gridantaw

### A Residential Demand Response Platform for Peak Demand Management

Gridantaw is a concept for helping residential communities participate in demand response programs during peak electricity demand periods.
As electricity demand continues to rise across India, utilities often face stress during peak hours. While industries already participate in energy management programs, residential communities remain an underutilized opportunity despite being one of the largest electricity-consuming sectors.
Gridantaw aims to bridge this gap by connecting residential communities with the grid during peak-demand events. The platform helps identify flexible loads that can be shifted with minimal impact on resident comfort while providing visibility into potential savings and community contribution.

## Problem Statement

- Residential electricity consumption is growing rapidly.
- Peak demand periods increase stress on the grid.
- Residents often have limited awareness of:
  - Peak demand events
  - Flexible household loads
  - Potential savings from load shifting
- Utilities face challenges in coordinating demand response at a community scale.

## Proposed Solution

Gridantaw acts as a residential demand response platform.

During a peak-demand event:

1. The Grid/DISCOM issues a demand response request.
2. Gridantaw identifies participating households and flexible loads.
3. Recommendations are generated using optimization techniques.
4. Residents receive suggested actions through a dashboard.
5. Community demand is reduced while maintaining resident comfort.

## Technical Approach

### Community Simulation
A residential community is simulated using the Mesa agent-based modeling framework.

Different household profiles are modeled, including:
- Working professionals
- Families
- Senior citizens
- EV owners

Each household has different energy usage patterns and preferences.

### Optimization
PuLP is used to determine suitable load-shifting actions while considering:
- Demand reduction targets
- User preferences
- Resident comfort
- Flexible and non-flexible loads

### Dashboard
A user dashboard provides:
- Peak demand alerts
- Recommended actions
- Estimated savings
- Community contribution insights

## Tech Stack

- Python
- Mesa
- PuLP
- Streamlit

## Expected Impact

- Reduced peak electricity demand
- Improved grid reliability
- Better visibility into energy consumption
- Potential cost savings for residents
- Community-scale participation in demand response programs

## Current Status

🚧 Idea & Simulation Prototype Stage

The current focus is on building:
- Household simulation models
- Optimization workflows
- Interactive dashboard prototypes
