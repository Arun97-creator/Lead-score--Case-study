# Lead-score--Case-study
Problem Statement
An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses.
The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%.
Now, although X Education gets a lot of leads, its lead conversion rate is very poor. For example, if, say, they acquire 100 leads in a day, only about 30 of them are converted. To make this process more efficient, the company wishes to identify the most potential leads, also known as ‘Hot Leads’. If they successfully identify this set of leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone.
X Education has appointed you to help them select the most promising leads, i.e. the leads that are most likely to convert into paying customers. The company requires you to build a model wherein you need to assign a lead score to each of the leads such that the customers with higher lead score have a higher conversion chance and the customers with lower lead score have a lower conversion chance. The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.

Lead Score Case Study
Goals of the Case Study
The goals of this case study are as follows:
- Build a logistic regression model to assign a lead score between 0 and 100 to each lead. This score can be used by the company to target potential leads. A higher score indicates a "hot" lead, which is most likely to convert, whereas a lower score indicates a "cold" lead, which is less likely to convert.
- Adapt the model to address additional problems presented by the company. These problems are detailed in a separate document and should be incorporated into your model as needed. Ensure these adjustments are included in your final presentation and recommendations.

Results Expected
- A well-commented Jupyter notebook with at least the logistic regression model, conversion predictions, and evaluation metrics.
- An overall approach to the analysis presented in a presentation.
  - Briefly mention the problem statement and the analysis approach.
  - Explain the results in business terms.
  - Include visualizations and summarize the most important results in the presentation.

 Steps Followed
1. Reading Data
2. Cleaning Data
3. Exploratory Data Analysis (EDA)
4. Creating Dummy Variables
5. Splitting Data into Train and Test Sets
6. Building the Model
7. Making Predictions
8. Model Evaluation
   - ROC Curve
   - Precision-Recall
9. Prediction on Test Set

 Details of Files Provided
- Lead-scoring-APS-FINALONE : The Jupyter Notebook file showing coding and data analysis.
- Assignment Subjective Questions with Answers.pdf: Document containing answers to subjective questions.
- Lead Score Case Study.pdf: The final presentation.
- Summary Report.pdf: A summary of what’s done in the entire Python notebook.
