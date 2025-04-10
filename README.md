# OPTIMIZATION-MODEL

COMPANY: CODTECH IT SOLUTIONS

NAME: Vansh Raina

INTERN ID: CT08WQF

DOMAIN: DATA SCIENCE DEVELOPMENT

DURATION: 4 WEEEKS

"MENTOR*: NEELA SANTOSH

# -Description
This project focuses on solving a real-world business optimization problem in the furniture manufacturing industry using Linear Programming (LP). The core objective is to help a furniture company determine the optimal number of products—chairs, tables, and desks—to produce in order to maximize profit, while adhering to constraints on available wood and labor hours. The solution is implemented using the PuLP library in Python, a popular tool for modeling and solving LP problems.

Problem Formulation
The company produces three types of furniture: chairs, tables, and desks. Each of these products requires a certain amount of wood and labor. For instance, a chair may require less material and labor compared to a desk, but the profit margins for each item also differ. With limited raw materials and a fixed number of labor hours available per day, the challenge is to find the most profitable production combination.

To solve this, the problem is formulated as a Linear Programming model. The decision variables represent the number of each type of furniture item to produce. The objective function is to maximize total profit, which is the sum of profits from all items. The constraints include limitations on wood and labor usage, which are modeled as inequalities based on available resources.

# -Mathematical Model
Let:

x = number of chairs produced

y = number of tables produced

z = number of desks produced

Then, the LP model includes:

Objective Function: Maximize Profit = p1*x + p2*y + p3*z
(where p1, p2, and p3 are profit margins for chairs, tables, and desks respectively)

Constraints:

Wood constraint: w1*x + w2*y + w3*z ≤ total_wood

Labor constraint: l1*x + l2*y + l3*z ≤ total_labor

Non-negativity: x, y, z ≥ 0

# -Implementation Using PuLP
The model is implemented using PuLP, which allows for defining LP problems with a high-level syntax. After specifying the objective and constraints, the model is solved using an LP solver (like the default CBC solver provided by PuLP). The output gives the optimal number of chairs, tables, and desks to produce for maximum profit.

Insights
Upon solving the model, the program displays:

The optimal production quantities for each product

The maximum achievable profit under current constraints

Whether all resources are fully utilized or if there’s leftover capacity

This provides actionable insights for business decision-making. For instance, if labor is fully used but wood isn’t, the company might consider hiring more workers to increase profit further.

Applications
This project has broad applications in operations research, supply chain management, and strategic planning. The approach can be scaled and adapted to other manufacturing scenarios, such as optimizing production schedules, raw material purchases, or delivery logistics.

# -OUTPUT
