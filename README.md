# Supplier-Evalution-and-Order-Optimization-Using-DP

This project is a decision-making tool designed to help businesses evaluate suppliers and optimize purchase orders based on multi-criteria decision analysis and demand scenarios. The application uses **Streamlit** for an interactive user interface and incorporates the **Analytic Hierarchy Process (AHP)** and dynamic programming to provide optimal order quantities and supplier selection.

---

## Features

1. **Supplier Evaluation**:
   - Rate suppliers on key criteria: Price, Quality, Delivery, and Environmental Impact.
   - Calculate AHP weights for each criterion to determine supplier scores.

2. **Order Optimization**:
   - Optimize orders across multiple periods based on supplier capacity, demand scenarios, and inventory constraints.
   - Calculate Total Value of Purchase (TVP) and Total Profit of Purchase (TPP) to assess the value of each decision.

3. **Dynamic Programming**:
   - Use dynamic programming to track the best order combinations for each period, taking inventory and shortages into account.

4. **Interactive User Interface**:
   - Streamlit-powered sliders and input fields for seamless data entry.
   - Instant visualization of optimal orders and values for each period.

---

### Prerequisites

- Python 3.8 or above
- Libraries: `numpy`, `streamlit`

