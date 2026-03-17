Here are  **instructions to run the project** (simple and direct):

---

### ▶️ Run the Notebook (Local System)

* Make sure Python is installed (Python 3.8+ recommended)

* Install required libraries:

  ```bash
  pip install pandas numpy scikit-learn matplotlib seaborn xgboost
  ```

* Place the following files in the same folder:

  * `titanic_prediction.ipynb`
  * `train.csv`
  * `test.csv`

* Open terminal / command prompt in that folder and start Jupyter:

  ```bash
  jupyter notebook
  ```

* Open `titanic_prediction.ipynb` and run all cells (Shift + Enter)

---

### ▶️ Run on Kaggle

* Go to Kaggle → Code → New Notebook
* Upload `titanic_prediction.ipynb`
* Attach Titanic dataset (`train.csv`, `test.csv`)
* Click **Run All**

---

### ▶️ Run on Google Colab

* Open Google Colab
* Upload the notebook file
* Upload dataset files when required
* Run all cells from top to bottom

---

### ⚠️ Important

* Ensure dataset paths are correct in code

  * Local: `"train.csv"`
  * Kaggle: `"/kaggle/input/.../train.csv"`
  * Colab: `"/content/train.csv"`

* Install missing libraries if any error occurs

* Run cells in sequence for correct output
