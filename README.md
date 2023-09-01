# Target-tuition-Grade-predictor-hackathon


1. **Data Collection and Understanding:**
   - Review the structure and contents of each file and folder provided to understand how the data is organized.
   - Examine the "Mock Exam Data (Labelled).xlsx" and "worksheet data.xlsx" spreadsheets to see the layout of the student response data.
   - Understand the information present in the "student profiles" spreadsheet and the "question key."

2. **Data Preprocessing:**
   - Merged the information from the "student profiles" spreadsheet with the response data to incorporate student details.
   - created a column 'is_right' to indicate if a student's answer is right or wrong.
   - created a column for the scores of each student ( expressed as a percentage).
   - Calculated metrics like Difficulty Index and Discrimination Index for each question based on the responses.
   - calculated the percentage of correct answers for each question type of all students.
   - calculated each students age in years and months.
     


3. **Feature Engineering:**
   - Extract features from the student response data such as the question type, difficulty index,genre, age, score
   - 

4. **Exploratory Data Analysis (EDA):**
   - Analyze the distribution of percentage of correct answers for each question types, to gain  insight into how students are performing and help identify patterns and trends. 
    

5. **Data Splitting:**
   - Split the data into training, and test sets to evaluate the performance of predictive models.

6. **Predictive Modeling (Part 1):**
   - Select appropriate machine learning algorithms (e.g., classification models) to predict whether a student's response is correct or incorrect.
   - Train the models using the training data and fine-tune hyperparameters using the validation set.
   - Evaluate model performance using metrics like accuracy, precision, recall, and F1-score.

**Labeling Dilemma in Question Types**

In the process of working on the project, an issue regarding the labeling of question types has surfaced. While the mock exam data spreadsheet provides clear labels for question types, the worksheet data spreadsheet lacks consistent labeling. This discrepancy makes it challenging to accurately categorize certain question types.I have encountered instances where questions are labeled as 'Phrases' (evident in the 'Frost Passage' - questions 1, 4, 6, 7) and 'Writing Technique'. Regrettably, the exact meanings for these particular question types were not explicitly provided in the 'Question Key' workbook.

Furthermore, some questions have been labeled as 'Understanding' without specifying whether this pertains to 'Understanding Factual Recall' or 'Understanding Inference'. An example of this can be found in the 'Tyger Passage' word document. These labeled entries will be used as training data to develop the prediction model effectively. However, I will be working with the sheets on the worksheet data that are already labeled.
