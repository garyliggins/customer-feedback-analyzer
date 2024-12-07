Customer Feedback Analyzer

Overview

The Customer Feedback Analyzer is a ServiceNow application that integrates with Google’s Natural Language API to analyze feedback sentiment. It automates categorization, provides actionable insights, and visualizes trends through dashboards.

Features

Real-time sentiment analysis.

Automatic categorization (Positive, Neutral, Negative).

Task creation for negative feedback.

Dashboards for sentiment trends.

Setup Instructions

Clone the Repository

git clone https://github.com/your-repo/customer-feedback-analyzer.git

Set Up Google API Key

Create a project in Google Cloud Console.

Enable the Natural Language API.

Generate and copy the API key.

Configure ServiceNow

Create the Customer Feedback table.

Add the required fields.

Configure the REST Message for the Google API.

Install Scripts

Add the Script Include for API processing.

Create a Business Rule to trigger sentiment analysis.

Build Dashboards

Create visual widgets to display insights.

Usage

Add customer feedback via the Customer Feedback table.

View sentiment analysis results in the record.

Monitor trends and take actions using the dashboard.

