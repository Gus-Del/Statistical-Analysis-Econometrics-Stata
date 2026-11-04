# Workers’ Compensation Injury Claims

**Question:** What factors are associated with the duration of benefits, medical costs, and benefit amounts in workers’ compensation claims?

**Data:** Injury claim observations including duration of benefits, previous wage, total medical costs, injury type, body part injured, industry, and state (Kentucky vs Michigan).

**Methods:** Summary statistics, data cleaning, tabulations by state, and exploration of high-cost claims.

**Key variables:**  
- `durat` — duration of benefits  
- `prewage` — previous weekly wage  
- `totmed` — total medical costs  
- `benefit` — benefit amount  
- `ky` — Kentucky indicator  
- `age` — age at injury  
- Injury-type and body-part indicators (`head`, `neck`, `trunk`, `lowback`, etc.)  

**Output:** Stata log with descriptive statistics, by-state summaries, and data-cleaning steps.
