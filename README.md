# Hotel Booking Cancellation Project

Behind every hotel booking lies a combination of customer decisions, reservation details, and travel patterns. These factors collectively influence whether a booking ultimately results in a successful stay or a cancellation.

This project aims to uncover the key drivers behind cancellation behaviour through a comprehensive exploratory data analysis. The investigation consists of univariate, bivariate, multivariate, and statistical analyses, each designed to reveal patterns, relationships, and insights hidden within the data.

The findings obtained throughout the analysis are then used to guide feature selection and support the development of a predictive machine learning model capable of estimating the likelihood of a booking being cancelled.

## Content

1. [Exploratory Data Analysis](./data-exploration/README.md)
2. [Data Preprocessing]
3. [Model Development]
4. [Model Evaluation]

## Build Configuration 

The project environment can be recreated using the provided `environment.yml` file.
```bash
conda env create -f enviroment.yml
conda activate hotel_booking
jupyter lab
```

## Repository Structure

```text
hotel-booking-project/
│
├── data/
├── data-exploration/
├── data-preprocessing/
├── model-development/
├── model-evaluation/
├── README.md
└── environment.yml
```