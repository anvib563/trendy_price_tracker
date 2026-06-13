# trendy_price_tracker
A production-grade, highly optimized daily price scraper engine and advanced analytics dashboard tracking 11 premier fashion brands and Amazon Tech. Built with Python, Playwright, Pandas, and Chart.js.
# Fashion & Tech – Dynamic Price Analysis Engine 📈🛒

A production-grade, highly optimized automated system engineered to track, parse, and analyze daily product pricing matrixes across 11 premier fashion retailers and the Amazon Tech ecosystem. 

This project transforms unstructured, highly volatile e-commerce webpages into clean, relational, historical flat-file CSV datasets, exposing them via a high-density, cryptocurrency-style interactive HTML client dashboard.

## 🔥 Key Capabilities

*   **Resilient Automated Scraping Backend:** Multi-tiered data collection architecture engineered to systematically bypass modern anti-bot obstacles, dynamic script delays, and layout changes.
*   **Deep Business Analytics Engine:** Automated Python-driven vector processing that tracks markdown velocity, absolute price differentials, and historical volatility trends.
*   **Financial-Style Live UI Cockpit:** A single-file, zero-dependency dark-mode interface featuring side-scrolling ticker tapes, real-time search, multi-currency conversion, and embedded row sparklines.

## 🛠️ System Architecture & Stack
### Technical Stack
*   **Backend & Extraction:** Python 3.11+, Playwright Async, BeautifulSoup4, Requests
*   **Data Processing:** Pandas, NumPy
*   **Frontend Dashboard:** TailwindCSS v3, Chart.js 4.x, PapaParse (Client-side, Serverless)

---

## 🚀 How It Works (Collection Profiles)

The system deploys three distinct ingestion methods depending on the target retailer's underlying e-commerce architecture:

1.  **Method A (Shopify JSON API):** Targets hidden, unauthenticated native framework endpoints (e.g., *Brandy Melville, Garage, PacSun*) to pull the absolute lowest available variant price with zero frontend layout reliance.
2.  **Method B (JSON-LD Structural Parse):** Evaluates deep structured metadata blocks script tags via BeautifulSoup4 to bypass dynamic client-side element render delays (e.g., *Subdued*).
3.  **Method C (Playwright Headless Browser):** Launches masked, flag-hidden headless Chromium instances to simulate realistic human behaviors, setting desktop viewports and rendering heavy JavaScript-dependent Single Page Applications (e.g., *Zara, H&M, Lululemon, Amazon*).

---

## 📊 Analytics & Statistical Logic

Every automated cycle feeds into `analysis/analyze.py` to calculate core micro/macro economic metrics strictly bounded by product lines:
*   **7-Day Rolling Moving Average (`MA_7`):** Generates structural baseline pricing layers using grouped transformations.
*   **Discount & Price Step Vectoring:** Evaluates absolute dollar shifts (`diff()`) and scaling factor discount percentages.
*   **Weekday Pattern Discovery:** Maps promotional distribution clusters to isolate high-frequency markdown trends (e.g., Friday/Saturday drops).
*   **Retailer Volatility Matrix:** Ranks company pricing behaviors descending by calculating `changes / total_observations * 100`.
If you
