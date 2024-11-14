================
Project Overview
================

In this documentation, we'll outline the strategic steps taken to achieve the specified deliverables in the project.


Background
==========
The sales group of a technology and chip manufacturing company is provided with annual targets in $ that they need to sell. The team tries to achieve the same by pursuing multiple opportunities (an opportunity can be defined as a potential customer with specific asks of products in type, design and quantity with their $ values negotiated) across customers and business segments.
The sales enablement group of the same organization has identified that while a number of opportunities are being pursued, the sales group lacks a means to quantify the potential of conversion of these group of opportunities (hereon referred as sales pipeline portfolio) within a specific timeframe (say a quarter). The conversion potential of a sales pipeline portfolio is realized by,
- Quality of an opportunity: How likely is an opportunity to convert within a specific timeframe?


Evaluation
==========

1. Understanding Opportunity Line Movements:
   - Analyzing the flow of opportunities through different stages.
   - Visualize the transition between stages using pictorial representations.
   - Formulate and test hypotheses related to stage transitions.
   - Identifying any trends between the datasets to better track the timeline of Sales.

2. Score Opportunities for Likelihood of Conversion:
   - Merge Opportunity with Product data (monthly snapshot).
   - Create a dependent variable based on movement to a "win" stage.
   - Develop a logistic regression model for predicting the likelihood of conversion.

3. Identifying Key Drivers:
   - Correlating the sales data with different features to understand which features have the most significant impact on product sales.
   - Identifying the key factors driving sales performance, which will assist the client in optimizing their product offerings and marketing strategies.
   - Utlising ML model Feature importances to tap into more important sales drivers.

The insights gained from this analysis will enable Manufacturer A to make data-driven decisions, enhance brand positioning, and strengthen its market presence.