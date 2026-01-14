# Water Flow Optimization System

## Overview
This project implements a **Python-based water flow optimization system** that models the efficient distribution of limited water resources to multiple demand points under real-world constraints such as **capacity limits, priority levels, and leakages**.

The system simulates how water can be dynamically allocated and reallocated from multiple sources to meet demand while minimizing wastage and ensuring high-priority areas are served first.

---

## Problem Statement
Water scarcity and inefficient distribution lead to wastage, inequitable access, and environmental stress.  
This project addresses the challenge by:
- Optimizing water flow across predefined paths
- Prioritizing critical demand points
- Detecting leakages and redistributing water dynamically

---

## Key Features
- Priority-based water allocation  
- Capacity-constrained flow paths  
- Leakage detection and exclusion of faulty paths  
- Dynamic redistribution to meet unmet demands  
- Modular and extensible Python implementation  

---

## System Model

### Water Sources
- 5 water sources with limited availability

### Demand Points
- 10 demand points
- Each demand has:
  - Required water quantity
  - Priority level (1 = highest priority)

### Flow Paths
- 18 predefined paths
- Each path has:
  - Capacity constraint
  - Leakage detection flag

---

## Algorithmic Paradigms Used
- **Search**: Identifying feasible paths for water allocation  
- **Decision Making**: Priority-based allocation and redistribution  
- **Optimization**: Maximizing demand satisfaction under constraints  
- **Organization**: Efficient data handling using dictionaries and lists  

---

## Core Components

### Allocation
- Initial water allocation based on **priority and path capacity**

### Leakage Handling
- Detects discrepancies between allocated and received water
- Excludes leaked paths and reallocates water through alternatives

### Optimization Loop
- Reallocates remaining water until:
  - All demands are satisfied, or
  - No further feasible allocation is possible

---

## Technologies Used
- **Python**
- Data Structures (Dictionaries, Lists)
- Custom Sorting (Insertion Sort)

---


