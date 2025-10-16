<p align="center">
 <img width="100%" src="./images/project-banner.png " align="center" alt="Project banner" />
 <h1 align="center">Health Insurance Cost Analysis</h1>
 <p align="center">Analysing health insurance cost data from Kaggle.</p>
</p>

<p align="center">
  <br/>
  <a href="https://www.python.org/" title="Python official website">
    <img alt="Python Logo" height="30px" src="./images/python-logo.png" />
  </a>
  <a href="https://pandas.pydata.org/" title="Pandas official wesbite">
    <img alt="Pandas Logo" height="30px" src="./images/pandas-logo.png" />
  </a>
   <a href="https://matplotlib.org/stable/" title="Matplotlib offical website">
    <img alt="Matplotlib Logo" height="30px" src="./images/matplotlib-logo.png" />
  </a>
  <a href="https://seaborn.pydata.org/" title="Seaborn offical website">
    <img alt="Seaborn Logo" height="30px" src="./images/seaborn-logo.png" />
  </a>
  <a href="https://plotly.com/python/" title="Plotly offical website">
    <img alt="Plotly Logo" height="30px" src="./images/plotly-logo.png" />
  </a>
  <a href="https://www.kaggle.com/" title="Kaggle offical website">
    <img alt="Kaggle Logo" height="30px" src="./images/kaggle-logo.png" />
  </a>
  <br />
</p>

<p align="center">
  <a href="https://github.com/users/petedanielsmith/projects/2">Project Board</a>
  &nbsp;&nbsp;-&nbsp;&nbsp;
  <a href="./jupyter_notebooks/data_cleanup.ipynb">Data Cleanup</a>
  &nbsp;&nbsp;-&nbsp;&nbsp;
  <a href="./jupyter_notebooks/data_visualisation.ipynb">Data Visualisation</a>
   &nbsp;&nbsp;-&nbsp;&nbsp;
  <a href="#conclusions">Conclusions</a>
  <br/><br/><br/>
</p>

<details>
<summary>Table of contents (Click to show)</summary>

- [Dataset Content](#dataset-content)
- [Business Requirements](#business-requirements)
- [Hypothesis and how to validate?](#hypothesis-and-how-to-validate)
- [Project Plan](#project-plan)
- [The rationale to map the business requirements to the Data Visualisations](#the-rationale-to-map-the-business-requirements-to-the-data-visualisations)
- [Analysis techniques used](#analysis-techniques-used)
- [Ethical considerations](#ethical-considerations)
- [Unfixed Bugs](#unfixed-bugs)
- [Development Roadmap](#development-roadmap)
- [Conclusions](#conclusions)
- [Main Data Analysis Libraries](#main-data-analysis-libraries)
- [Credits](#credits)
  - [Content](#content)
  - [Media](#media)
- [Acknowledgements](#acknowledgements)

</details>

<p>

</p>

<details>
<summary>How to use this repo (Click to show)</summary>

**Make sure you have:**

- Python installed, this project used V3.12,
- VS Code latest

**Inside VS Code:**

Open Extensions (Ctrl+Shift+X or ⇧⌘X on macOS)
Install these extensions if you don't have them:

- Python extension (by Microsoft in the Extensions Marketplace)
- Jupyter extension (also by Microsoft)

**From the terminal:**

Open the folder in a terminal where you want the project to be saved

#### Run git clone:

```
git clone https://github.com/petedanielsmith/HealthcareInsuranceDataAnalyticsProject.git
```

#### Navigate in to the new folder:

```
cd HealthcareInsuranceDataAnalyticsProject
```

#### Setup a virtual enviroment:

Create a virtual enviroment for the project.

Linux / Mac:

```
python3 -m venv .venv
source .venv/bin/activate
```

Windows CMD:

```
python3 -m venv .venv
.venv\Scripts\activate
```

Windows PowerShell:

```
python3 -m venv .venv
.\.venv\Scripts\Activate.ps1
```

#### Install the dependancies:

This will install all the dependancies needed for the project in to the virtual enviroment if it is setup, rather than globally

```
pip install -r requirements.txt
```

#### Select the Kernel

There is a drop down at the top of the notebooks to select your kernal that will run the Python.
If you setup a virtual enviroment then make sure you pick the venv one.

---

</details>

<p>
<br/>
</p>

## Dataset Content

The dataset used in this project can be downloaded from [Kaggle: Healthcare Insurance Dataset](https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance). It contains information on the relationship between personal attributes, geographic factors, and their impact on medical insurance charges

**Columns include:**

- `age` - The insured persons age.
- `sex` - Gender (male or female) of the insured.
- `bmi` - (Body Mass Index): A measure of body fat based on height and weight.
- `children` - The number of dependents covered.
- `smoker` - Whether the insured is a smoker (yes or no).
- `region` - The geographic area of coverage.
- `charges` - The medical insurance costs incurred by the insured person.

## Business Requirements

Analyse healthcare insurance data to understand how personal attributes and geographic factors influence insurance costs.

## Hypothesis and how to validate?

| Hypothesis                                                | How to validate?                         |
| --------------------------------------------------------- | ---------------------------------------- |
| Smokers have higher insurance charges                     | Use charts to visualise the distribution |
| People with higher BMI have higher insurance charges      | Use charts to visualise the distribution |
| Geographic region influences insurance charges            | Use charts to visualise the distribution |
| Sex of a person influences insurance charges              | Use charts to visualise the distribution |
| Including children on an insurance plan increases charges | Use charts to visualise the distribution |

## Project Plan

The prjoject follows the following steps:

1. `Extract` - Extract the data from Kaggle.
2. `Load` - Load the CSV via Pandas.
3. `Transform` - Clean and process the data using Pandas, adding new columns and checking for missing or duplicated values.
4. `Visualise` - Creating charts with Matplotlib, Seaborn and Plotly to visualise trends.
5. `Analyse` - Interpret what the visualisations displayed.
6. `Document` - Record findings and conclusions.

## The rationale to map the business requirements to the Data Visualisations

## Analysis techniques used

## Ethical considerations

The data was already anonymised and contained no data that could be used to identify an individual so there were no ethical concerns.

## Unfixed Bugs

## Development Roadmap

## Conclusions

## Main Data Analysis Libraries

## Credits

### Content

### Media

## Acknowledgements
