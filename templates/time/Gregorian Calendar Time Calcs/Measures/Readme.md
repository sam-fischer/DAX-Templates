# Templates in the Directory
## Fact AVG 1Y
### File 
Fact AVG 1Y.qdt.json
### Description
moving average over one year
### Support Links
https://www.daxpatterns.com/standard-time-related-calculations/#code62
## Fact AVG 30D
### File 
Fact AVG 30D.qdt.json
### Description
moving average over 30 days
### Support Links
https://www.daxpatterns.com/standard-time-related-calculations/#code59
## Fact AVG 3M
### File 
Fact AVG 3M.qdt.json
### Description
moving average over three months
### Support Links
https://www.daxpatterns.com/standard-time-related-calculations/#code61
## Fact Fiscal YTD
### File 
Fact Fiscal YTD.qdt.json
### Description
returning a Fiscal YTD result only when the ShowValueForDates measure returns TRUE
### Support Links
https://www.daxpatterns.com/standard-time-related-calculations/#code9
## Fact MAT
### File 
Fact MAT.qdt.json
### Description
Moving Annual Total
### Support Links
https://www.daxpatterns.com/standard-time-related-calculations/#code54
## Fact MTD
### File 
Fact MTD.qdt.json
### Description
returning the Month to Date result only when the ShowValueForDates measure returns TRUE
### Support Links
https://www.daxpatterns.com/standard-time-related-calculations/#code14
## Fact Period Growth Pct
### File 
Fact Period Growth Pct.qdt.json
### Description
Used to create period growth measures, i.e. YOY %, QOQ %, MOM %
### Support Links
https://www.daxpatterns.com/standard-time-related-calculations/#code18
## Fact Period Growth
### File 
Fact Period Growth.qdt.json
### Description
Used to create period growth measures, i.e. YOY, QOQ, MOM
### Support Links
https://www.daxpatterns.com/standard-time-related-calculations/#code17
## Fact PM
### File 
Fact PM.qdt.json
### Description
uses DATEADD and filters Date[DateWithSales] to guarantee a fair comparison of the last period with data.
### Support Links
https://www.daxpatterns.com/standard-time-related-calculations/#code23
## Fact PMC 
### File 
Fact PMC .qdt.json
### Description
Period Month Complete
### Support Links
https://www.daxpatterns.com/standard-time-related-calculations/#code50
## Fact PQ
### File 
Fact PQ.qdt.json
### Description
uses DATEADD and filters Date[DateWithSales] to guarantee a fair comparison of the last period with data.
### Support Links
https://www.daxpatterns.com/standard-time-related-calculations/#code20
## Fact PQC 
### File 
Fact PQC .qdt.json
### Description
Period Quarter Complete
### Support Links
https://www.daxpatterns.com/standard-time-related-calculations/#code46
## Fact PY
### File 
Fact PY.qdt.json
### Description
uses DATEADD and filters Date[DateWithSales] to guarantee a fair comparison of the last period with data.
### Support Links
https://www.daxpatterns.com/standard-time-related-calculations/#code16
## Fact PYC 
### File 
Fact PYC .qdt.json
### Description
Period Year Complete
### Support Links
https://www.daxpatterns.com/standard-time-related-calculations/#code39
## Fact QTD
### File 
Fact QTD.qdt.json
### Description
returning the Quarter to Date result only when the ShowValueForDates measure returns TRUE
### Support Links
https://www.daxpatterns.com/standard-time-related-calculations/#code12
## Fact YTD
### File 
Fact YTD.qdt.json
### Description
returning a result only when the ShowValueForDates measure returns TRUE
### Support Links
https://www.daxpatterns.com/standard-time-related-calculations/#code8
## POP Comparison Units
### File 
POP Comparison Units.qdt.json
### Description
Compares a base or aggregated measure in the current period, with the same measure in a previous, equivalent period, accounting for incomplete last periods.  For example, a year-over-year comparison between 2021 and 2020 where data only goes through November 2021, would only consider data from Jan - Nov 2020 when comparing with Jan - Nov 2021.  Enables user to make the comparison on a base measure (i.e. Sum of Sales) or any aggregation thereof (CYTD, FYTD or QTD of Sales) to look, for example, at YOY changes on a year/fiscal-year/quarter-to-date basis.
### Support Links
## PTD Aggregation
### File 
PTD Aggregation.qdt.json
### Description
Aggregates a base measure for a custom period-to-date (PTD) specified by the user.  This can be CYTD, FYTD, QTD or MTD.  The measure controls or hides values in future dates, for which there are no facts using a separate measure that the user should create (see Show Value for Dates template) and hide in their date table.
### Support Links
## Show Value for Dates
### File 
Show Value for Dates.qdt.json
### Description
A hidden measure in the DIM_Date in order to avoid showing results of time intelligence calculations in future dates
### Support Links
https://www.daxpatterns.com/standard-time-related-calculations/#code6
