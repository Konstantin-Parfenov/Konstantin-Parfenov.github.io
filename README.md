# Data science portfolio by Konstantin Parfenov

This portfolio is a compilation of my data science and machine learning projects in recent years.

## Stand-alone projects.
### Energy market counterparty bankruptcy prediction analytics system 
A client for this project is Rosenergoatom JSC. The task is to predict bankruptcy for a counterparty on a Russian wholesales energy and capacity market. 

Fundamental data extracting and transformation procedures are written in SAS Base/Macro language and scheduled daily. Scripts combine raw payment data, data from corporate sources, various scrapped data from .pdf and .html files and put them in an Oracle database. The connection between Oracle database and Atomcloud ("IBM Cloudpak for data" deployed on [Data center Kalininsky](https://www.rosenergoatom.ru/stations_projects/opornyy-tsod/)) approved by the internal Information Security Department.

Python script, which executes on a dedicated runtime described in the environment management tab, performs further data transformation, data cleaning, and data quality check. 

Model compares 6 approches.
*Logistic Regression
*Knearest Neighbours
*Support Vector Classifier
*Decision Tree Classifier
*MLP Neural Network Classifier
*Gradient Boosting Classifier

Prediction results from both, Gradient Boosting Classifier and MLP Neural Network Classifier are represented in an analytical dashboard.

The model result is a .csv file that is visualized on an analytical dashboard. 

[Short video of product description for Rosatom CEO (Alexey Likhachev)](https://user-images.githubusercontent.com/6107160/123541038-e5547000-d74a-11eb-9464-9e36329f4a12.mp4)

### Sibur PET-price Prediction

### Sibur Farction Mix Prediction

### DMP-System user classifiation


## RecSys for videocontent Megafon

## Big data Spark Projects

###

## Kaggle competitions.







Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Konstantin-Parfenov/Konstantin-Parfenov.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
