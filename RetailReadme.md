{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "3cb2737c",
   "metadata": {},
   "source": [
    "# 🛒 Retail Sales Prediction using Machine Learning\n",
    "\n",
    "This project uses a real-world retail dataset to build machine learning models that predict daily sales (`venda`) based on features like stock (`estoque`), price (`preco`), and date components (day, month, weekday, etc.).\n",
    "\n",
    "---\n",
    "\n",
    "## 📂 Dataset\n",
    "\n",
    "The dataset includes:\n",
    "\n",
    "- `data`: Date of the record\n",
    "- `venda`: Number of units sold (target variable)\n",
    "- `estoque`: Inventory available\n",
    "- `preco`: Product price\n",
    "\n",
    "Date features (`year`, `month`, `day`, `day_of_week`) were extracted to improve model performance.\n",
    "\n",
    "---\n",
    "\n",
    "## 🎯 Objective\n",
    "\n",
    "Predict the number of items sold on a given day based on historical pricing, inventory, and calendar features.\n",
    "\n",
    "---\n",
    "\n",
    "## 📈 Models Used\n",
    "\n",
    "### 1. Linear Regression\n",
    "- Simple and interpretable model.\n",
    "- **R² Score**: ~0.22\n",
    "\n",
    "### 2. XGBoost Regressor\n",
    "- Handles non-linearity and interactions well.\n",
    "- **R² Score**: ~0.42\n",
    "- **Conclusion**: XGBoost significantly outperformed Linear Regression in terms of both MAE and R².\n",
    "\n",
    "---\n",
    "\n",
    "## 🧪 Evaluation Metrics\n",
    "\n",
    "- **MAE (Mean Absolute Error)**\n",
    "- **MSE (Mean Squared Error)**\n",
    "- **R² Score**\n",
    "\n",
    "---\n",
    "\n",
    "## 🛠️ Requirements\n",
    "\n",
    "Install dependencies:\n",
    "\n",
    "```bash\n",
    "pip install -r requirements.txt\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "dd186d65",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.9.13"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
