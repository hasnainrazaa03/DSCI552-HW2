# DSCI 552 - Homework 2

Combined Cycle Power Plant data set: simple and multiple linear regression, polynomial
and interaction models, and KNN regression.

Name: Mohammad Hasnain Raza
GitHub Username: hasnainrazaa03
USC ID: 1259246355

## Structure

```
data/CCPP/          data set (the notebook reads Sheet1 of Folds5x2_pp.xlsx)
notebook/           Raza_MohammadHasnain_HW2.ipynb
requirements.txt    package versions used
```

## Running the notebook

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
cd notebook
jupyter notebook Raza_MohammadHasnain_HW2.ipynb
```

The notebook loads the data with the relative path `../data/CCPP/Folds5x2_pp.xlsx`,
so it runs from the `notebook` folder without any change.
