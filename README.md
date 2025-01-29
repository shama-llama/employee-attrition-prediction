# Employee Attrition Prediction

[![Python](https://img.shields.io/badge/Python-3.12+-3776AB?logo=python&logoColor=white)](https://docs.python.org/3.12/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.7+-F7931E?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/whats_new/v1.7.html)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

This project uses a Decision Tree Classifier to predict employee attrition using scikit-learn. The notebook compares model performance before and after hyperparameter tuning and is adapted from [Decision Trees & Random Forest for Beginners](https://www.kaggle.com/code/faressayah/decision-trees-random-forest-for-beginners).

## Topics

- Preprocessing
- Feature Engineering
- Train-test Split
- Decision Tree Classifier from `scikit-learn`
- Hyperparameter Tuning with `GridSearchCV`
- Model Evaluation
- Visualization with `matplotlib`, `seaborn`, and `pydot`

## Dataset

The dataset used for this project is the "[IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data)" dataset from Kaggle. A copy of the dataset accessed on Jan. 25 is included in the `data` directory.

## Project Setup

This project uses `uv` for package management. `uv` is an extremely fast Python package and project manager, written in Rust that can be used as a drop-in replacement for `pip`, `pip-tools`, `pipx`, `poetry`, `pyenv`, `twine`, `virtualenv`.

- **`uv` Installation**

    ```bash
    curl -LsSf https://astral.sh/uv/install.sh | sh
    ```

- **Clone the Repository:**

    ```bash
    git clone https://github.com/shama-llama/employee-attrition-prediction.git
    cd employee-attrition-prediction
    ```

- **Create a Virtual Environment and Install Dependencies with `uv`:**

    ```bash
    uv venv
    uv pip install -e .
    ```

- **Activate the Virtual Environment:**

    ```bash
    source .venv/bin/activate
    ```

- **Launch Jupyter Notebook:**

    ```bash
    jupyter notebook
    ```

    Navigate to the `notebooks/` directory to run the analysis.

## References

> F. Sayah, “Decision Trees & Random Forest for Beginners,” *Kaggle*. Accessed: Jan. 10, 2025. [Online]. Available: [https://www.kaggle.com/code/faressayah/decision-trees-random-forest-for-beginners](https://www.kaggle.com/code/faressayah/decision-trees-random-forest-for-beginners).
>
> P. Subhash, Aug. 2017, “IBM HR Analytics Employee Attrition & Performance,” Kaggle. [Online]. Available: [https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data).

## License

This project is licensed under the terms of the [Apache 2.0](LICENSE) open source license.
