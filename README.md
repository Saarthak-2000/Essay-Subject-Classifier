Essays are an important part of any high school curriculum. A high school is trying to categorize the sentences that are present in the essays written by students and demarcate what topics have used. 
Task Your task is to process the different sentences and correctly classify them into their respective categories.
Data Description The dataset folder contains the following files: train.csv: 10000 x 3 test.csv: 4020 x 2 sample submission.csv: 5 x 2 
The columns provided in the dataset are as follows: 

📁 Dataset Column Descriptions

| **Column Name** | **Description**                                               |
|------------------|---------------------------------------------------------------|
| `ID`             | Unique identifier for each text entry                         |
| `Text`           | The actual sentence or excerpt from a student's essay         |
| `Subject`        | The category or subject that the essay sentence belongs to    |

Evaluation metric score =100*f1_score(actual, predicted, average='macro') Result submission guidelines The index is ID and the target is the Subject column. 
The submission file must be submitted in .csv format only. The size of the submission file must be 4020 x 2. 
Note: Ensure that your submission file contains the following: Correct index values as per the test file Correct names of columns as provided in the sample_submission.csv file Uploading the source code is mandatory.
Failure to do so will result in disqualification.

Absolutely! Here's a clean and structured table summarizing the dataset and task details for your GitHub README or documentation:

### 📊 Project Overview Table

| **Category**              | **Details**                                                                 |
|---------------------------|------------------------------------------------------------------------------|
| **Project Title**         | Essay Subject Classification                                                |
| **Objective**             | Classify student essay sentences into their respective subject categories   |
| **Dataset Files**         | `train.csv`, `test.csv`, `sample_submission.csv`                            |
| **Train File Size**       | 10,000 rows × 3 columns                                                      |
| **Test File Size**        | 4,020 rows × 2 columns                                                       |
| **Sample Submission Size**| 5 rows × 2 columns                                                           |
| **Columns in Dataset**    | `ID` (Text ID), `Text` (Essay Sentence), `Subject` (Target Category)         |
| **Evaluation Metric**     | `score = 100 × f1_score(actual, predicted, average='macro')`                |
| **Submission Format**     | `.csv` file with 4,020 rows × 2 columns (`ID`, `Subject`)                    |
| **Submission Requirements**| Must match `test.csv` index and column names from `sample_submission.csv` |
| **Disqualification Rule** | Source code upload is **mandatory**                                         |

