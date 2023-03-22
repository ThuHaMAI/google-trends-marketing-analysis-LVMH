# Google Trends for a Time Series Marketing Analysis: the LVMH case

This project illustrates the use of Google Trends data to extract brand search volume, either to assess advertising or predict sales. The choice of different LVMH brands as the data set of interest for this study was influenced by several factors, which were discussed in the attached report.

The remainder of the attached report is organized as follows. Section 2 introduces the characteristics of Google Trends data and the overall process of data collection. Section 3 then focuses on outliers detection and treatment, which is one of the most difficult parts of time series data preprocessing, and the outliers’ possible explanations based on real events. Section 4 concentrates entirely on clustering techniques, algorithms and results while section 5 is dedicated to the forecast application and evaluation for each series and clustering. The report concludes in Section 6 by pointing out the key marketing insights given in our analyses.

The dataset used for the analysis contains the Google Trends Interest Over Time of:
- Different brands of LVMH
- Various categories/ business groups: perfumes and cosmetics, fashion and leather goods, wines and spirits
  - Perfumes and Cosmetics: ’Sephora’, ’Make Up For Ever’, ’Benefit Cosmetics’, ’Fenty Beauty’, ’Guerlain’
  - Fashion and Leather goods: ’Louis Vuitton’, ’Christian Dior, S. A.’, ’Givenchy’, ’Marc Jacobs’, ’Kenzo’, ’Loewe’, ’Fendi’, ’Celine’
  - Wines and Spirits: ’Dom P´erignon’, ’Veuve Clicquot Ponsardin’, ’Chandon’, ’Ruinart’, ’Chateau Cheval Blanc’, ’Hennessy’, ’Mo¨et Chandon’
- In a timeframe of 5 years from 27th November 2017 to 27th November 2022
- In different countries: USA, France, Japan since these are the three most prominent markets
of LVMH worldwide
