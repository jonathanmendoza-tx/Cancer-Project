# Survival After Cancer Diagnosis

You can find the project article on [Medium](https://medium.com/can-it-be-predicted/survival-after-cancer-diagnosis-eb17a8d82080).

- [Project Overview](#project-overview)
    - Tech Stack
    - Data Sources
- [Getting Started](#getting-started)
    - Locally
        - Pre-requisite python packages
        - Analyze data
- [Contributing](#contributing)
    - Issue/Bug Request
    - Feature Requests
    - Pull Requests
    - Attribution
- [Documentation](#documentation)

## Project Overview

The goal of this project was to predict the length of time a person might survive after recieving a diagnosis of cancer.
Analysis was performed on a dataset obtained from the National Institutes of Health (NIH). 
Findings and analysis are discussed in my medium article.

 - Achieved 70% accuracy for predicting survivability of a patient.

 - Analyzed and plotted relevant data to showcase the most important findings.

 - Shared findings with NIH and gained access to their private dataset for future projects.


### Tech Stack

- Jupyter
- Pandas
- numpy
- scikit-learn (Random forest classifier, K-means clustering) 
- XGBoost classifier 
- scipy
- eli5 
- Shap 
- pdpbox
- seaborn

### Data Sources

National Institutes of Health cancer dataset:
* [SEER data 1975-2017](https://seer.cancer.gov/data-software/documentation/seerstat/nov2019/)

## Getting Started

### Locally

#### Pre-requisite python packages

 - jupyterlab (or notebook)
 - seaborn
 - sklearn
 - xgboost
 - pandas
 - scipy
 - yellowbrick
 
Everything else is pip installed within the jupyter notebook

#### Analyze Data

Run the cells within the jupyter notebook. Areas of interest have been annotated with comments or in markdown sections.

## Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.

### Issue/Bug Request

 **If you are having an issue with the existing project code, please submit a bug report under the following guidelines:**
 - Check first to see if your issue has already been reported.
 - Check to see if the issue has recently been fixed by attempting to reproduce the issue using the latest master branch in the repository.
 - Create a live example of the problem.
 - Submit a detailed bug report including your environment & browser, steps to reproduce the issue, actual and expected outcomes,  where you believe the issue is originating from, and any potential solutions you have considered.

### Feature Requests

I would love to hear from you about new features which would improve this study and furthers the aims of the project. Please provide as much detail and information as possible to show why you think your new feature should be implemented.

### Pull Requests

If you have developed a patch, bug fix, or new feature that would improve this project, please submit a pull request. It is best to communicate your ideas with the developer first before investing a great deal of time into a pull request to ensure that it will mesh smoothly with the project.

#### Pull Request Guidelines

- Ensure any install or build dependencies are removed before the end of the layer when doing a build.
- Update the README.md with details of changes to the interface, including new plist variables, exposed ports, useful file locations and container parameters.
- Ensure that your code conforms to the existing code conventions.
- Include the relevant issue number, if applicable.
- Your Pull Request will be merged in once you have the sign-off of the developer.

### Attribution

These contribution guidelines have been adapted from [this good-Contributing.md-template](https://gist.github.com/PurpleBooth/b24679402957c63ec426).

## Documentation

Refer to the [SEER*stat](https://seer.cancer.gov/analysis/) website for guidance on the definitions of the data columns and values.
