## Intelligent-Credit-Card-Usage-Cashback-Optimization-Platform

An AI-assisted machine learning and analytics platform that converts raw credit card transaction data into intelligent usage recommendations, cashback optimization insights, and early risk alerts. The system analyzes multi-card spending behavior across merchants, categories, and time periods to help users make better card decisions and reduce reward loss and financial risk.

This project combines data engineering, feature engineering, supervised and unsupervised ML models, anomaly detection, and stakeholder-friendly visualizations to build a practical fintech decision engine.

🎯 Problem Statement

Many users actively track their spending but still lose rewards and incur avoidable risk because: • multiple credit cards have different reward rules • cashback categories rotate or have caps • subscriptions increase silently • spending patterns shift month to month • credit utilization risk is detected too late • raw transaction logs don’t translate into decisions

Tracking alone answers “what happened” — but not “what should I do next?”

This project focuses on building a system that answers:

Which card should be used for a purchase, and when is spending behavior become risky?

🧠 Project Objectives • Build a multi-card spend intelligence pipeline • Engineer reliable monthly & yearly aggregation features • Detect abnormal and risky spending behavior • Predict credit-limit breach risk early • Identify subscription spikes and merchant anomalies • Generate customer-care risk signals • Evaluate models using precision, recall, and F1 • Produce non-technical visual dashboards • Create a foundation for real-time card recommendation systems

🗂 Data Scope

The dataset includes structured transaction and card metadata such as: • customer identifiers • multiple cards per user • merchant names • spend categories • transaction dates • transaction amounts • credit limits • monthly & yearly spend aggregates • subscription merchants • anomaly and risk labels

Edge cases were intentionally included: • inconsistent categories • string-based dates • mismatched aggregations • subscription spikes • credit-limit breach scenarios
