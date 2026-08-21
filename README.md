# AI Project: Network Intrusion Detection

**Group Members:**
- M. Uzair Shoaib (24P-0507)
- Azaan Noor Khuwaja (24P-0706)

---

## Prerequisites

Before running the notebook, make sure you have the following installed:

- **Python** (3.8 or higher) — [Download](https://www.python.org/downloads/)
- **Jupyter Notebook** or **JupyterLab**

Install Jupyter and the required Python libraries via pip:

```bash
pip install notebook numpy pandas matplotlib scikit-learn
```

Or install via Anaconda (recommended): [https://www.anaconda.com/download](https://www.anaconda.com/download)

---

## Installation & Setup

### Step 1 — Extract the Project

Extract the contents of the provided ZIP file to a folder of your choice. Ensure that the original dataset is placed correctly as expected by the notebook:
You should have a `dataset` directory containing `network_traffic.csv` in the same directory as the notebook.

---

### Step 2 — (Optional) Create a Virtual Environment

It is recommended to use a virtual environment to avoid dependency conflicts.

```bash
python -m venv venv
```

Activate it:

- **Windows:**
  ```bash
  venv\Scripts\activate
  ```
- **macOS / Linux:**
  ```bash
  source venv/bin/activate
  ```

---

## Running the Notebook

### Step 3 — Launch Jupyter Notebook

In your terminal (inside the extracted project folder), run:

```bash
jupyter notebook
```

This will open the Jupyter interface in your default web browser at `http://localhost:8888`.

---

### Step 4 — Open the Notebook File

In the Jupyter browser interface:

1. Navigate to the project folder.
2. Click on the `AI_Final_Project.ipynb` file to open it.

---

### Step 5 — Run the Notebook

You have two options:

**Option A — Run All Cells at Once:**

Go to the top menu and click:

```
Kernel → Restart & Run All
```

This restarts the kernel and executes every cell from top to bottom without manual tweaking.

**Option B — Run Cells One by One:**

Click on any cell and press:

```
Shift + Enter
```

This runs the current cell and moves to the next one. Repeat for each cell in order.

---

### Step 6 — View the Output

Results, plots, and model outputs will appear directly below each cell as they finish executing. The notebook covers:
- Task 1: Data Exploration
- Task 2: Simple Reflex Agent
- Task 3: Supervised Learning (KNN, Naïve Bayes, Logistic Regression)
- Task 4: K-Means Clustering
- Task 5: Genetic Algorithm for Feature Selection

---

## Project Structure

```text
/
│
├── AI_Final_Project.ipynb       # Main Jupyter notebook containing all tasks
├── Final_Report_Project.pdf     # Comprehensive project report (PDF)
├── README.md                    # Instructions on how to run the code
└── dataset/                     # Required dataset folder (not included in submission)
    └── network_traffic.csv      # The dataset file (6,000 connection records)
```

---

## Troubleshooting

| Issue | Solution |
|---|---|
| `jupyter: command not found` | Run `pip install notebook` again |
| Module not found error | Run `pip install numpy pandas matplotlib scikit-learn` |
| Kernel keeps dying | Check RAM usage; restart kernel and re-run |
| Port 8888 already in use | Run `jupyter notebook --port 8889` |
