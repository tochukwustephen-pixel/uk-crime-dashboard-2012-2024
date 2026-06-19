# UK Crime Statistics Dashboard 2012–2024

## Project Overview
A complete data analytics project covering data cleaning, 
merging and visualization of UK recorded crime statistics 
from 2012 to 2024.

## Tools Used
- Microsoft Excel
- Power Query
- Microsoft Power BI

## What Was Done

### Data Cleaning & Merging (Excel + Power Query)
- Imported 12 annual crime sheets using Power Query
- Removed extra null columns generated during append
- Fixed Offence Code decimal corruption using custom formula
- Replaced null values with 0
- Removed duplicates and blank rows
- Merged all 12 sheets into one Master Table (254,428 rows)

### Visualization (Power BI)
- Built interactive dashboard with 4 KPI cards
- Line chart showing crime trend 2012–2024
- Bar chart showing offences by crime category
- Dropdown slicer for filtering by financial year

## Key Insights
| Metric | Value |
|---|---|
| Total records merged | 254,428 rows |
| Period covered | 2012/13 – 2023/24 |
| Highest crime year | 2022/23 (6,736,588 offences) |
| Most common crime group | Theft offences (18,176,213) |
| Grand total offences | 54,531,703 |

## Dashboard Preview
<img width="1920" height="1030" alt="dashboard_preview" src="https://github.com/user-attachments/assets/823afb2c-1f6c-4540-9c7b-0b014acabe72" />


## Files
| File | Description |
|---|---|
| `data/Mini Project Data Cleaning...xlsx` | Full cleaned and merged dataset |
| `powerbi/Crime_Dashboard.pbix` | Power BI dashboard file |
| `screenshots/dashboard_preview.png` | Dashboard screenshot |

## Skills Demonstrated
- Data cleaning and transformation
- Power Query (M language)
- Data merging across multiple sheets
- Power BI dashboard design
- KPI reporting and data storytelling
