# Proposal

At most one page. Replace the prompts under each heading. Leave the headings.

## Hypothesis

Machine learning can predict the number of days until a computer component fails based on its operating conditions, usage, and sensor measurements.

## Data

The data will come from a publicly available predictive maintenance dataset, such as the AI4I 2020 Predictive Maintenance Dataset from the UCI Machine Learning Repository. Each observation represents one simulated industrial machine operating instance. The dataset contains 10,000 records and was generated to model predictive maintenance conditions. It includes operating temperatures, rotational speed, torque, tool wear, and machine failure labels. The dataset does not directly measure the number of days until a computer component fails, so the project will estimate failure risk rather than exact time to failure unless suitable time-based failure data are available.

## Decision affected by the model

IT technicians and maintenance managers will use the model's predictions to identify equipment that may need inspection or replacement before failure occurs. Failing to identify a component that is about to fail may cause unexpected downtime and costly repairs, while predicting a failure that does not occur may lead to unnecessary maintenance.
