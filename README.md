### Creating an Interactive E-commerce Sales Dashboard: LUXELUME E-COMMERCE DASHBOARD in Power BI

Power BI is a powerful business intelligence tool that enables interactive data visualization and insightful analytics. In this project, I walked through the end-to-end process of building an interactive E-commerce Sales dashboard using Power BI Desktop and publishing it online.

### Data Gathering and Import

The first step was gathering relevant data and understanding business requirements. For this project, I used sample sales data for a fictional company, Luxelume, provided in Excel format. After installing Power BI Desktop, I imported the data by selecting the appropriate file type and loading the tables. This gave me a connected dataset to work with in Power BI.

### Data Transformation

With the raw data imported, I cleaned and transformed it to prepare for analysis. Key steps included:
- Renaming tables for clarity
- Removing unnecessary rows
- Promoting headers
- Unpivoting columns
- Splitting columns, such as names into first and last
- Merging columns, like first and last names
- Replacing text values
- Changing data types
- Filtering out unused data

These transformations shaped the data into an optimal form for visualization.

### Data Modeling

Next, I built relationships between the tables to create a star schema model. The core Fact table was the Sales table, which connected to supporting Dimension tables like Category, Customer, and State. I also created new calculated columns and measures using DAX to derive additional insights. Examples include a Total Profit column and a Sales Growth measure.

### Visualization and Reporting

With properly modeled data, I visualized it effectively by designing the E-commerce Sales Dashboard. Here are the main features:

#### Key Metrics
- **Sum of Amount:** $433K
- **Sum of Profit:** $37K
- **Sum of Quantity:** 5610 units
- **Average Order Value (AOV):** $120K

#### Detailed Insights
- **Profit by State:** 
  - Highlights top-performing states like Madhya Pradesh, Maharashtra, Uttar Pradesh, Gujarat, and Tamil Nadu.
- **Sales Quantity by Payment Mode:** 
  - Visualizes distribution with 44% via Credit Card, 21% via Debit Card, 13% via Net Banking, and 12% via Cash on Delivery.
- **Monthly Profit Trends:** 
  - Shows profit spikes in June and November.
- **Customer Sales Analysis:** 
  - Identifies top customers such as Hadya, Meda, Shiva, and Vedika.
- **Category-wise Quantity Sold:** 
  - Dominated by Electronics (63%), followed by Apparel (21%) and Home Goods (17%).
- **State-wise Sales Amount:** 
  - Maharashtra leads, followed by Madhya Pradesh, Uttar Pradesh, and Rajasthan.

### Publishing and Sharing

Once the reports were finished, I published them to the Power BI cloud service. This allowed sharing interactive dashboards via links and enabled data refresh.

### Key Benefits
- **Interactive visualization:** Uncovers data insights
- **Modeling:** Enhances analysis
- **Powerful DAX calculations**
- **Flexible publishing and sharing**
- **Real-time data refresh**
- **Mobile-friendly dashboards**

By mastering this end-to-end process, Power BI can be leveraged to create insightful, impactful data models tailored to any business need.

![Dashboard Screenshot](https://raw.githubusercontent.com/Ayushi-sengupta/PowerBi_E-Commerce_DashBoard/main/dashboard.jpg)

Feel free to explore, fork, and contribute to this repository! 📊✨
