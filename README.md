# 📦 SWIFT Shipment Tracking Assignment

### 👩‍💻 Submitted by: Sonali Kumari

---

## 📁 Project Overview
This project is designed for SWIFT's logistics data pipeline challenge. The assignment involves processing shipment tracking data from JSON format, extracting key fields, transforming them into a flattened structure, and exporting:

- A shipment-level dataset for analytics.
- Summary statistics to highlight delivery efficiency.

---

## 🔧 Technologies Used
- Python (3.x)
- Pandas
- Google Colab
- JSON handling
- Timezone conversions (`pytz` / pandas built-in support)
- Git & GitHub for version control

---

## 🗂️ Repository Structure
```
.
├── main.py                              # Python script for full pipeline
├── swift_shipment_tracking_sonali_kumari.ipynb  # Colab notebook version
├── shipment_dataset.json               # Raw dataset (uploaded via Colab)
├── shipment_tracking_output.csv        # Cleaned and transformed data
├── shipment_tracking_summary.csv       # Summary statistics CSV
└── README.md                            # Project documentation
```

---

## 📌 Features Implemented
- ✅ JSON parsing and data flattening
- ✅ IST timezone conversion
- ✅ Calculated delivery days (Pickup to Delivery)
- ✅ Counted number of delivery attempts (OD + DL events)
- ✅ Exported clean CSV for analysis
- ✅ Summary stats: Mean, Median, Mode

---

## 🚀 How to Run

### 📄 Using `main.py`
```bash
python main.py
```
> This will generate `shipment_tracking_output.csv` and `shipment_tracking_summary.csv` in the working directory.

### 🧠 Using Google Colab
1. Open `swift_shipment_tracking_sonali_kumari.ipynb`
2. Upload the dataset via the upload prompt
3. Run each cell in order
4. Download the two generated CSV files

---

## 📬 Output Files
- **shipment_tracking_output.csv** – Flattened shipment-level data
- **shipment_tracking_summary.csv** – Summary metrics (mean/median/mode)

---

## 📩 Author Contact
**Sonali Kumari**  
Data Engineer & AI Enthusiast  
Email: kumari.sonali.2017381@gmail.com  
GitHub: [@sonalee88](https://github.com/sonalee88)

---

## 🏁 Notes
- This project was built and executed in a time-sensitive challenge format.
- Accuracy, clarity, and code readability were prioritized.
- Submission includes both script and notebook versions for flexibility.

Thank you SWIFT team for the opportunity! 🚀
