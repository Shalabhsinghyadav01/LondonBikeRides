# London Bike Rides Analysis

## Project Overview

This project involves analyzing bike ride data in London to uncover insights about bike usage patterns, trends, and other key metrics. The analysis was performed using various tools and data sources, including a Tableau workbook, Jupyter Notebook, and data files in different formats.
## Table of Contents

- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Data Sources](#data-sources)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Tableau Dashboard Details](#tableau-dashboard-details)
- [Key Findings](#key-findings)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)
- [Contact](#Contact)
## Project Structure
The project repository contains the following files and directories:

- `london_bike_rides.ipynb`: Jupyter Notebook containing the analysis code and visualizations.
- `London Bike Rides.twbx`: Tableau workbook with visualizations and dashboards.
- `london_bike_rides.xlsx`: Excel file with bike ride data.
- `london_merged.csv`: Merged CSV file with comprehensive bike ride data.
- `bikes_data (london_bike_rides).hyper`: Hyper file used in Tableau.
- `london-bike-sharing-dataset.zip`: Compressed dataset used for the analysis.
## Data Sources

The data for this project was collected from multiple sources and merged to provide a comprehensive view of bike rides in London. The main data sources include:

- Historical bike ride data in CSV format.
- Supplementary data files in Excel and Hyper formats.
- Compressed dataset containing additional details about the bike rides.## Installation and Setup

To run the analysis, you need to set up your local environment. Follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/Shalabhsinghyadav01/LondonBikeRides
    ```

2. **Set up a virtual environment** (optional but recommended):
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required Python packages**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Open the Jupyter Notebook**:
    ```sh
    jupyter notebook london_bike_rides.ipynb
    ```

5. **Explore the Tableau workbook**:
    - Open `London Bike Rides.twbx` in Tableau Desktop to view the visualizations.
## Usage

### Jupyter Notebook

The Jupyter Notebook `london_bike_rides.ipynb` contains the data analysis and visualizations. You can run the notebook cells to reproduce the analysis or modify the code to explore additional insights.

### Tableau Workbook

The Tableau workbook `London Bike Rides.twbx` provides interactive dashboards and visualizations. You can filter the data, drill down into specific metrics, and gain insights through the visual interface.
## Tableau Dashboard Details

The Tableau dashboard includes several interactive features and operations designed to provide a comprehensive analysis of bike ride data in London. Below are the key components and their functionalities:

1. **Overview Dashboard**:
    - **Total Rides**: Displays the total number of bike rides over the selected period.
    - **Heat Map**: A heat map showing the density of bike rides across different areas in London. Interactive features allow users to zoom in and out and hover over specific areas to see detailed ride counts.
    - **Time Series Analysis**: A line chart depicting the number of rides over time. Users can filter the data by date ranges to analyze trends during specific periods.

2. **Peak Usage Times**:
    - **Hour of the Day**: Bar chart showing the distribution of bike rides by the hour of the day. This helps identify peak usage times, such as morning and evening rush hours.
    - **Day of the Week**: Bar chart showing the distribution of bike rides by the day of the week. Users can see which days have the highest and lowest bike usage.

3. **Popular Routes**:
    - **Route Map**: An interactive map highlighting the most popular bike routes in London. Users can click on different routes to see detailed statistics such as average ride duration, total rides, and more.
    - **Route Details**: A table listing the top routes with metrics like total rides, average speed, and distance.

4. **Weather Impact**:
    - **Weather Correlation**: Scatter plot showing the correlation between weather conditions and bike usage. Filters allow users to select specific weather types (e.g., sunny, rainy) to see how they affect ride counts.
    - **Weather Breakdown**: Pie chart or bar chart breaking down bike rides by different weather conditions.

5. **User Demographics**:
    - **Age Distribution**: Histogram showing the distribution of riders' ages.
    - **Gender Breakdown**: Pie chart showing the proportion of rides by gender.
    - **Subscription Type**: Bar chart displaying the number of rides by subscription type (e.g., annual members, casual riders).

6. **Custom Filters and Interactive Elements**:
    - **Date Range Selector**: Allows users to filter data by specific date ranges.
    - **Dropdown Filters**: Users can filter data by various dimensions such as station names, rider types, weather conditions, and more.
    - **Tooltips**: Hovering over data points provides additional details and context.

These interactive features make it easy to explore the data, identify patterns, and gain actionable insights. Users can customize their view and focus on the metrics that matter most to them.

### Link to Tableau Dashboard

You can explore the interactive Tableau dashboard by following this [link to the Tableau Dashboard](https://public.tableau.com/app/profile/shalabh.yadav/viz/LondonBikeRides_17229416611690/Dashboard1).
## Key Findings

Here are some of the key findings from the analysis:

- **Peak Usage Times**: The data shows that bike usage peaks during morning and evening rush hours, indicating a high number of commuters.
- **Popular Routes**: Certain routes are more popular, suggesting key areas of interest and commuter paths in London.
- **Weather Impact**: Weather conditions have a significant impact on bike usage, with fewer rides on rainy days.
## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
## Acknowledgements

- Thanks to the open data sources that provided the bike ride data.
- Special thanks to the developers and contributors of the tools and libraries used in this project.


## Contact
If you have any questions or want to discuss the project, feel free to reach out:
- **Name**: Shalabh Singh Yadav
- **Email**: [shalabhsinghyadav@gmail.com](mailto:shalabhsinghyadav@gmail.com)
- **LinkedIn**: [LinkedIn Profile](https://www.linkedin.com/in/shalabh-singh-yadav-66b607204/)