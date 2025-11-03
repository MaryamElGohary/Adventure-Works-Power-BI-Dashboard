Data Source: https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver17&tabs=ssms

Storage connection mode : import



Data Modeling

Designed a star schema to structure the data model efficiently for reporting and analysis.

Created relationships between fact and dimension tables (e.g., Product, Customer, Date).

Defined inactive relationships between multiple date columns (such as Order Date, Ship Date, and Due Date) and the Date table to support flexible time-based analysis.




Data Transformations & DAX

Applied data cleaning and transformations in Power Query before modeling.

Used DAX functions such as USERELATIONSHIP() to activate inactive relationships dynamically for time-specific calculations (e.g., comparing Order Date vs. Ship Date metrics).

Implemented additional measures to calculate total sales, profit, and other KPIs.

Dashboard Features

Hierarchies and Drill Down: Created product hierarchies (Category → Subcategory → Product) and applied drill-down functionality in visuals such as the Tree Map for detailed exploration.

Tooltip Page: Added a custom tooltip page to display additional insights when hovering over visuals.

Drill Through Page: Implemented drill-through functionality to navigate from summary visuals to detailed report pages.

Interactive Filters and Slicers: Enabled users to filter data by region, product, and time period for customized analysis.



Tools & Technologies

-Power BI Desktop

-AdventureWorks Database

-DAX (Data Analysis Expressions)

-Power Query (M Language)
