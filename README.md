## Yearly Production Dashboard

### Overview
This report tracks written premium for new business and renewals across business units, states, and policy years, giving stakeholders a fast, flexible picture of production performance from either a geographic or tabular view.

### Business Value
Insurance production data is only useful if the right people can slice it the right way, quickly. This report solves that by letting users toggle between two complementary views:

- **Map View** — A choropleth map of the U.S. lets users visually scan production by state at a glance. Hovering over any state surfaces a detailed tooltip breaking down new, renewal, and total premium by business unit — turning a simple geographic overview into a drill-down tool without ever leaving the page.

- **Table View** — A cross-tabulated summary shows new, renewal, and total premium by business unit across multiple policy years side-by-side, making trend analysis and year-over-year comparisons straightforward.

Both views share the same filter panel (Business Unit, Policy Year, State), so users can narrow in on a specific segment — say, renewal performance for two business units in Texas and Florida over the last two years — and get the answer immediately, rather than exporting data to Excel and building it manually.

### Who It's For
Executives and underwriting leaders who need to monitor growth by business unit and geography, identify which states or lines are driving new business versus retention, and support portfolio and territory planning decisions.

### Key Features
- Interactive map and table toggle for geographic vs. tabular analysis
- Drill-down tooltips showing business-unit-level premium detail by state
- Multi-select filters for Business Unit, Policy Year, and State
- Side-by-side New / Renewal / Total premium breakdown across years

### Viz Skills Demonstrated
Interactive map visualizations, custom tooltips, view toggling (bookmarks), multi-select slicers, matrix/table formatting

### Tech Stack
SQL, Excel, Office Scripts, Python, Power Query, Power BI, DAX

### Data Source
A fictional dataset I created to populate a simplified version of one of the semantic models I designed to serve as a core central model to be used by several reports.

The .pbix file of all the dashboards shown in this portfolio combined into one report is included in the [Semantic-Model-and-Data-Dictionary](https://github.com/Jodi-Schreiner/Semantic-Model-and-Data-Dictionary) repository.  In practice, many reports are built on the shared core semantic models then grouped into apps by use case for distribution.
<br><br><br>
*Yearly production map with tooltip containing business unit detail*
<br><br>
<img width="666" height="428" alt="Yearly-Production-Map" src="https://github.com/user-attachments/assets/fabc2e99-aaa6-44ff-a4e9-21b0624ff8dc" />
<br><br><br>
*Yearly production table showing multiple years of premium*
<br><br>
<img width="666" height="430" alt="Yearly-Production-Table" src="https://github.com/user-attachments/assets/ae5ae5f5-6c16-4ef0-b84b-da88de468e85" />

