# Agri-Chain OS

Agri-Chain OS is an integrated agriculture management and analytics platform built with Streamlit. It helps farmers, agribusinesses, and supply chain managers optimize crop production, market analysis, inventory, logistics, and sales—all in one place.

## Features

- **AI Forecasting:** Predict crop yields and market trends using advanced models.
- **Market Analysis:** Analyze commodity prices and trends with interactive dashboards.
- **Farm Management:** Track crop planting, growth, and harvest cycles.
- **Inventory & Warehouse:** Manage harvested commodities and warehouse stock.
- **Logistics Tracker:** Dispatch shipments and monitor real-time delivery progress with maps.
- **Finance & Sales:** Generate UPI QR codes for payments, log sales, and view financial dashboards.

## Tech Stack
- Python 3.12+
- Streamlit
- Pandas, Matplotlib, Seaborn
- SQLite (local database)
- geopy, folium, streamlit-folium
- qrcode

## Setup Instructions

1. **Clone the repository:**
   ```powershell
   git clone https://github.com/Dhanush-aradhya/Agri-connect.git
   cd Agri-connect
   ```
2. **Install dependencies:**
   ```powershell
   pip install -r requirements.txt
   ```
3. **Configure environment variables:**
   - Create a `.env` file with your API keys and UPI ID:
     ```env
     GROQ_API_KEY="your_groq_api_key"
     MY_UPI_ID="your_upi_id"
     ```
4. **Run the app:**
   ```powershell
   streamlit run 1_🔮_AI_Agri-Forecast_Model.py
   ```
   - You can also run other pages by changing the filename.

## Usage
- Access different modules from the sidebar in Streamlit.
- Add farm plots, harvest crops, manage inventory, dispatch shipments, and log sales.
- View analytics and financial dashboards for insights.

## Contribution
- Fork the repo and create a feature branch.
- Submit pull requests with clear descriptions.
- Report issues and suggest improvements via GitHub Issues.

## License
MIT License

## Contact
For questions or support, open an issue or contact the owner via GitHub.
