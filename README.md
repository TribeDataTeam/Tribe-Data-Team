# Tribe-Data-Team
This houses all codes for the teams projects, data pipeline and analytics.

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/TribeDataTeam/Tribe-Data-Team?quickstart=1)

## Development Setup

### Virtual Environment

This project uses a Python virtual environment to manage dependencies. Follow these steps to set up your development environment:

1. Ensure you have Python 3.8+ installed on your system.

2. Clone the repository:
   ```bash
   git clone https://github.com/TribeDataTeam/Tribe-Data-Team.git
   cd Tribe-Data-Team
   ```

3. Create a virtual environment:
   ```bash
   python -m venv .venv
   ```

4. Activate the virtual environment:
   - On macOS/Linux:
     ```bash
     source .venv/bin/activate
     ```
   - On Windows:
     ```bash
     .venv\Scripts\activate
     ```

5. Install the project dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Sensitive Files

This repository does not include sensitive files such as:
- CSV data files (*.csv)
- Excel files (*.xls, *.xlsx)
- PDF reports (*.pdf)
- Power BI files (*.pbix)
- Image files (*.jpg, *.jpeg, *.png)
- API credentials (client_secrets.json, credentials.json)

Contact a team administrator to obtain any necessary credential files needed for development.

## Project Structure

The repository contains several Jupyter notebooks for different analytics tasks:
- Event analytics
- Social media analytics
- Community data analysis

## Working with Jupyter Notebooks

To start Jupyter Lab:
```bash
jupyter lab
```

This will open Jupyter Lab in your browser, where you can access and run the project notebooks. 
