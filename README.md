E2E CICD Pipeline
==============================

Built End2End CI/CD Pipeline using GitHub Actions, Docker, Amazon ECR, and hosted it to AWS EC2.

#### CICD Workflow Status :
[![build docker img](https://github.com/ronylpatil/cicd-aws/actions/workflows/pull_img.yaml/badge.svg)](https://github.com/ronylpatil/cicd-aws/actions/workflows/pull_img.yaml)
[![continuous deployment](https://github.com/ronylpatil/cicd-aws/actions/workflows/continuous_deployment.yaml/badge.svg)](https://github.com/ronylpatil/cicd-aws/actions/workflows/continuous_deployment.yaml)

## Workflow
<p align = "center">
  <img class="center" src = "https://github.com/ronylpatil/cicd-aws/blob/main/workflow/workflow.png" alt = "Drawing">
</p>

## Installation

1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`

## Folder Structure

- `/src`: Contains the source code.
- `/data`: Stores raw and processed data.
- `/.github`: Contain the ci/cd workflow file.
- `/figures`: Contains the plots generated during model experimentations.
- `/log`: Store the log files.
- `/prod`: Production files. 

## Dataset

- Download the dataset from [here](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset).

___
