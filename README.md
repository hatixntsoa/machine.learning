# Machine Learning Project Template 🤖

A professional **Machine Learning project template** designed for GitHub repositories connected to Kaggle.
Use this as a starting point to keep your ML projects organized, reproducible, and production-ready.

---

## 📂 Project Structure

```
.
├── data
│   ├── raw/              # Original datasets
│   └── processes/        # Cleaned and feature-engineered data
│
├── notebooks/            # Jupyter / Kaggle notebooks
│   └── ml.template.ipynb
│
├── src/
│   ├── __init__.py       # Register as a package
│   └── model_export.py   # Example code of model export
│
├── models/               # generated models
│
├── tests/                # Unit testing out the model
│
├── LICENSE.md            # License file
├── README.md             # Project documentation
├── requirements.txt      # Python dependencies
└── .gitignore            # Ignore python related dependencies and environments
```

---

## ⚙️ Setup

You have **two ways** to use this template:

### 🔹 Option 1 — Work directly on Kaggle

1. Go to the [Machine Learning Project Template](https://github.com/hatixntsoa/machine.learning) repository on GitHub.
2. Click the **“Use this template”** button and create a new repository.
3. On Kaggle, create a new Notebook and choose **“Link to GitHub”** → select your repository.

   * This keeps your exploratory work synced with GitHub.
4. Start coding directly in Kaggle without installing anything locally.

---

### 🔹 Option 2 — Work locally or on your own cloud machine

1. Go to the [Machine Learning Project Template](https://github.com/hatixntsoa/machine.learning) repository on GitHub.
2. Click the **“Use this template”** button and create a new repository.
3. Clone your new repository:

   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
   ```
4. Create a virtual environment:

   ```bash
   python -m venv .venv
   ```
5. Activate the virtual environment:

   * On Linux/Mac:

     ```bash
     source .venv/bin/activate
     ```
   * On Windows:

     ```bash
     venv\Scripts\activate
     ```
6. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

Now you're good to go! 🚀

---

## 📜 License

This project is licensed under the [MIT License](LICENSE.md).
