
# 🎣 Phish Catcher

**Phish Catcher** is an intelligent phishing detection system that leverages machine learning to identify and block phishing URLs before they cause harm. Whether you're building browser extensions, email scanners, or web app firewalls, Phish Catcher offers a powerful backend to help protect users from online threats.

![Phish Catcher Screenshot](./screenshot.png)


## 🚀 Features

* 🛡️ Detects phishing URLs in real time
* 🤖 Trained ML model (Logistic Regression / Random Forest / XGBoost)
* 🌐 Web-based interface (Flask or Django)
* 🔍 URL Feature Extraction (e.g., length, presence of @, subdomains)
* 📈 Model Evaluation Dashboard
* 🔗 Easy API integration for developers

---

## 📦 Tech Stack

* **Frontend**: HTML, CSS, JavaScript (or React)
* **Backend**: Python, Flask (or Django)
* **ML Libraries**: scikit-learn, pandas, numpy
* **Deployment**: Docker, Heroku / Vercel / Netlify
* **Database**: SQLite / PostgreSQL (optional)

---

## 🧠 How It Works

1. User inputs a URL into the interface.
2. Features are extracted from the URL:

   * Length
   * Use of special characters (@, //, etc.)
   * Presence of IP addresses
   * Number of subdomains
   * HTTPS use
3. Pre-trained ML model predicts whether it's **phishing** or **legitimate**.
4. Output is shown with probability/confidence.

---



## 📊 Sample Model Performance

| Metric    | Score |
| --------- | ----- |
| Accuracy  | 96.2% |
| Precision | 95.1% |
| Recall    | 94.7% |
| F1 Score  | 94.9% |

---

## 🧪 Example URL Predictions

| URL                       | Prediction | Confidence |
| ------------------------- | ---------- | ---------- |
| `http://paypal-login.com` | Phishing   | 98%        |
| `https://google.com`      | Legitimate | 99%        |

---



---

## 🛠️ Future Enhancements

* Add real-time blacklist checks (Google Safe Browsing API)
* Extend to email content scanning
* Browser extension support
* Live dataset updates for retraining

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📬 Contact

Feel free to reach out with questions or suggestions:

* GitHub: [@aryan-70](https://github.com/aryan-70)
* Email: [er.shambhusah@gmail.com.com](mailto:er.shambhusah@gmail.com)

---

