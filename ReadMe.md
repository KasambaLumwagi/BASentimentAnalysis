# British Airways Sentiment Analysis of Customer Reviews

This repository contains sentiment analysis on British airways airline reviews scraapped from Skytrax website. The project uses a combination of VADER sentiment analysis and a Naive Bayes classifier to classify reviews as positive or negative, and extracts common themes from these reviews.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

The goal of this project is to analyze reviews of British Airways and determine their sentiment using both VADER sentiment analysis and a N aive Bayes classifier. Additionally, the project extracts common themes from positive and negative reviews to gain further insights.

## Dataset

The dataset used for this project is `BA_reviews.csv`, which contains customer reviews of British Airways. Each review may contain a prefix `✅ Trip Verified` that needs to be removed before analysis.

## Installation

### Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed Python 3.6 or later.
- You have a basic understanding of Python.

### Step-by-Step Installation

1. **Clone the Repository**

   Clone this repository to your local machine using Git:

   ```bash
   git clone https://github.com/your-username/sentiment-analysis-airline-reviews.git
   cd sentiment-analysis-airline-reviews
