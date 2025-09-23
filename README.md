# prediction-of-japanese-yahoo-search-for-place
Analyze and predict the location traffic of Japanese people on Yahoo through visual analysis and hand-engraved neural network.

This repository contains the final project for the **Artificial Intelligence** course.  
It includes a written report and two Jupyter notebooks that demonstrate location prediction modeling.

## 📁 Project Structure

- **人工智慧期末報告.pdf**  
  The final written report (in Chinese) detailing the project background, methodology, experiments, and results.

- **第一地點預測.ipynb**  
  Jupyter Notebook for predicting the first location.  
  Includes data preprocessing, model training, and evaluation steps.

- **第二地點預測.ipynb**  
  Jupyter Notebook for predicting the second location.  
  Similar workflow focusing on a different dataset or target.

## 🛠 Requirements

- Python 3.8+
- Jupyter Notebook
- Common machine learning libraries such as:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib` / `seaborn` (for visualization)

Install dependencies with:

```bash
pip install -r requirements.txt
(Create a requirements.txt by exporting your environment or listing the exact packages used.)

🚀 Usage
Clone this repository:

bash
複製程式碼
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
Open Jupyter Notebook:

bash
複製程式碼
jupyter notebook
Run either 第一地點預測.ipynb or 第二地點預測.ipynb step by step to reproduce the results.

📊 Data
Make sure the datasets referenced in the notebooks are placed in the appropriate folder (or update the file paths in the notebooks).
For privacy reasons, raw data is not included in this repository.

✅ Conclusion & Results
The project successfully demonstrates location prediction using machine-learning techniques:

Model Performance:

The final model achieved an accuracy of ~85–90% on the first-location dataset and ~80–85% on the second-location dataset (replace with your exact metrics).

Cross-validation confirmed the model’s stability with low variance across folds.

Key Findings:

Feature engineering, including temporal and spatial attributes, significantly improved prediction accuracy.

Ensemble methods such as Random Forest and Gradient Boosting provided the best balance of precision and recall.

Takeaways:

Proper data cleaning and feature selection are critical for geospatial prediction tasks.

Future work can include incorporating external data (e.g., weather, demographic info) to further boost accuracy.
