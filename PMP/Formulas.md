# Formulas 

| Term                                        | Formula                                                     |
|---------------------------------------------|-------------------------------------------------------------|
| Budget at Completion (BAC)                  | Just the original budget. (an input to formulas)            |
| Planned Value (PV)                          | PV = Planned % Complete x BAC                               |
| Earned Value (EV)                           | EV = Actual % Complete x BAC                                |
| Actual Cost (AC)                            | The total amount already spent.  (an input to formulas)     |
| Cost Variance (CV)                          | CV = EV - AC                                                |
| Cost Performance Index (CPI)                | CPI = EV / AC                                               |
| Schedule Variance (SV)                      | SV = EV - PV                                                |
| Schedule Performance Index (SPI)            | SPI = EV / PV                                               |
| Estimate at Completion (EAC)                | EAC = BAC / CPI                                             |
| Estimate to Completion (ETC)                | ETC = EAC - AC                                              |
| Variance at Completion (VAC)                | VAC = BAC - EAC                                             |
| To-Complete Performance Index (TCPI)        | TCPI = (BAC - EV) / (BAC - AC)                              |
| PERT - Beta                                 | (Optimistic + 4 * Realistic + Pessimistic) / 6              |
| PERT - Standard Deviation                   | (Pessimistic - Optimistic) / 6                              |
| PERT - Triangular Distribution              | (Optimistic + Realistic + Pessimistic) / 3                  |
| Communications Channels                     | N(N-1)/2                                                    |

## Formula Purpose and Examples in Project Management:

These formulas are used in Earned Value Management (EVM) to track project progress, performance, and potential risks. Here's a breakdown:

### Inputs:

* **Budget at Completion (BAC):** This is the total project budget, a fixed value.
* **Actual Cost (AC):** This is the total amount of money spent on the project so far. 

### Calculated Values:

* **Planned Value (PV):** This represents the budgeted cost of work scheduled for completion by a specific date. 
  * **Example:**  Imagine a project with a BAC of $100,000 and planned to be 20% complete at the end of month 1. PV = 0.2 * $100,000 = $20,000 (budgeted cost for month 1).
* **Earned Value (EV):** This reflects the actual value of work completed, measured against the project schedule and budget. 
  * **Example:** If by the end of month 1, the project team completed tasks worth $25,000 according to the project plan, EV = $25,000.

### Performance Measurement:

* **Cost Variance (CV):**  This shows the difference between the earned value (what was accomplished) and the actual cost (what was spent). 
  * **Example:** CV = $25,000 (EV) - $22,000 (AC) = $3,000 (positive variance indicates project is under budget).
* **Cost Performance Index (CPI):** This is a ratio of earned value to actual cost, indicating how efficiently the project is using its budget.
  * **Example:** CPI = $25,000 (EV) / $22,000 (AC) = 1.14 (a CPI > 1 indicates good cost performance).
* **Schedule Variance (SV):** This shows the difference between the earned value (what was accomplished) and the planned value (what should have been accomplished).
  * **Example:** SV = $25,000 (EV) - $20,000 (PV) = $5,000 (positive variance indicates project is ahead of schedule).
* **Schedule Performance Index (SPI):** This is a ratio of earned value to planned value, indicating how well the project is adhering to the schedule.
  * **Example:** SPI = $25,000 (EV) / $20,000 (PV) = 1.25 (an SPI > 1 indicates project is ahead of schedule).

### Predictive Measures:

* **Estimate at Completion (EAC):** This forecasts the total project cost based on current performance (CPI).
  * **Example:** If CPI is 1.14 (as above), EAC = $100,000 (BAC) / 1.14 = $87,719 (predicted total cost).
* **Estimate to Completion (ETC):** This estimates the remaining amount needed to complete the project based on the EAC and actual cost spent.
  * **Example:** ETC = $87,719 (EAC) - $22,000 (AC) = $65,719 (predicted remaining cost).
* **Variance at Completion (VAC):** This predicts the difference between the original budget and the estimated total cost.
  * **Example:** VAC = $100,000 (BAC) - $87,719 (EAC) = $12,281 (predicted cost saving).

### Schedule Estimation (PERT):

**PERT Formulas for Task Duration Estimation:**

PERT (Program Evaluation and Review Technique) uses three formulas to estimate the most likely duration and potential variability of a project task. These estimates consider optimistic, pessimistic, and most likely scenarios.

**1. PERT - Beta (Optimistic + 4 * Realistic + Pessimistic) / 6**

* **Purpose:** This formula calculates the **expected duration** or **most likely time** a task will take to complete.
* **Example:** Imagine a development task has an optimistic time of 2 days, a pessimistic time of 10 days, and a realistic (most likely) time of 5 days. The expected duration would be: (2 + 4 * 5 + 10) / 6 = 7 days.

**2. PERT - Standard Deviation (Pessimistic - Optimistic) / 6**

* **Purpose:** This formula calculates the **standard deviation** of the possible task durations. It helps understand the potential variability in the task completion time. 
* **Example:** Using the same data as above, standard deviation = (10 - 2) / 6 = 2/3 days. This indicates a potential range of +/- 2/3 days around the expected duration of 7 days. 

**3. PERT - Triangular Distribution (Optimistic + Realistic + Pessimistic) / 3**

* **Purpose:** This is a simplified version of the Beta formula, providing a **rough estimate** of the expected duration. It assumes a symmetrical distribution of times between optimistic and pessimistic scenarios. 
* **Example:** Using the same data, expected duration = (2 + 5 + 10) / 3 = 5.67 days. This is close to the more accurate Beta calculation (7 days) but doesn't account for the weight given to the most likely time.

**Choosing the Right Formula:**

* The PERT - Beta formula is the most widely used and recommended for its accuracy in considering optimistic, pessimistic, and most likely scenarios.
* The standard deviation helps assess potential risks associated with task variability. 
* The Triangular Distribution can be a quicker estimate but may be less accurate. 

**Communication Channels:**

* **Communications Channels formula:** This calculates the number of unique communication channels needed in a team with N people. 
  * **Example:**  For a team of 5 (N = 5), there are N(N-1)/2 = 10 unique communication channels needed (e.g., emails, meetings) to ensure everyone stays informed. 