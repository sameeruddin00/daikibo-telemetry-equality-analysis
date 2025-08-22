# Daikibo Telemetry & Gender Equality Analysis
Project Overview

This project analyzes telemetry data from Daikibo factories to identify machine downtime patterns and evaluates gender pay equality across job roles. The analysis was performed using Tableau for visualization and Excel for data classification.

Project Objectives

Telemetry Analysis

Identify which factory experiences the most machine downtime.

Determine which types of machines break most frequently.

Gender Pay Equality Analysis

Classify job roles into categories based on equality scores:

Fair: Score between -10 and +10

Unfair: Score < -10 or > 10

Highly Discriminative: Score < -20 or > 20

Data Description

Telemetry Data: JSON file containing machine status messages every 10 minutes from 4 factories over one month.

Equality Data: Excel file with factory, job role, and equality score.

Methods

Telemetry Analysis in Tableau

Imported JSON data.

Created calculated field Unhealthy (10 minutes per unhealthy message).

Created bar charts:

Down Time per Factory

Down Time per Device Type

Built a dashboard connecting the two charts to filter by factory.

Gender Equality Classification

Added a new column Equality Class in Excel.

Classified equality scores according to the thresholds above.
