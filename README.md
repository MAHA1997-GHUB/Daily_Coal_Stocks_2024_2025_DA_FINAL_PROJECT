# <img width="50" height="50" alt="project title" src="https://github.com/user-attachments/assets/4caf0881-a47f-4b7d-ae80-34fb5cb10d02" /> Analysis of Daily Coal Stock Monitoring in Indian Power Plants
The dataset used in this project consist of daily coal stock records from thermal power stations across india between 2024-2025. Its provides detailed information at the state, sector, and individual station level, capturing both operational and logistical aspects of coal supply.
## <img width="50" height="50" alt="Dashboard" src="https://github.com/user-attachments/assets/a7b3e70f-0f0a-49a0-9b28-c74344f7548c" />Dashboard
## <img width="1315" height="549" alt="Dashboard 1" src="https://github.com/user-attachments/assets/bae79b0c-660c-4b2e-b70e-28c308c64dc6" />
## <img width="1315" height="549" alt="Dashboard 2" src="https://github.com/user-attachments/assets/c52b9e9b-1dc2-4a20-9770-a2b95ce84130" />
## <img width="1315" height="549" alt="Dashboard 3" src="https://github.com/user-attachments/assets/db1cbc4a-9c00-4ebd-9cb8-503f1f0faa1f" />
## <img width="50" height="50" alt="Project Objective" src="https://github.com/user-attachments/assets/81660f6d-41c9-4cc4-8275-2997a09b7c25" /> Objective
The objective of this analysis is to provide a comprehensive view of Daily Coal Stock data from thermal power stations across India. It **aims to evaluate coal supply, receipts, consumption, and stock adequacy at the state, sector, and station levels,** while identifying patterns, trends, and critical conditions that affect plant load factor and energy security. The study will **generate clear visual reports and actionable recommendations to improve coal logistics** strengthen stock management, and support informed policy decisions for reliable energy planning.
## <img width="50" height="50" alt="scope" src="https://github.com/user-attachments/assets/a8560331-9524-4f10-8558-e1c549fc12f4" /> Scope
1)	A **cleaned and well structured** dataset prepared for robust analysis.
2)	**Clear Identification of patterns and trends** in coal stock adequacy versus normative requirements, highlighting critical plants and supply gaps.
3)	**Visualizations that effectively communicate** state - level differences and highlight key operational insights.
4)	**Evidence based recommendations** to strengthen coal logistics, stock management, and overall energy security.
5)	**Comprehensive Analytical Report (Python Scripts, PowerBI)** connecting technical findings to future research and policy in India’s power sector.
## <img width="50" height="50" alt="domain" src="https://github.com/user-attachments/assets/c4759c65-6091-4223-9bb3-42a6b7138c27" /> Domain
This project falls within the **energy analytics domain,** focusing on daily coal stock monitoring for thermal power stations across India. The domain emphasizes operational efficiency, logistics management, and policy support, connecting technical analysis with broader goals of energy security and sustainable power sector planning.
## <img width="50" height="50" alt="information" src="https://github.com/user-attachments/assets/830eaff1-b18a-460e-8416-6ea4bd96c4e9" /> Dataset Information
- **Size** : 79000+
- **Timeline**: 2024-2025.
- **Description**: The dataset used in this project consist of daily coal stock records from thermal power stations across India Between 2024-2025. It provides detailed information at the state, sector, and individual station level, capturing both operational and logistical aspects of coal supply. This dataset offers a comprehensive view of granularity at the station level makes it highly suitable for exploratory data analysis, visualization, and AI-Driven modelling, uncovering actionable insights for power sector reliability, logistics optimization, and policy decision making.
- **Dataset Columns** : 22 columns(id, date, state_name, state_code, power_station_name, sector, utility, mode_of_transport, capacity_of_power_station, daily_requirement_tonnes, daily_receipt_tonnes, daily_consumption_tonnes, req_normative_stock_tonnes, req_normative_stock_days, indigenous_stock_tonnes, import_stock_tonnes, total_stock_tonnes, stock_days, plf_prcnt, actual_vs_normative_stock_prcnt, is_critical, remarks)
## <img width="50" height="50" alt="Step by step" src="https://github.com/user-attachments/assets/f3a3f852-8d51-4b87-8829-f7987adeda8b" /> Step by Step Explanation of the Project
#### Stage 1: Loading the Dataset and Initial EDA:
- Initially I do EDA using Python code like,
- df
- df.describe()
- df.head()
- df.tail()
- df.columns
- df.info()
- df.shape
- df.isnull().sum()
#### Stage 2 : Data Cleaning and Pre-Processing:
- A structured and reliable dataset was developed through rigorous cleaning and advanced imputation methods, ensuring accuracy and readiness for impactful visualization and decision-making.
#### Stage 3 : Dashboard Creation:
- An integrated Power BI dashboard was created, combining diverse chart types to deliver clear, actionable insights through interactive visualization.
## <img width="50" height="50" alt="key findings" src="https://github.com/user-attachments/assets/a63ab693-74b9-4f1a-a854-8512c9cd9f36" /> Key Findings
- **Critical vs Non-Critical Plants:** Critical plants consistently show fewer stock days, making them vulnerable to outages.
- **Transport Dependency:** Rail transport sustains longer stock days compared to road, highlighting logistics bottlenecks.
- **Efficiency Link:** Plants with lower stock days often show reduced PLF%, meaning coal shortages directly affect generation efficiency.
- **Regional Variations:** Certain states (e.g., with higher private sector share) show more frequent shortages.
- **Correlation Patterns:** Strong positive correlation between receipts and total stock; weak correlation between PLF% and normative stock.
## <img width="50" height="50" alt="insights" src="https://github.com/user-attachments/assets/f713bd1e-812e-4c43-81af-1ef5b06f7ffb" /> Key Insights
- **Stock Days Trend:** Non-critical plants maintain healthier reserves, while critical plants hover dangerously close to outages.
- **Transport Bottleneck:** Dependence on rail transport is evident; plants relying on road transport face shorter stock days.
- **Efficiency Drop:** PLF% declines sharply when stock days fall below normative levels.
- **Sectorial Risk:** Private sector plants show higher volatility in stock availability compared to central utilities.
- **Regional Clusters:** Some states consistently underperform in maintaining normative stock levels.
## <img width="50" height="50" alt="REcommentaion" src="https://github.com/user-attachments/assets/e2ace47d-a822-4cd5-b269-4d9d80c7bba0" /> Business Recommentations
- **Diversify Transport:** Reduce reliance on road transport by strengthening rail and port logistics.
- **Policy Intervention:** Prioritize coal allocation to critical plants with consistently low stock days.
- **Operational Planning:** Use PLF% vs stock analysis to schedule preventive maintenance during shortage periods.
- **Regional Strategy:** Focus on vulnerable states with repeated shortages for targeted support.
- **Dashboard Adoption:** Encourage utilities to adopt this Power BI dashboard for real-time monitoring.
## <img width="50" height="50" alt="final story" src="https://github.com/user-attachments/assets/13e8a1d2-7ea7-438a-9e26-0f082fbb4195" /> Final Story
**Dashboard tells a clear narrative:**
- **Macro View:** National coal resilience trends (stock days, criticality).
- **Micro View:** Plant-level vulnerabilities ( boxplots).
- **Multivariate View:** Systemic dependencies (correlation heat map, pair plot).
- **Hierarchical View:** Sector → Transport → Requirement breakdown (sunburst, tree map).
- **Various Power Bi Visuals:** Card Visuals, KPIs, Slicers, Bar Plot, Area Chart etc.,
**Together, these visuals show how coal logistics, sectorial differences, and stock management directly impact energy reliability. The story ends with actionable recommendations for policy makers, utilities, and transport planners.**
## <img width="50" height="50" alt="Links" src="https://github.com/user-attachments/assets/e5a85f44-419f-4709-8264-9e563def4f69" /> Links
- **Source:** [India Data Portal](https://indiadataportal.com/p/power/r/mop-coal_stock-pl-dl-aaa)
- **Raw Dataset:** [Daily Coal Stock Raw Data](https://drive.google.com/file/d/1PUM8LNxFq92jTrQZKJfsUqvImIBgHX6D/view?usp=sharing)
- **Cleaned Dataset:** [Daily Coal Stock Cleaned Data](https://drive.google.com/file/d/1kmhQwXAxI8eQdDgy8QfT-mryBv7ynSMj/view?usp=sharing)
- **Google Colab Link:** [Google Colab](https://colab.research.google.com/drive/1sWmuETrOvQ3aYSrezDeesgSZyJBzfz3N)
- **PowerBI Dashboard PDF Link:** [Power BI PDF](https://drive.google.com/file/d/14TIRJNxPDm57l51AAPXeWG096faoUApw/view?usp=drive_link)
- **Power Point Presentation Link:** [PPT](https://drive.google.com/file/d/1t3xFqWlGKnGJXLjYMmEzjcVJsG-5sRh9/view?usp=drive_link)
## <img width="50" height="50" alt="conclusiion" src="https://github.com/user-attachments/assets/e2aad36a-f28d-4e33-8ffe-57fd31846ff6" /> Conclusion
Overall, this project demonstrates the value of combining data cleaning, advanced visualization, and interactive dashboards to transform raw records into actionable insights. The final story underscores the importance of proactive monitoring, diversified transport strategies, and targeted policy support to strengthen energy security and ensure uninterrupted power generation.
#### Author
M.Mahalakshmi
