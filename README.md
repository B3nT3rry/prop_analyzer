# Property Investment Analyzer 🏠

A powerful Python-based tool for analyzing UK property investments. This system helps investors identify profitable properties by analyzing listing data, calculating ROI metrics, and providing detailed market insights.

![Python Version](https://img.shields.io/badge/python-3.8+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Development Status](https://img.shields.io/badge/status-beta-yellow.svg)

## 🚀 Features

- **Real-time Property Analysis**
  - Automated data collection from major UK property portals
  - Instant ROI calculations and yield analysis
  - Historical price trend analysis
  - Rental market assessment

- **Data Sources Integration**
  - Zoopla listings
  - Land Registry sold prices
  - ONS demographic data
  - Local authority planning data
  - EPC ratings

- **Investment Metrics**
  - Gross & Net Yield calculations
  - Capital growth projections
  - Cash flow analysis
  - Mortgage calculations
  - Risk assessment

- **Reporting**
  - Detailed PDF property reports
  - Market comparison analysis
  - Investment recommendations
  - Portfolio tracking

## 📋 Requirements

<!-- - Python 3.8+
- PostgreSQL
- Required Python packages:
```
pandas>=1.5.0
requests>=2.28.0
beautifulsoup4>=4.11.0
scikit-learn>=1.0.0
python-dotenv>=0.20.0
fastapi>=0.85.0
SQLAlchemy>=1.4.0
``` -->

## 🛠️ Installation

<!-- 1. Clone the repository:
```bash
git clone https://github.com/yourusername/property-investment-analyzer.git
cd property-investment-analyzer
```

2. Create and activate virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up environment variables:
```bash
cp .env.example .env
# Edit .env with your API keys and database credentials
```

5. Initialize the database:
```bash
python scripts/init_db.py
``` -->

## 🚀 Quick Start

<!-- 1. Configure your search criteria:
```python
from property_analyzer import PropertyAnalyzer

analyzer = PropertyAnalyzer()
criteria = {
    'location': 'Manchester',
    'max_price': 250000,
    'min_yield': 5.0
}
``` -->
<!-- 
2. Run analysis:
```python
results = analyzer.find_deals(criteria)
```

3. Generate report:
```python
report = analyzer.generate_report(results[0])
report.save('property_analysis.pdf')
``` -->

## 📊 Example Usage

<!-- ```python
from property_analyzer import PropertyAnalyzer, DealFinder

# Initialize analyzer
analyzer = PropertyAnalyzer()

# Set investment criteria
criteria = {
    'location': 'Manchester',
    'max_price': 250000,
    'min_bedrooms': 2,
    'property_type': 'flat',
    'min_yield': 5.0
} -->

<!-- # Find deals
deal_finder = DealFinder(analyzer)
good_deals = deal_finder.find_deals(criteria)

# Analyze top deal
if good_deals:
    top_deal = good_deals[0]
    analysis = analyzer.analyze_property(top_deal)
    print(f"Best Deal Found:")
    print(f"Price: £{analysis['price']:,}")
    print(f"Estimated Rent: £{analysis['estimated_rent']:,}")
    print(f"Net Yield: {analysis['net_yield']}%")
``` -->

## 📁 Project Structure

```
property-investment-analyzer/
├── src/
│   ├── data_collection/
│   │   ├── collectors/
│   │   ├── cleaners/
│   │   └── validators/
│   ├── analysis/
│   │   ├── calculator/
│   │   ├── predictor/
│   │   └── risk_assessor/
│   └── reporting/
├── tests/
├── docs/
├── scripts/
└── config/
```

## 🔑 API Keys Required

<!-- You'll need API keys for:
- Rightmove Data API (Commercial license required)
- Zoopla Property API
- Land Registry API
- ONS API
- Companies House API (optional) -->

## 🤝 Contributing

Contributions are welcome! Please read our [Contributing Guidelines](CONTRIBUTING.md) first.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

This tool is for research and analysis purposes only. Investment decisions should not be made solely based on this tool's output. Always conduct your own due diligence and consult with qualified professionals before making investment decisions.

## 🙏 Acknowledgments

- UK Land Registry for property price data
- Office for National Statistics for demographic data
- OpenStreetMap contributors for location data
- All contributors who have helped with the project

## 📞 Support

If you have any questions or need help with setup, please:
1. Check the [Documentation](docs/README.md)
2. Look through [Existing Issues](https://github.com/yourusername/property-investment-analyzer/issues)
3. Open a new issue if needed

---
Made with ❤️ by Ben Terry