# Personal Finance Manager

A desktop-based financial management application developed in C++ using the Qt Framework. This tool provides users with a comprehensive dashboard to track expenses, visualize spending habits, and manage monthly budgets with persistent data storage.


## Overview

Personal Finance Manager is designed to simplify personal accounting through an intuitive Graphical User Interface (GUI). It integrates budget tracking, custom categorization, and dynamic data visualization to help users maintain financial discipline.

The application is built using **C++** and **Qt Creator**, utilizing standard libraries for backend logic and QtCharts for data rendering.

## Key Features

### Balance & Budget Tracking
* **Monthly Budgeting:** Allows users to set a specific expense target for the month. The system automatically resets tracking at the start of each billing cycle.
* **Visual Indicators:** Features a dynamic progress bar that displays real-time expenditure against the set budget, providing immediate visual feedback on financial health.
* **Calendar Integration:** Users can interact with a calendar widget to retrieve and review specific transactions recorded on any given date.

### Custom Categorization & Data Management
* **Transaction Labeling:** Users can specify amounts and assign categories to every income and expense entry for precise tracking.
* **Custom Categories:** The system supports dynamic category creation, allowing users to define new labels beyond the default set.
* **CSV Persistence:** All financial data is serialized and stored in CSV format, ensuring data persistence and portability.

### Advanced Search
* **Keyword Filtering:** A robust search bar allows users to locate specific transactions instantly.
* **Detail View:** Filtering by category or item name populates a detailed table view with all matching transaction records.

### Data Visualization
* **Interactive Charts:** Integrates **QtCharts** to render financial data visually.
* **Time-Series Analysis:** A line chart displays daily expense trends over selected periods (Last 7 days, 30 days, or Year-to-Date).
* **Category Breakdown:** A pie chart provides a percentage-based breakdown of spending by category, helping users identify major expense areas.
* **Custom Ranges:** Users can define specific date ranges to generate custom analytical reports.

### Predictive Shopping List
* **Cost Estimation:** A dedicated module for tracking planned purchases.
* **Budget Impact Analysis:** Users can toggle a predictive feature that calculates how planned shopping items will impact their current remaining budget, updating the visual indicators in real-time without committing the transaction.

### Reporting
* **QR Code Generation:** The application generates QR codes containing brief summaries of expense reports, including specific items and total costs, facilitating easy data transfer to mobile devices.

## Technical Stack

* **Language:** C++
* **Framework:** Qt 5 / Qt 6
* **Libraries:** QtCharts, QtMultimedia
* **Data Storage:** CSV / File I/O
* **Build System:** QMake / CMake

## Installation & Usage

1. Clone the repository.
2. Open `ExpenseTracker.pro` in Qt Creator.
3. Configure the project with your specific Kit (Desktop Qt MinGW or MSVC).
4. Build and Run.

## Future Improvements

* Migration from CSV storage to SQLite database for improved query performance.
* Implementation of cloud synchronization for cross-device access.
* Dark mode UI support.