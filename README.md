# Sparkify: Customer Churn Prediction of a Music Streaming Service Using Spark

This project analyzes and predicts customer churn of a music streaming service using Spark on a large dataset.

I took the starter code for this repository from a Udacity assignment project and modified it to the present form, which deviates significantly from the original form; see [`starter`](starter).

The project focuses on an imaginary music streaming service, similar to Spotify, where users can listen to streamed music. In that service:

- We have: (1) free-tier users and (2) premium users who pay a subscription.
- Every time an user is involved in an event, it is logged with a timestamp; example events: `songplay`, `logout`, `like`, `ad_heard`, `downgrade`, etc.

The goal is to predict customer churn, either (1) as a downgrade from the premium to free plan or (2) in form of a user leaving the service. With churn predictions, the company can target those users with incentives, such as discounts, etc.

:construction: On-going work.

Contents:

- [ ] A
- [ ] B
- [ ] ...

## Table of Contents

- [Sparkify: Customer Churn Prediction of a Music Streaming Service Using Spark](#sparkify-customer-churn-prediction-of-a-music-streaming-service-using-spark)
  - [Table of Contents](#table-of-contents)
  - [Dataset](#dataset)
  - [How to Use This Project](#how-to-use-this-project)
    - [Installing Dependencies for Custom Environments](#installing-dependencies-for-custom-environments)
  - [Notes on the Theory](#notes-on-the-theory)
  - [Notes on the Implemented Analysis and Modeling](#notes-on-the-implemented-analysis-and-modeling)
  - [Results and Conclusions](#results-and-conclusions)
  - [Next Steps, Improvements](#next-steps-improvements)
  - [References and Links](#references-and-links)
  - [Authorship](#authorship)


## Dataset

:construction: TBD.

## How to Use This Project

:construction: TBD.

The directory of the project consists of the following files:

```
.
├── Instructions.md
...
```

### Installing Dependencies for Custom Environments

If you'd like to control where the notebook runs, you need to create a custom environment and install the required dependencies. A quick recipe which sets everything up with [conda](https://docs.conda.io/en/latest/) is the following:

```bash
# Create environment with YAML, incl. packages
conda env create -f conda.yaml
conda activate sparkify

# Or
conda create --name rec-ibm pip python=3.9
conda activate sparkify
# and install version-specific pip dependencies
pip install -r requirements.txt

# To track any changes and versions you have
conda env export > conda.yaml
pip list --format=freeze > requirements.txt
```

List of most important dependencies:

- A
- B

## Notes on the Theory

:construction: TBD.

## Notes on the Implemented Analysis and Modeling

:construction: TBD.

## Results and Conclusions

:construction: TBD.

## Next Steps, Improvements

:construction: TBD.

## References and Links

:construction: TBD.

- [spark_big_data_guide](https://github.com/mxagar/spark_big_data_guide)
- [data_science_udacity](https://github.com/mxagar/data_science_udacity)
- [sql_guide](https://github.com/mxagar/sql_guide)
- [eda_fe_summary](https://github.com/mxagar/eda_fe_summary)


## Authorship

Mikel Sagardia, 2023.  
No guarantees.

If you find this repository useful, you're free to use it, but please link back to the original source.
