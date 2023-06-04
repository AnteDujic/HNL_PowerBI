# Supersport HNL Dashboard

This repository contains a Power BI dashboard showcasing an overview of the Croatian Football League, Supersport HNL, for the 2022/23 season. The dashboard aims to provide a comprehensive overview of the league's player landscape, enabling users to analyze and gain insights into player demographics, team dynamics, and market values.

## Data Source

The data displayed in this Power BI dashboard is sourced from Transfermarkt, a popular football database and platform. A Python web scraper was used to extract the relevant data from Transfermarkt, including player numbers, profile images, names, positions, dates of birth, nationalities, heights, preferred foot, joining dates, previous clubs, contract details, market values, and current club affiliations.

 To learn more about the Python scraper project and access the source code, please refer to the following link: https://github.com/AnteDujic/TransfermarktScrap


## Repository Contents

- 'HNL.pbix' - The Power BI dashboard file
- 'SuperSportHNL.csv' - The dataset
- 'HNL_Notebook.ipynb' - The jupyter notebook
...

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository:
```bash
git clone https://github.com/AnteDujic/HNL_PowerBI.git
```
2. Open the `HNL.pbix` file in Power BI to explore and interact with the visualizations.
3. Alternatively, you can also access the dashboard by clicking: [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/AnteDujic/HNL_PowerBI/blob/main/HNL_Notebook.ipynb) or opening 'HNL_Notebook.ipynb' jupyter notebook.

### How to use

In the main section of the dashboard, you'll find essential overview statistics such as the total number of players, the percentage of foreign players, and the total value of players. It also includes visualizations like a pie chart comparing the market values of domestic and foreign players, a bar chart displaying player nationalities, and additional insights like the total player value by clubs, the top 5 most expensive players, average age, average value, and a plot showing the average value by age.

At the top of the dashboard, there is a title tile featuring the league's logo and emblems of all the clubs. These emblems are clickable, enabling you to filter the dashboard based on a specific club's data. Additionally, clicking on the league's logo takes you to the default dashboard, providing a comprehensive overview of the entire league.

To further interact with the dashboard, you can click on various features such as chart elements and data points. This allows you to drill down and explore specific aspects of the data. Moreover, you have the flexibility to drill down into the data by clicking on multiple elements simultaneously using the "Ctrl" key. This level of interactivity empowers you to customize your analysis, gain deeper insights, and tailor the dashboard to your specific interests and needs.

## Credits

- Transfermarkt (https://www.transfermarkt.com/)






https://nbviewer.org/github/AnteDujic/HNL_PowerBI/blob/main/HNL_Notebook.ipynb