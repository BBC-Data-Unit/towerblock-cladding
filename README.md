# Grenfell Tower: Unsafe cladding 'still affects thousands'

![](https://ichef.bbci.co.uk/news/624/cpsprodpb/D1D1/production/_104231735_highrise2-nc.png)

In November 2018 David Rhodes and Jonny McGuigan [reported](https://www.bbc.co.uk/news/uk-england-46103414) that thousands of people in England were still living in tower blocks with unsafe cladding more than a year after the Grenfell disaster.

The government has been publishing heavily redacted data for a year. David Rhodes looked at the [latest release](https://www.gov.uk/government/publications/building-safety-programme-monthly-data-release-end-october-2018) and found thousands of people were still living in buildings that were deemed unsafe, while 157 out of 457 affected buildings still had no clear plan in place to do anything about it.

We used R and ggplot2 to make the graphic.

## Get the data

* PDF: [Building Safety Programme: Monthly Data Release](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/754709/Building_Safety_Data_Release_endOctober_2018.pdf) ([cached](https://github.com/BBC-Data-Unit/towerblock-cladding/blob/master/Building_Safety_Data_Release_endOctober_2018.pdf))
* CSV: [Data on number of properties affected and remediation status](https://github.com/BBC-Data-Unit/towerblock-cladding/blob/master/acm2.csv)

## Quotes and interviews

* Nick Dugdale, resident, Skyline Apartments in Leeds
* Spokesperson, Liv Group
* Warren Smart, owner of a property in Saxton Parade, Leeds
* Spokesman, Residential Management Group (RMG), managing agent for Saxton Parade
* Hilary Benn, MP for Leeds Central
* James Brokenshire MP, Secretary of State for Housing, Communities and Local Government

## Visualisation

* Stacked bar chart: Status of high-rises with ACM cladding unlikely to meet building regulations (created using R and the ggplot package)


