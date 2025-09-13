
# U.S. Airlines Sentiment Analysis (Interactive Dashboard)

## Project Description

This project presents an interactive dashboard designed to analyze the "pain points" of customers flying with various domestic U.S. airlines. It stems from the need to research the U.S. aviation industry market, understand customer sentiment, and report findings to stakeholders and company decision-makers, such as marketing executives, communications and press departments, or investment teams.

The information is obtained from social media data (specifically tweets from Twitter in the U.S.) that mention airlines such as Delta, United, Southwest Airlines, Virgin America, among others. The data was obtained from the U.S. Airlines Sentiment dataset on Kaggle, where it was collected and formatted, including tweet ID, sentiment (positive, neutral, or negative), location, and tweet text, all stored in a CSV file.

The dashboard was developed in Python, using charting libraries like Plotly to create data visualizations. Its objective is to offer stakeholders a quick and simple way to explore relevant data themselves and select the visualizations that interest them most in an interactive manner.

## Key Features

The interactive dashboard offers the following functionalities:

• **Real Tweet Examples by Sentiment**: Users can click on "positive," "neutral," or "negative" to see a random tweet from the dataset corresponding to that sentiment.

• **Tweet Count Visualization by Sentiment**: An interactive chart shows the overall sentiment distribution, with the option to view data as either a bar chart or pie chart.

• **Geographic Distribution of Tweets**: A map shows the locations from where users tweeted, with major clusters identified, for example, in California, the Midwest, and near Manhattan/New York.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/2805b98c-60c4-4c36-8d42-b2d613da65cb" />


• **Airline Popularity and Sentiment Breakdown**: Allows users to see which airlines have been tweeted about the most. Additionally, sentiment can be broken down for specific airlines (for example, by clicking on United, you can see that most tweets are negative despite its popularity) and compare multiple airlines.

• **Word Cloud by Sentiment**: A visualization where the font size of a word indicates its frequency in the dataset, broken down by sentiment.

• **Smart Caching Mechanism**: Uses a simple Streamlit function decorator to cache data, improving performance by avoiding reloading and repeating calculations unless input data is modified.

## How It Works

The dashboard is designed to run on an internal server (company or through VPN), allowing colleagues and other stakeholders to access the data and report conclusions.

The web application was built using Streamlit, which enabled creating all the interactivity and user interface components using pure Python code.

## Technologies Used

• **Python**: Primary programming language for data analysis and dashboard creation.
• **Streamlit**: Framework for building interactive web applications and dashboards with ease.
• **Plotly**: Library for creating interactive and attractive data visualizations.

## Usage

To use this dashboard, it can be run on the company server or through a VPN. Users can interact with different components, such as clicking on tweet examples, toggling between chart types, selecting airlines for detailed analysis, and exploring the word cloud.

This project is inspired by the vision of making machine learning and data science tool development as easy as writing Python scripts. Streamlit demonstrates that this is certainly possible, facilitating the creation of interactive and effective dashboards with minimal code.
