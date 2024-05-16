### Project Description

Mobile operator "Megaline" has discovered that many customers are using legacy tariff plans. They want to build a system capable of analyzing customer behavior and offering users a new tariff: "Smart" or "Ultra."

You have access to data on the behavior of customers who have already switched to these tariffs. The task is to build a classification model that will select the appropriate tariff. Data preprocessing is not required - you've already done it.

Build a model with the highest possible accuracy. To pass the project successfully, you need to achieve an accuracy of at least 0.75. Verify the accuracy on the test set independently.

### Project Execution Instructions

1. Open the data file and study it. File user_behavior.csv

2. Split the raw data into training, validation, and test sets.

3. Explore the quality of different models by varying hyperparameters. Write brief conclusions from the study.

4. Evaluate the model's quality on the test set.

5. Extra task: Check the models for adequacy. Don't worry if it doesn't work out - these data are more complex than those you've worked with before. We'll delve into this more in the next course.

### Data Description

Each object in the dataset represents information about the behavior of one user for a month. It includes:

- **calls:** Number of calls.
- **minutes:** Total duration of calls in minutes.
- **messages:** Number of SMS messages.
- **mb_used:** Internet traffic used in MB.
- **is_ultra:** Tariff used during the month ("Ultra" — 1, "Smart" — 0).
