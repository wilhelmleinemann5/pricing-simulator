# pricing-simulator
A repo for a pricing simulator game


🌊 Ocean Pricing & Trade Simulation Game (Updated Recap)
🎯 Objective:
Equip Ocean Carrier Pricing and Trade Managers with the skills to effectively balance fixed-rate contracts and dynamic spot pricing, optimizing weekly container pricing strategies to maximize revenue.

🚢 Key Simulation Dynamics (Clarified):
1. Inventory Management
Weekly inventory of container slots (e.g., 500 per week).

Inventory is perishable weekly, aligning with vessel departure schedules.

2. Booking Products
Contract (Fixed-Rate) Bookings

Rates set quarterly and remain constant each week within the quarter.

Booking volumes vary weekly based solely on the attractiveness of fixed rates relative to current market conditions (searches/conversion rates).

Spot (Dynamic Pricing) Bookings

Prices can be dynamically adjusted within the week.

Weekly searches and conversion rates provide an initial market baseline.

Spot conversion rates dynamically respond to intra-week pricing adjustments, governed by clearly defined price elasticity:

Decreasing price → higher conversions (more bookings).

Increasing price → lower conversions (fewer bookings).

📈 Market Condition Evolution (Random Walk):
Weekly searches and conversion rates evolve based on a log-normal random walk, where each week’s level is built from the prior week’s value plus random fluctuation.

Allows for realistic, continuous evolution of demand signals.

⚖️ Market Price Concept:
Derived conceptually from spot rates and baseline market signals (searches & conversion).

Fixed-rate bookings adjust in volume based on market price attractiveness, but rates remain unchanged.

📊 Performance Measurement (Unchanged):
Revenue Efficiency

Inventory Utilization

Forecast Accuracy

Pricing Responsiveness

Combined into a clear final performance score (0-100).

🛠️ Implementation Approach:
Simulation clearly structured in Python notebook form.

Dynamic spot-rate pricing strategy responsive within each simulated week.

Accurate reflection of booking dynamics and intra-week pricing influence.

🏅 Learning Outcomes:
Understand the dynamics of fixed vs. spot bookings in response to evolving market conditions.

Build strong forecasting, inventory management, and pricing responsiveness skills.

Gain realistic, hands-on experience optimizing pricing strategies in volatile market environments.

