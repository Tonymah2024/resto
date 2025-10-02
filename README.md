Restaurant Analytics Dashboard Demo

This is an interactive, single-page web application that demonstrates a modern dashboard for analyzing a restaurant's daily performance. The project is built for a fictional Canadian restaurant, "UrbanBites Bistro".

The dashboard is built entirely with front-end technologies and uses Google's Gemini API to generate AI-powered insights from the displayed data.

Live Demo: https://tonymah2024.github.io/resto/

Key Features

    At-a-Glance KPIs: Key Performance Indicators are prominently displayed for a quick overview of the day's success, including:

        Total Revenue (CAD)

        Average Check Size (CAD)

        Total Covers (Guests Served)

        Table Turnover Rate

    Interactive Data Visualization:

        Hourly Sales Performance: A line chart showing revenue generated throughout the day.

        Sales by Category: A doughnut chart breaking down sales between Food, Beverages, and Desserts.

        Top 5 Selling Items: A horizontal bar chart to quickly identify the most popular menu items.

        Customer Satisfaction: A doughnut chart visualizing customer feedback scores.

    AI-Powered Insights: A "Generate Insights" button uses the Google Gemini API to analyze the current data and provide an executive-level summary and actionable advice from the perspective of a restaurant operations analyst.

    Custom Data Loading: A "Load Data" feature allows you to upload your own local .json file to populate the dashboard with custom data sets. The required JSON structure is documented in the index.html file.

Technologies Used

    HTML5 for the core structure.

    Tailwind CSS for modern and responsive styling.

    Chart.js for creating interactive and beautiful charts.

    Google Gemini API for generative AI features.

How to Run Locally

    Download the index.html file.

    Open it in any modern web browser.

    When prompted, enter your Google AI API key to enable the "Generate Insights" feature.
