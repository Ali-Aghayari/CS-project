
# **Queue Simulation Model**

This repository contains a queue simulation system for modeling interactions between employees and customers in a service environment. Employees are categorized based on their roles, and customers are queued for service following defined policies. The project analyzes system performance using key metrics such as queue lengths, service times, and wait times, complemented by visualizations.

---

## **Features**
- **Employee Categorization**:
  - Employees are grouped into three categories (`A`, `B`, `C`), each with unique roles and service times.
- **Queue Management Policies**:
  - Implements both FIFO (First In First Out) and SPT (Shortest Processing Time) policies.
- **Customer Simulation**:
  - Models customer arrivals and service interactions.
- **Performance Metrics**:
  - Queue lengths (`L` and `LQ`).
  - Service times (`Si`).
  - Wait times (`W` and `WQ`).
  - Employee task distribution.
- **Visualizations**:
  - Pie charts for task distribution.
  - Line graphs for queue length, wait times, and service metrics.

---

## **Key Sections in the Notebook**
1. **Employees**: Defines roles and responsibilities for each employee category.
2. **Customers**: Simulates customer interactions and queuing behavior.
3. **Simulation**:
   - **Arrival Intervals (`Ai`)**: Time between consecutive customer arrivals.
   - **Service Times (`Si`)**: Duration for serving each customer.
   - **Queue Lengths (`L` and `LQ`)**: Number of customers in the system and queue.
   - **Wait Times (`W` and `WQ`)**: Total wait time and queue delay for customers.
4. **Visualization**:
   - Generates pie charts for employee workload distribution.
   - Plots line graphs to analyze system performance over time.

---

## **Libraries Used**
- **Core Libraries**:
  - `numpy`
  - `random`
- **Visualization**:
  - `matplotlib.pyplot`
  - `seaborn`
- **Additional Modules**:
  - `norm`
  - `Counter`
  - `filterfalse`

---

## **Simulation Output**
- **Numerical Metrics**:
  - Average queue lengths and wait times.
  - Service time statistics.
- **Visualizations**:
  - Pie charts for task distributions across employees.
  - Line graphs showing queue lengths and service times over time.

---
