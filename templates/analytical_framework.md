**Analytical Framework & Modeling Approach**

**Core Viability Model**

**Formula Implementation:**
- Teams Possible = FLOOR(Interested Count / Minimum Players Required, 1)
- Viability Decision = IF(Teams Possible ≥ 1, "Viable", "Not Viable")

**Excel Implementation with Actual Data:**

| Sporting Code | Interested Count | Min. Players Required | Teams Possible | Viable? | Decision |
|---------------|------------------|-----------------------|----------------|---------|----------|
| Football | 310 | 22 | =FLOOR(310/22,1) = 14 | Y | APPROVED |
| Netball | 288 | 14 | =FLOOR(288/14,1) = 20 | Y | APPROVED |
| Tug of War | 195 | 16 | =FLOOR(195/16,1) = 12 | Y | APPROVED |
| Relay | 182 | 8 | =FLOOR(182/8,1) = 22 | Y | APPROVED |
| Darts | 165 | 1 | =FLOOR(165/1,1) = 165 | Y | APPROVED |
| Cricket | 18 | 22 | =FLOOR(18/22,1) = 0 | N | REJECTED |
| Basketball | 7 | 10 | =FLOOR(7/10,1) = 0 | N | REJECTED |

**Key Excel Features Used:**
- FLOOR() function for team calculation (prevents fractional teams)
- Conditional formatting for visual indicators:
  - "APPROVED"/"REJECTED" = Green/Red fill
  - "Y"/"N" = Light green/light red fill
- Data validation for input constraints (ensures positive integers)
- PivotTables for departmental analysis and summary statistics
- IF() logical functions for viability determination

**Additional Features in Model:**
- Data bars/color scales for "Interested Count" visualization
- Summary statistics (total interested, approval rate, etc.)
- Dropdown selection for sporting codes (if applicable)
- Dynamic updating when input values change
