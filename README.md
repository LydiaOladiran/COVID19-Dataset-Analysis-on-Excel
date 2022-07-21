# Introduction
Coronavirus disease (COVID-19) is an infectious disease caused by the SARS-CoV-2 virus of which high fatality was recorded all around the world. This project aims at analyzing the level of containment of the disease.

# Data sourcing
The dataset used for this analysis was gotten from https://github.com/CSSEGISandData/COVID-19. The data was imported into Microsoft Excel using the URL of the web page.

# Data cleaning and Transformation
Data cleaning was done using Power Query editor in Microsoft Excel. Some transformation steps were applied to the data so that it would be suitable for analysis,
1. Settings was done on the data source so that the data would continiously update realtime
2. All first rows were promoted to headers.
3. The date columns were unpivoted from wide (wide data grows bigger in columns and can have more columns than row) so that they can be stacked in a way that it can be easily analysed
4. The new columns were appropriately renamned and the data types were changed.
5. Next, the global deaths and global recovery datasets were similarly imported and same transformations applied to them.
