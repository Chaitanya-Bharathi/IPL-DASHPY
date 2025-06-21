# IPL-DASHPY 🏏📊

A Python-based data analysis project for IPL statistics using Jupyter Notebook.

## Features ✨
✅ Data analysis of IPL matches and players  
✅ Interactive visualizations using Matplotlib  
✅ Team and player performance insights  
✅ Built using **Python, Pandas, Matplotlib**  

## Installation 🥠

Follow these steps to set up and run the project:

### Step 1: Clone the Repository
Download the project files by running:
```bash
git clone https://github.com/Chaitanya-Bharathi/IPL-DASHPY.git
cd IPL-DASHPY
```

### Step 2: Set Up a Virtual Environment 
Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows
```

### Step 3: Install Required Libraries
Install dependencies required for the project:
```bash
pip install -r requirements.txt
```
*If `requirements.txt` is missing, install manually:*
```bash
pip install pandas matplotlib jupyter
```

### Step 4: Run the Jupyter Notebook
Launch Jupyter Notebook and open the project file:
```bash
jupyter notebook
```
- In the browser, navigate to `ipl dashpy.ipynb` and run the cells.

### Step 5: Load the IPL Dataset
The dataset is already included in the repository as `matches.csv`. Ensure you are in the correct directory before running the code:
```python
import pandas as pd
ipl = pd.read_csv("matches.csv")
```
If you move the dataset, update the file path accordingly:
```python
ipl = pd.read_csv(r"C:\Users\YourUsername\Downloads\matches.csv")
```

## Dataset 📂
The dataset used for analysis includes IPL match data. It contains details about match results, teams, players, and statistics.

### Dataset File: `matches.csv`
This file is already present in the repository, so no additional downloads are required.

## Technologies Used 🖥️
- **Python** 🐍  
- **Jupyter Notebook** 🗃️  
- **Pandas** 💃  
- **Matplotlib** 🎨  

## Usage 📌
- View IPL team performance trends  
- Analyze player statistics  
- Generate graphs and insights from IPL match data  

## Contributing 🤝
Feel free to fork the repo, create a branch, and submit a pull request!
