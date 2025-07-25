# 🏁 Formula 1 Winner Predictor

**Author:** Nirvaan Lagishetty

A web application that predicts Formula 1 Grand Prix winners using real-time data from the [Ergast Developer API](https://ergast.com/mrd/) and a Random Forest machine learning model. This project demonstrates the integration of sports data, data science, and web development in an interactive, user-friendly format.

---

## 🚦 Features

- **Live Data Integration:** Automatically fetches up-to-date race statistics.
- **Insightful Analytics:** Considers driver performance, constructor strength, and track details.
- **Robust Predictions:** Utilizes a trained Random Forest model for winner forecasting.
- **Modern Web App:** Built with Flask, featuring an intuitive interface.

---

## 🖥️ Preview

<p align="center">
  <img src="templates/demo.png" width="600" alt="App Screenshot">
</p>

---

## 🚀 Quick Start

1. **Clone the Repository**
    ```
    git clone https://github.com/Nirvaan05/F1-Winner-Predictor-.git
    cd Formula1_project
    ```

2. **Install Dependencies**
    ```
    pip install -r requirements.txt
    ```

3. **Run the Application**
    ```
    python app.py
    ```
    Then visit [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.

---

## 🕹️ Usage

1. Enter the **F1 season** and **race number**.
2. Click **Predict**.
3. View the predicted winner and team for the selected Grand Prix.

---


## 🧩 Tech Stack

- Python 3
- Flask
- Pandas
- scikit-learn (Random Forest)
- HTML/CSS (Jinja2 templates)

---

## ℹ️ Troubleshooting

- **API Connection Error:**  
  Confirm internet access and API availability.
- **No Prediction Output:**  
  Ensure valid inputs and verify that the Ergast API is responsive.

---

## 📊 Data Sources

- [Ergast Developer API](https://ergast.com/mrd/)
- Local F1 CSV datasets (provided in `/data`)

---

## 📄 License

This project is for educational and demonstration use only.

---

## 🙏 Acknowledgements

- [Ergast Developer API](https://ergast.com/mrd/)
- The global Formula 1 community

---

