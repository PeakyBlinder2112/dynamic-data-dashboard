# 📊 Dynamic Data Visualization Dashboard

An interactive and powerful data visualization app built using **Streamlit**. Upload your own CSV data, clean and filter it, generate insightful charts, and download the results — all without writing a single line of code!

---

## 🚀 Features

✅ **Upload CSV Files**: Easily upload your CSV data to begin analysis.  
✅ **Data Cleaning**: Handle missing values (mean, median, mode, custom, interpolation, etc.), remove duplicates, outliers, and high-null rows.  
✅ **Flexible Filters**: Apply categorical, numeric, date range, and custom query filters.  
✅ **Rich Visualizations**:  
 • Bar Charts  
 • Pie Charts  
 • Scatter Plots (with optional trendline)  
 • Line Charts  
 • Histograms  
 • Box Plots  
 • Violin Plots  
 • Heatmaps (correlation matrix)  
✅ **Dashboards**: Switch between auto-generated Default Dashboard and user-defined Custom Dashboard.  
✅ **Filter Modes**: Choose between global dashboard filters or per-visualization filters.  
✅ **Download Data**: Export cleaned or filtered datasets as CSV.  
✅ **AI Insights**: Get summaries of numeric and categorical data, including mean, min, max, skewness, and correlations.  

---

## 🛠️ Technologies Used

- **Streamlit**: For the interactive web interface.  
- **Pandas**: For data manipulation and cleaning.  
- **Plotly**: For interactive visualizations.  
- **Seaborn** & **Matplotlib**: For heatmap visualizations and plotting support.  
- **NumPy**: For numerical operations.  
- **Statsmodels**: For regression trendlines in scatter plots (optional).  
- **Pillow (PIL)**: For image handling.  

---

## 📁 Folder Structure

```
dynamic-data-dashboard/
│
├── app.py              # Main Streamlit application
├── requirements.txt    # Python dependencies
├── README.md           # This file
└── sample.csv          # (Optional) Sample dataset for testing
```

---

## ⚙️ Setup Instructions

### 🔧 Run Locally

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/dynamic-data-dashboard.git
   cd dynamic-data-dashboard
   ```

2. **Create a Virtual Environment** (recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the App**
   ```bash
   streamlit run app.py
   ```

5. Open your browser at `http://localhost:8501`.

### 🌐 Deploy on Streamlit Cloud

1. Push the repository to GitHub.
2. Go to [Streamlit Community Cloud](https://share.streamlit.io).
3. Connect your GitHub account, select the repository, and choose `app.py` as the main file.
4. Deploy, and your app will be live!

---

## 📝 Requirements

Create a `requirements.txt` file with the following dependencies:

```
streamlit==1.24.0
pandas==2.0.3
plotly==5.15.0
seaborn==0.12.2
matplotlib==3.7.1
numpy==1.24.3
statsmodels==0.14.0
pillow==10.0.0
```

Install them using:
```bash
pip install -r requirements.txt
```

---

## 🧪 Sample Data

To test the app, you can use a `sample.csv` file with the following structure:

```csv
Category,Value,Date
A,10,2023-01-01
B,20,2023-01-02
A,15,2023-01-03
C,25,2023-01-04
```

Upload this file via the app’s file uploader to explore its features.

---

## 📸 Screenshots

*Check output screens Folder *

---

## 🛠️ Usage

1. **Upload Data**: Upload a CSV file using the file uploader.
2. **Clean Data**: Use the "Clean Data" tab to handle missing values, remove duplicates, outliers, or sample large datasets.
3. **Create Visualizations**: In the "Filters & Visualization" tab, select chart types, configure axes, apply filters, and add to the Custom Dashboard.
4. **View Dashboards**: Switch between Default and Custom Dashboards in the "Dashboard" tab, applying global or per-visualization filters.
5. **Explore Insights**: Check the "Insights & Filtered Data" tab for AI-generated summaries and download filtered datasets.

---

## 🙌 Credits

Built with ❤️ using Streamlit, Pandas, and Plotly.  
Developed by [Your Name] – contributions and forks are welcome!

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.