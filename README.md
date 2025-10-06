# data-science-learning
This repo contains my data science learning assignments.
Titanic Passenger Survival Analysis
Overview

This project analyzes Titanic passenger data to identify factors affecting survival during the disaster. Using Python and pandas, we explored how demographics, ticket info, and family size relate to survival rates.

Dataset

Contains 714 passengers with variables such as Survived, Pclass, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, and Embarked.

Approach

Loaded and cleaned data with pandas.

Created new features:

FamilySize = SibSp + Parch + 1

TravelGroup (Small: 1–2, Large: 3+)

Fare_level (High/Low based on median)

Age_group (binned age ranges)

Grouped data by demographics and features to calculate survival rates.

Key Findings

Females and first-class passengers had higher survival rates.

Smaller travel groups showed different survival trends compared to large families.

Higher fare payers and younger passengers were more likely to survive.

Survival rates varied by embarkation port.

Tools

Python (pandas, numpy) for data processing and analysis.

Grouping, aggregation, and feature engineering techniques were applied.

Usage

Run the provided scripts or notebook with Titanic CSV data to reproduce analyses and outputs.
