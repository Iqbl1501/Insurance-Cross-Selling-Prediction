<p align="center">
  <img src="https://img.icons8.com/external-tal-revivo-regular-tal-revivo/96/external-readme-is-a-easy-to-build-a-developer-hub-that-adapts-to-the-user-logo-regular-tal-revivo.png" width="100" />
</p>
<p align="center">
    <h1 align="center">INSURANCE-CROSS-SELLING-PREDICTION</h1>
</p>
<p align="center">
    <em><code>Data 200</code></em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/Theofilusarifin/Insurance-Cross-Selling-Prediction?style=flat&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/Theofilusarifin/Insurance-Cross-Selling-Prediction?style=flat&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/Theofilusarifin/Insurance-Cross-Selling-Prediction?style=flat&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/Theofilusarifin/Insurance-Cross-Selling-Prediction?style=flat&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
		<em>Developed with the software and tools below.</em>
</p>
<p align="center">
	<img src="https://img.shields.io/badge/Jupyter-F37626.svg?style=flat&logo=Jupyter&logoColor=white" alt="Jupyter">
</p>
<hr>

##  Quick Links

> - [ Overview](#-overview)
> - [ Repository Structure](#-repository-structure)
> - [ Getting Started](#-getting-started)
>   - [ Installation](#-installation)
>   - [ Running Insurance-Cross-Selling-Prediction](#-running-Insurance-Cross-Selling-Prediction)
> - [ Contributing](#-contributing)
> - [ Acknowledgments](#-acknowledgments)

---

##  Overview
<p align="center">
The Health Insurance Cross Sell Prediction project aimed to develop a classification model to predict health insurance policyholders' interest in subscribing to vehicle insurance. The project was led by Team Data 200 from Rakamin Academy, with Theofilus Arifin as the project leader. The dataset used in the project contained demographic and behavioral information of health insurance customers related to their interest in vehicle insurance. The team conducted an exploratory data analysis (EDA) to gain insights into the relationships between various features and the customers' interest in vehicle insurance. The EDA revealed that middle-aged adults, both male and female, showed the highest interest in vehicle insurance, with approximately 17.3% and 18.7% interest rates, respectively. Furthermore, the analysis showed that customers who had not previously subscribed to vehicle insurance exhibited a higher interest rate of 22.5%, while those who had previously subscribed showed minimal interest. These insights were crucial in understanding customer behavior and forming the basis for the subsequent modeling phase.
</p>
<p align="center">
In terms of preprocessing, the team performed data cleansing to handle missing values and duplicates in the dataset. Feature transformation was carried out to handle class imbalance, feature encoding, and outlier handling. Feature extraction involved creating new features based on age categories, the interaction between vehicle damage and age, and the ratio of annual premium to age. Feature selection was conducted using Pearson correlation and mutual information to identify the most influential features for modeling. The selected features included previously insured, region code, vehicle age, vehicle damage, policy sales channel, age category, and vehicle damage age interaction. These features were then used for the modeling phase.
</p>
<p align="center">
The modeling phase involved comparing the performance of various machine learning models, including XGBoost, Random Forest, Adaboost, LightGBM, CatBoost, and KNN. The models were evaluated based on metrics such as accuracy, precision, recall, F1 score, and mean ROC-AUC. The results indicated that the models exhibited similar performance across the metrics. Furthermore, the feature importance analysis revealed that the "previously insured" feature had the most significant influence on customer interest in vehicle insurance. Based on these findings, the team recommended prioritizing customers who had not previously subscribed to vehicle insurance, focusing on region code 28, and targeting customers with a medium premium to age ratio for marketing efforts. The team's simulation showed that using the predictive model for marketing efforts increased the conversion rate by 47.1%, leading to a significant improvement in revenue and a reduction in customer acquisition costs.
</p>

[Documentation Details](https://github.com/Theofilusarifin/Insurance-Cross-Selling-Prediction/blob/main/Documentation.pdf)

---

##  Repository Structure

```sh
└── Insurance-Cross-Selling-Prediction/
    └── Code
        ├── EDA - Data200.ipynb
        ├── Modeling
        │   ├── AdaBoostClassifier_Ujang.ipynb
        │   ├── Catboost_Arifin.ipynb
        │   ├── decision trees_Ramlan.ipynb
        │   ├── k_nearest_neighbors.ipynb
        │   ├── Lightgbm_Arifin.ipynb
        │   ├── LogisticRegression.ipynb
        │   ├── Random_Forest_iqbal.ipynb
        │   └── XGBoost_Arifin.ipynb
        ├── modeling - Data 200.ipynb
        └── preprocessing - Data200.ipynb
```

---

##  Getting Started

***Requirements***

Ensure you have the following dependencies installed on your system:

* **JupyterNotebook**: `python 3.9`

###  Installation

1. Clone the Insurance-Cross-Selling-Prediction repository:

```sh
git clone https://github.com/Theofilusarifin/Insurance-Cross-Selling-Prediction
```

2. Change to the project directory:

```sh
cd Insurance-Cross-Selling-Prediction
```

3. Install the dependencies:

```sh
pip install -r requirements.txt
```

###  Running Insurance-Cross-Selling-Prediction

Use the following command to run Insurance-Cross-Selling-Prediction:

```sh
jupyter nbconvert --execute notebook.ipynb
```

###  Tests

To execute tests, run:

```sh
pytest notebook_test.py
```

---


##  Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Submit Pull Requests](https://github/Theofilusarifin/Insurance-Cross-Selling-Prediction/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github/Theofilusarifin/Insurance-Cross-Selling-Prediction/discussions)**: Share your insights, provide feedback, or ask questions.
- **[Report Issues](https://github/Theofilusarifin/Insurance-Cross-Selling-Prediction/issues)**: Submit bugs found or log feature requests for Insurance-cross-selling-prediction.

<details closed>
    <summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your GitHub account.
2. **Clone Locally**: Clone the forked repository to your local machine using a Git client.
   ```sh
   git clone https://github.com/Theofilusarifin/Insurance-Cross-Selling-Prediction
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to GitHub**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.

Once your PR is reviewed and approved, it will be merged into the main branch.

</details>

---

##  Acknowledgments

- List any resources, contributors, inspiration, etc. here.

[**Return**](#-quick-links)

---
