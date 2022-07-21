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
6. The three tables were then merged as one

![Screenshot 2022-07-21 112543](https://user-images.githubusercontent.com/107180803/180226030-8fa9c09c-c82d-477d-936a-e66fba3a165e.jpg)

![Screenshot 2022-07-21 113500](https://user-images.githubusercontent.com/107180803/180226418-b6045aa3-2da3-4c66-8f48-c36c95ceb827.jpg)


