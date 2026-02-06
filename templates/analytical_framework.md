# Analytical Framework & Modeling Approach

## Core Viability Model

### Formula Implementation:
Teams Possible = FLOOR(Interested Count / Minimum Players Required, 1)
Viability Decision = IF(Teams Possible ≥ 1, "Viable", "Not Viable")

### Excel Implementation Example:
| Sport | Interested | Min Players | Teams Possible | Viable? |
|-------|------------|-------------|----------------|---------|
| Football | 44 | 11 | =FLOOR(44/11,1) = 4 | Yes |
| Basketball | 7 | 5 | =FLOOR(7/5,1) = 1 | Yes |
| Cricket | 18 | 11 | =FLOOR(18/11,1) = 1 | Yes |
| Relay | 9 | 4 | =FLOOR(9/4,1) = 2 | Yes |
| Tennis Doubles | 3 | 4 | =FLOOR(3/4,1) = 0 | No |

### Key Excel Features Used:
- `FLOOR()` function for team calculation
- Conditional formatting for visual indicators
- Data validation for input constraints
- PivotTables for departmental analysis
