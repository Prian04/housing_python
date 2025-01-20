# London Housing Analysis
This project involves analyzing London housing data using Python and key libraries like Pandas, Seaborn, and Matplotlib. The dataset was processed and analyzed to answer specific questions related to housing prices and crime rates. The following tasks were performed:

## Key Features:
**1) Data Cleaning and Transformation:**
- Converted the 'Date' column to datetime format.
- Extracted year and month values into separate columns.
- Removed unnecessary columns ('year', 'month') post-analysis.

**2) Exploratory Data Analysis:**
- Identified missing values using sns.heatmap and handled them effectively.
- Grouped and filtered data to calculate insights like:
- Maximum & minimum average prices per year in England.
- Maximum & minimum number of crimes recorded per area.
- Filtered records where the number of crimes is 0 and counted them.

**3) Additional Analysis:**
- Analyzed total records per area where the average price is less than 100,000.
- Created visualizations to better understand trends and distributions.

## Tools and Libraries:
- **Pandas:** For data manipulation and transformation.
- **Seaborn & Matplotlib:** For data visualization.
- **Jupyter Notebook:** For interactive coding and analysis.

## Commands Used:
Key Python commands included pd.read_csv, df.groupby(), sns.heatmap(), plt.show(), and more for data transformation and visualization.

This project demonstrates effective use of Python for data cleaning, analysis, and visualization to derive insights from the London housing dataset.

## Dataset:
The dataset used in this project is publicly available at [London Housing Dataset](https://datasciencelovers.graphy.com/products/64e0b8e6af71f92061d53206?dgps_u=l&dgps_s=ucpd&dgps_t=cp_u&dgps_u_st=u&dgps_uid=677cc155123d571a60231d72). Full credit goes to the original creator of the dataset.
