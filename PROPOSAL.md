# Proposal

At most one page. Replace the prompts under each heading. Leave the headings.

## Hypothesis

Machine learning can predict whether a computer hard drive will fail within the next 30 days based on its temperature, usage, and age.

## Data

The data will come from a publicly available computer hardware failure dataset, such as the Backblaze Hard Drive Test Data. The unit of observation will be an individual hard drive recorded on a specific date. The sample size will depend on the selected dataset files. The data include daily drive information, such as temperature, operating hours, and failure status. The data are collected through hard drive monitoring systems. The measured information represents recorded drive conditions and failure history, while the decision requires predicting whether a drive will fail within the next 30 days.

## Decision affected by the model

IT maintenance teams will use the predictions to identify hard drives that may need replacement before they fail. A false negative costs more because it could result in data loss and downtime. For example, if the model identifies a hard drive with a high probability of failure, technicians can prioritize that drive and transfer important files to another storage device before the failure occurs. This can help organizations protect important business information, maintain reliable computer systems, reduce unexpected repair expenses, and prevent interruptions to daily operations. The model can also help IT managers plan their hardware replacement budgets and determine which equipment needs attention first.
