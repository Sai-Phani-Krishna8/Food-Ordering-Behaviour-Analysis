# Solution Architecture

## System Architecture

```
                   +----------------------+
                   |   CSV Dataset        |
                   +----------+-----------+
                              |
                              |
                              v
                +---------------------------+
                | Data Cleaning & Validation|
                +------------+--------------+
                             |
                             |
                             v
                +---------------------------+
                | Tableau Data Source       |
                +------------+--------------+
                             |
                             |
                             v
                +---------------------------+
                | Calculated Fields         |
                | Parameters                |
                | Filters                   |
                +------------+--------------+
                             |
                             |
                             v
                +---------------------------+
                | Interactive Dashboard     |
                +------------+--------------+
                             |
            -----------------------------------------
            |                    |                  |
            v                    v                  v
   Business Analyst      Operations Manager     Management
            |                    |                  |
            -----------------------------------------
                             |
                             v
                  Business Decisions
```

---

## Architecture Components

### Data Source

Food Ordering Behaviour Dataset stored in CSV format.

---

### Data Processing

- Data Cleaning
- Data Validation
- Data Transformation

---

### Tableau Layer

- Worksheets
- Parameters
- Filters
- Calculated Fields
- Dashboard

---

### Business Intelligence Layer

Provides interactive reports and visual insights for stakeholders.

---

### End Users

- Business Analyst
- Operations Manager
- Management Team

---

## Output

Interactive dashboard supporting business analysis and strategic decision-making.