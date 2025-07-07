# NCCarbonPlan

## Introduction
This spreadsheet estimates the cost impact of variations in natural gas prices and nuclear capital costs associated with capacity build plans developed by the NCUC Public Staff.

The information provided here is also included in the _README_ worksheet in the attached spreadsheet.

This spreadsheet is licensed under CC BY 4.0.

## Assumptions
1. We utilize the capacity buildout plans published by the Public Staff of the NC Utilities Commission
2. Wherever possible, we use assumptions drawn from the NCUC docket
3. Where key modeling assumptions are unpublished or redacted, we use non-proprietary sources of data

## Worksheet Descriptions
**_Main:_** Includes key assumptions and calculations. Near the top, green cells provide high-level results; tan cells provide key assumptions. Key calculations related to natural gas and nuclear capex begin on Row 21. Generation by technology type is estimated by multiplying installed capacity (drawn from the Public Staff build plans), technology-specific capacity factor, and hours in a year (8,760). Natural gas generation (Column J) is calculated as the difference between load and all other sources of generation (detailed formulation shown beginning in Cell J3). Estimated natural gas cost (Columns M-O) is calculated as the product of natural gas generation, heat rate, projected natural gas prices, and discount rate (detailed formulation shown beginning in Cell J6). Variation in nuclear capital costs (Columns P-R) are the product of new nuclear capacity (drawn from the Public Staff build plans), nuclear capital cost, and discount factor (detailed formulation shown beginning in Cell J10).

**Note 1:** The calculations above were repeated for two scenarios run by the Public Staff:  "PS 2034 Base" (interim target included) and "NCGA - Base" (interm target removed).

**Note 2:** The discount rate can be set in Cell G10.

**_Load_**: Projected DEP + DEC load. Source: [Docket E-100 Sub 190, Supplemental Planning Analysis, pgs 21-22](https://starw1.ncuc.gov/NCUC/ViewFile.aspx?Id=bfb12788-90ea-4352-97d6-3f3a7134b5ad).

**_Existing Capacity:_** Existing generation capacity. Source:[Docket F-E-20230817-090, Appendix B: DEC and DEP System Overview](https://starw1.ncuc.gov/NCUC/ViewFile.aspx?Id=b05e0100-1874-4db0-89f3-958afd4617ce).

**_PS - Relative Buildout:_** Capacity expansion plan provided by the Public Staff.

**_PS - Relative Buildout -- All Years:_** Capacity expansion plan provided only included select future years. In this sheet, changes in capacity are linearly interpreted to fill in the missing years.

**_Nuclear Capex:_** Projected nuclear capital costs under three different scenarios (Advanced, Moderate, Conservative) drawn from NREL's Annual Technology Baseline. We could not locate unredacted, publicly available nuclear capital cost numbers in the NCUC docket.
Projected NG Prices: Natural gas price projections included in the NCUC docket. Source: [Docket F-E-20230817-090, Appendix C: Quantitative Analysis, p. 44](https://starw1.ncuc.gov/NCUC/ViewFile.aspx?Id=0ef8dbf4-5fd9-4441-9110-b5d778e7437e). 

