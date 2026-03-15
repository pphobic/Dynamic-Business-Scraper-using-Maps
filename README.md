# Dynamic Business Scraper 💎

A professional Python-based web scraper designed to generate high-quality business leads. It dynamically scrapes Google Maps for businesses in a specific niche and then performs "skiptracing" to identify decision-makers (Owners, CEOs, Founders) using sources like the BBB, Yellow Pages, and company websites.

## 🚀 Features

- **Google Maps Integration**: Searches for businesses based on niche and location.
- **Decision Maker Discovery**: Automatically attempts to find the names of business owners or executives.
- **Multi-Source Validation**: Cross-references data from:
  - Google Maps
  - Better Business Bureau (BBB)
  - Yellow Pages
  - Official Company Websites (About/Team pages)
- **Formatted Export**: Saves all leads into a professionally formatted Excel (`.xlsx`) file.
- **Anti-Bot Measures**: Uses Selenium with stealth configurations to minimize detection.

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/dynamic-pro-scraper.git
   cd dynamic-pro-scraper
   ```

2. **Set up a virtual environment** (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Web Driver**: The script uses `webdriver-manager`, so it will automatically download the correct Chrome driver for your system. Ensure you have Google Chrome installed.

## 📖 Usage

1. Run the scraper:
   ```bash
   python scraper.py
   ```
2. Enter your **Target Niche** when prompted (e.g., `Solar`, `Roofing`, `HVAC`).
3. The script will open a Chrome window and begin searching.
4. Once complete (or if manually stopped), the leads will be saved in an Excel file named after your niche (e.g., `Solar.xlsx`).

## ⚠️ Disclaimer

This tool is for educational and professional lead generation purposes only. Users are responsible for complying with the Terms of Service of the websites being scraped (Google, BBB, Yellow Pages) and ensuring they adhere to local data privacy laws (e.g., GDPR, CCPA). Use responsibly and avoid aggressive scraping that could strain server resources.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
