# Power BI Project: Hotel Business Analytics Dashboard 📊

## Overview 📋
This Power BI project (.pbix) delivers an interactive analytics dashboard for a comprehensive hotel business dataset. The project analyzes key metrics such as Average Daily Rate (ADR), Revenue Per Available Room (RevPAR), and occupancy rates to drive data-informed decisions on room pricing, staffing, and marketing strategies. The .pbix file encapsulates the report and data model, providing a self-contained solution for data visualization and analysis.

The project showcases expertise in data loading, transformation, star schema modeling, DAX calculations, and dashboard visualization using Power BI Desktop.

![Dashboard Screenshot][https://github.com/Wuodmadam/Hotel-dashboard-with-power-BI/blob/master/bi%20dashboard.png]

## Features 🚀
- **Data Loading and Transformation** 🗂️: Ingests and cleans multiple CSV files, including `dim_date`, `dim_rooms`, `fact_bookings`, and additional tables, with duplicate removal and data preprocessing.
- **Data Model** 🛠️: Implements a star schema with dimension tables (e.g., `dim_date`, `dim_rooms`, and others) and a central fact table (`fact_bookings`) for efficient relationships.
- **DAX Calculations** 📈: Includes custom measures for key metrics like ADR, RevPAR, and occupancy rates.
- **Interactive Dashboard** 🖼️: Visualizes actionable insights to optimize hotel revenue and guest satisfaction.

![Star Schema Diagram][INSERT_IMAGE_LINK_HERE_2]

## Prerequisites ✅
To work with this project, ensure you have the following:
- **Power BI Desktop** 💻: Version December 2024 or later.
- **Access to Data Sources** 📂: CSV files (e.g., `dim_date.csv`, `dim_rooms.csv`, `fact_bookings.csv`, and additional dataset files) stored locally or in a synced folder.
- **Version Control (Optional)** 🌐: Git for tracking changes in a repository (if managing source data or documentation).
- **Text Editor (Optional)** ✍️: For editing source CSV files (e.g., VS Code), ensuring UTF-8 encoding.

## Installation and Setup 🛠️
1. **Clone or Download the Repository** 📥:
   - Clone using `git clone <repository-url>` or download the project folder containing the `.pbix` file.
2. **Open the PBIX File** 📄:
   - Launch Power BI Desktop.
   - Go to **File** > **Open Report** and select the `.pbix` file (e.g., `HotelAnalyticsDashboard.pbix`).
3. **Configure Data Sources** 🔗:
   - Update file paths for all dataset CSV files (e.g., `dim_date.csv`, `dim_rooms.csv`, `fact_bookings.csv`, and others) in Power BI Desktop to match your local environment.
4. **Save and Publish (Optional)** 📤:
   - Save changes to the `.pbix` file.
   - Publish to a Power BI Service workspace for sharing (requires appropriate permissions).

## Project Structure 📁
The project includes:
- `<ProjectName>.pbix`: The Power BI file containing the report, data model, DAX measures, and visualizations.
- **Source Data** (not included in .pbix but required) 📦:
  - `dim_date.csv`: Calendar data for time-based analysis.
  - `dim_rooms.csv`: Room inventory details.
  - `fact_bookings.csv`: Booking transactions.
  - Additional CSV files: Supporting tables for extended analysis (refer to the dataset documentation for details).

## Usage 🎯
- Open the `.pbix` file in Power BI Desktop to explore the interactive dashboard.
- Use the dashboard to analyze hotel performance metrics (ADR, RevPAR, occupancy) and derive insights for pricing, staffing, or marketing decisions.
- Modify DAX measures or report visuals as needed, then save changes to the `.pbix` file.

## Contributing 🤝
To contribute:
1. Fork the repository.
2. Create a new branch for your changes (`git checkout -b feature/your-feature`).
3. Modify the `.pbix` file in Power BI Desktop or update source data/documentation.
4. Commit changes (`git commit -m "Description of changes"`) and push to your fork.
5. Submit a pull request with a clear description of your updates.

## Notes ⚠️
- Ensure all CSV file paths are correctly configured in Power BI Desktop to avoid data loading errors.
- The `.pbix` file is a binary format; for version control, consider using Power BI Project (.pbip) format or managing source data separately.
- Avoid saving directly to OneDrive/SharePoint due to potential file locking issues; use a local or synced folder instead.

## License 📜
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

