# Asset Management Dashboard - MBTA

A comprehensive asset management and condition monitoring dashboard for tracking infrastructure assets, inspection schedules, and maintenance backlogs.

## 📊 Overview

This dashboard provides real-time insights into asset conditions across multiple lines and asset classes, helping prioritize maintenance activities and resource allocation.

### Key Metrics

- **Total Assets**: 250 assets tracked across all lines
- **Asset Condition**: 24.40% of assets rated as Poor/Very Poor
- **Overdue Inspections**: 136 inspections requiring immediate attention
- **Maintenance Backlog**: $87M in deferred maintenance costs

## 🎯 Features

### 1. Asset Condition by Line
Visual breakdown of asset health across different lines:
- **CR Line** (Purple): 26.3% Poor/Very Poor assets
- **Blue Line**: 26.0% Poor/Very Poor assets
- **Orange Line**: 25.6% Poor/Very Poor assets
- **Green Line**: 23.2% Poor/Very Poor assets
- **Red Line**: 20.5% Poor/Very Poor assets

### 2. Asset Classification
Track assets across five major categories:
- **Facilities**: 44 assets
- **Power**: 41 assets
- **Signals**: 53 assets
- **Structures**: 71 assets
- **Track**: 41 assets

### 3. Condition Ratings
Assets are classified into five condition categories:
- Excellent (29 assets)
- Fair (93 assets)
- Good (67 assets)
- Poor (44 assets)
- Very Poor (17 assets)

### 4. Asset Age vs Condition Analysis
- Scatter plot visualization showing relationship between asset age and condition scores
- Identifies assets flagged as overdue for replacement
- Helps prioritize capital improvement projects

### 5. Interactive Filtering
Filter data by:
- Condition bucket
- Line (CR, Blue, Orange, Green, Red)
- Asset class
- Custom combinations for detailed analysis

## 🚀 Getting Started

### Prerequisites
- Power BI Desktop (or equivalent BI tool)
- Access to asset management database
- Appropriate permissions for data sources

### Installation

1. Clone this repository:
```bash
git clone https://github.com/SiddhiRavindra/AssetManagement_Dashboard_MBTA.git
```

2. Open the dashboard file in Power BI Desktop

3. Configure data source connections:
   - Update connection strings
   - Refresh credentials if needed

4. Refresh data to load latest asset information

## 📈 Usage

### For Asset Managers
- Monitor overall asset health by line
- Identify critical assets requiring immediate attention
- Track inspection compliance rates
- Prioritize budget allocation based on backlog analysis

### For Maintenance Teams
- View overdue inspections by asset class
- Access detailed condition assessments
- Plan preventive maintenance schedules
- Track work order completion

### For Executive Leadership
- High-level KPIs on dashboard summary cards
- Trend analysis for capital planning
- Risk assessment based on asset conditions
- ROI tracking for maintenance investments

## 📊 Data Sources

The dashboard integrates data from:
- Asset inventory system
- Computerized Maintenance Management System (CMMS)
- Inspection records database
- Financial systems (replacement costs, backlog calculations)

## 🔄 Update Frequency

- **Real-time**: Asset condition updates
- **Daily**: Inspection status and overdue flags
- **Weekly**: Backlog calculations
- **Monthly**: Comprehensive asset health reports

## 🛠️ Customization

### Adding New Asset Classes
1. Update data model to include new classification
2. Modify filtering logic
3. Update visualizations to reflect new categories

### Modifying Condition Thresholds
Edit the condition scoring logic in the data transformation queries to adjust rating criteria.

## 📝 Best Practices

- Review overdue inspections weekly
- Update asset conditions immediately after inspections
- Validate backlog calculations monthly
- Archive historical data annually for trend analysis

## 🤝 Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit changes (`git commit -m 'Add new feature'`)
4. Push to branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📧 Contact

**Project Maintainer**: SiddhiRavindra

For questions or support, please open an issue in the GitHub repository.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- MBTA Operations Team for data validation
- Asset Management Division for requirements gathering
- IT Department for database integration support

---
