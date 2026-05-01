# Neurolytics

AI-powered data intelligence platform for analyzing datasets, detecting patterns, and generating insights.

---

## Overview

Neurolytics allows users to upload data and instantly receive:

* Cleaned datasets
* Visual analytics
* Predictive insights

Built as a full-stack system using Python for backend intelligence and a modern web interface for interaction.

---

## Features

* Upload CSV or JSON datasets
* Automatic data preprocessing
* Real-time charts and visualizations
* Machine learning predictions
* Pattern and trend detection
* Insight generation (summary output)
* Interactive dashboard
* Dark and light mode
* Persistent data storage

---

## Tech Stack

Backend:

* Python
* FastAPI / Flask
* pandas
* numpy
* scikit-learn

Frontend:

* HTML
* CSS
* JavaScript

Visualization:

* matplotlib / plotly

---

## How It Works

1. Upload dataset
2. System cleans and processes data
3. Models analyze patterns and trends
4. Results are returned as:

   * Charts
   * Metrics
   * Predictions
   * Insights

---
## Screenshots

![Screenshot 1](images/image%201.png)

![Screenshot 2](images/image%202.png)

![Screenshot 3](images/image%203.png)

![Screenshot 4](images/image%204.png)
## Installation

```bash
git clone <repo-url>
cd neurolytics
pip install -r requirements.txt
```

Run server:

```bash
uvicorn main:app --reload
```

---

## Usage

* Open browser at:
  http://localhost:8000

* Upload dataset

* View dashboard

* Explore insights

---

## Project Structure

```
/backend
  main.py
  routes/
  services/
  models/

/frontend
  index.html
  style.css
  script.js

/data
/uploads
/outputs
```

---

## Future Improvements

* Real-time data streaming
* Advanced AI models
* User authentication
* Cloud deployment
* API access

---

## License

MIT

