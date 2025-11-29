# GroupFinalProject

QuickRoute AI
Project Description

QuickRoute AI is an eco-friendly, AI-powered route optimization tool designed to help drivers choose the most fuel-efficient and environmentally sustainable routes.
Unlike traditional navigation systems that only focus on speed or distance, QuickRoute AI predicts fuel consumption using machine learning and classifies routes based on efficiency.
The tool aims to reduce fuel costs, carbon emissions, and unnecessary environmental impact through data-driven decision making.

Team Members and Roles

Name: Xander Crawley, Role: (So far everything.)

Name: Ayden Smith, Role: (So far nothing since I haven't been contacted yet and my discussion didn't recieve a reply.)

Overview of the AI Concept & Algorithm Used

QuickRoute AI uses supervised machine learning to analyze route characteristics and predict their fuel efficiency. The system integrates two key models:

1. Regression Model – Fuel Consumption Prediction

Algorithm: Random Forest Regressor (or Linear Regression)

Purpose: Predict estimated fuel used (L) for a given route

Inputs:

Distance

Average speed

Elevation gain

Traffic level

Temperature / weather

Output: Numerical prediction of fuel consumption for the route

2. Classification Model – Route Efficiency Labeling

Algorithm: Decision Tree Classifier (or Logistic Regression)

Purpose: Label each route as Efficient or Inefficient

Inputs: Same route features as regression

Output: Efficiency category for user comparison

Data Handling

Training data can come from open fuel-consumption datasets or simulated trip data created by varying factors such as distance, elevation, and traffic.
Both data types are anonymized and contain no personal information.

Ethical Considerations
1. Data Privacy

Although QuickRoute AI can be trained on simulated or publicly available datasets, any real-world route data could contain sensitive location information.
Mitigation:

Use only anonymized or synthetic data

Avoid storing raw location details

Document data sources transparently

2. Algorithmic Bias

Models may unintentionally favor certain types of routes (e.g., flat terrain) based on training data.
Mitigation:

Evaluate models on diverse route conditions

Perform fairness testing and feature-impact analysis

Clearly disclose model limitations in documentation

3. Environmental Claims Transparency

While QuickRoute AI promotes sustainability, predictions may not always match real-world outcomes due to traffic or driver behavior.
Mitigation:

Display confidence intervals and disclaimers

Emphasize the model as a decision support tool, not an exact measurement

Target Users

  1. Everyday drivers who want to save fuel

  2. Delivery fleets aiming to reduce operational costs

  3. Students and researchers working with smart mobility tools

  4. Eco-conscious users interested in sustainable travel

Links to Slides and Recordings

