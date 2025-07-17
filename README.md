# 🌍 Countries Data Analysis Project

## 📖 Description
This project conducts a detailed exploratory data analysis (EDA) on a comprehensive dataset covering 194 countries around the world. The analysis leverages Python and pandas to query and manipulate the data, aiming to uncover key insights into global demographics, politics, and geography. The entire process is documented in the `Countries_project.ipynb` Jupyter Notebook.

---

## 📊 Key Analyses Performed
* **Population Analysis:**
    * Identified the countries with the highest and lowest populations and their respective capitals.
    * Determined the political leader of the second most populous country in the world.
* **Political & Governance Analysis:**
    * Identified the top 5 countries with the highest democracy scores.
    * Counted how many countries have "Republic" in their official name.
    * Listed the countries where the political leader's name was not available in the dataset.
* **Geographical Analysis:**
    * Calculated the total number of unique global regions represented.
    * Filtered and listed all countries belonging to the "Eastern Europe" region.
    * Determined the most populous country on the African continent.

---

## 💻 Technologies Used
* **Python 3.13** (or your current stable version)
* **Pandas:** For data manipulation, querying, and analysis.
* **NumPy:** For core numerical operations.
* **Jupyter Notebook:** As the interactive environment for the analysis.

---

## 🚀 Setup and Installation

To run this project on your local machine, please follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Heet-Jamariya/Countries_Project.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Countries_Project
    ```
3.  **Create and activate a virtual environment:**
    ```bash
    # Create the virtual environment
    py -m venv .venv

    # Activate the virtual environment (for Windows)
    .\.venv\Scripts\activate
    ```
4.  **Create a `requirements.txt` file** with the following content:
    ```
    pandas
    numpy
    jupyter
    ```
5.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
6.  **Run the notebook:**
    Open the `Countries_project.ipynb` file in VS Code or Jupyter Notebook to view and run the analysis.

---
## 📈 Data Source
The dataset used for this analysis is included in this repository: `Countries.csv`.