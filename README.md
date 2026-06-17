# FX Checker - Currency Converter Hackathon Project

# Four phase Roadmap
- Phase 1 : Planning, Design system mapping
- Phase 2 : Core Frontend Development (HTML, CSS SETUP)
- phase 3 : Javascript logic and API intergration
- Phase 4 : Polish , animation and tesing


# Features

- Real-time Currency Conversion
- Historical Rate Chart (Line Graph)
- Responsive & Dynamic UI
- Modern Dark Theme
- User-Friendly Interface

# Tech Stack

- HTML 
- CSS
- Javascript

# API reference

- https://www.frankfurter.app/docs


# Structure

 - Header 
        - FX_CHECKER Logo
        - Live Rates Display (e.g., EUR/GBP 0.8595, -0.67%)


 - Static Converter Section (Always Visible) 
        - Amount Input
- [ From Currency ]  [ ⇄ Swap Button ]  [ To Currency ]
- Result Display (e.g., 920.00 EUR)
- Subtext: "1 USD = 0.92 EUR"

 - Navigation Tabs (Responsive) 
    - HISTORY | COMPARE | FAVORITES (10) | LOG (8)
    - (Collapses to dropdown on mobile)

- Dynamic Content Area (Changes based on tab) 
    - If HISTORY: Shows the Historical Trend Mini-Chart.
    - If COMPARE: Shows [Waiting for your details!]
    - If FAVORITES: Shows saved pairs list.
    - If LOG: Shows recent activity list.