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

some of the worksheet data dont have question types
