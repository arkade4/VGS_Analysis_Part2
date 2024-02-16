# VGS_Analysis
Video Games Sales Data Analysis Project (Grad School First Year Project)

Project Guidelines and Deliverables
The Second Deliverable
The second deliverable extends the First Deliverable by focusing more on modeling your data. Do not worry if your data is not “perfect” for this part of the project. Your data will never be perfect because you still are not sure what golden nuggets you’ll find within. You will continue to iterate by performing an analysis, finding holes in your data, obtaining more data, performing another analysis, finding more holes, and on and on and on. With that said, while your data does not need to be perfect, it needs to be usable.

Within this portion of the project you will be spending time developing models to answer your question of interest. You must present at least three models! When you have adequate models you will not only choose one of them as your solution, but need to explain why it is better than the others and how it answers your question or problem.

Adjust Deliverable 1 Requirements 
The previous requirements from Deliverable 1 are refined further during this stage of the project. Do not just refer me to your Deliverable 1 document. You must type out everything again. Remember, this is your final submission of your project to your manager. 

Select Modeling Technique (15 pts.)
Now that your data is ready to go it is time to select a modeling technique. You have planned out which modeling techniques you will use in the previous stages of this project. Will you use classification and prediction by utilizing decision trees, logistic regression, or neural networks? How about estimation using regression or nearest neighbor models? You also could look at binary responses with logistic regression or decision trees. Association analyses can be fruitful.

After choosing your modeling technique, discuss any assumptions this technique makes about the data. Also, explain what you hoped to get by using this technique and what you ended up with. I want to see both your successes and failure! Learning comes from understanding your mistakes or what didn’t work right. Include the bad with the good. So, to summarize:

Explain what the goal of each modeling technique is; how does this goal relate back to your overall goal/objective? I don’t want a technical description; i.e. don’t tell me regression explains the variance in the dependent variable. I know that it does. Instead, you can say that you are using regression to explain how the Sales changes linearly based on variables x1, x2, and x3 to determine if sales of shoes are influenced by certain variables in the summer.
Another example. Assume you are investigating education drop-out rates in California high schools. Your goal for a neural network model is to estimate the ratio of drop-out-to-population based on GPA, gender, race, and socio economic status. Thus, it relates back to your overall goal by determining which independent variables are strongly predictive of high drop-outs; unlike a decision tree, this cannot classify schools based on those predictors. Remember, I asked you to specify your predictors and target variables in the Scope, so you should have alignment.
Justify your choice of models. I don’t want you to blindly follow a program. You should understand why the program chose those techniques over others. (10 pts)
Explain the assumptions of each modeling technique you will pursue. How did you assess the assumptions? If the model has no assumptions (very few do), then state this. (5 pts)
Data Splitting and Sub-Sampling (8 pts.)
Once you have a modeling technique chosen you must decide on training, testing, and validating data sets. That is, you will have three separate and distinct data sets to work on for your models. If you separate the data in any way—whether you are using software to do that or manually separating it—you need to explain why the separation occurred. If you separate the data based on a variable or attributes within the data, please explain that here. Don’t just tell me you are splitting the data. If you split 30-40-30 explain why! Why not 40-60-0?

Once you have split your data samples, briefly discuss the discrepancies between the subsets. Focus on variables. For example, if you have gender as a variable and it is 50% male and 50% female in the complete data file, but after splitting the data into three subsets you find that in the training it is 30%/70% and find in the testing data set it is 60%/40%, you need to explain this. You may find a model doesn’t perform well in the validation set based on accuracy; it is possible this is because one of your key variables wasn’t split well among your three sets.

A word about small samples. Depending on the modeling technique you choose you may not be able to split your data. If this is your situation then consider taking random samples of your overall sample and create a subset for training and testing this way. For example, if you only have 100 records, randomly sample 80% of the records and create a training set; for the testing set, take another random sample of 80% of the 100 records. You can also try bootstrapping or jack-knifing as alternatives for your small samples.Justification and Explanation for Data Splitting (4 pts.)Discuss the Split Data Sets; compare the mean, median, and standard deviation of variables among the data sets. Are they the same? Different? (you can also do t-tests) (4 pts.)

Build the Models (20 pts.)
Finally! You have reached a critical stage in the project. Everything builds up to this. You must build your models (at least 2 of them!) on your prepared dataset. Provide the models and the results for each one. Interpret the meaning of your results for each of your models. Do not compare and contrast them; not yet. Specifically, I want to see the results displayed from your statistical package. What did you find? Interpret the results of your models. In other words, what can a manager do with your models? For example, in regression you can interpret each coefficient and explain how increasing cost will reduce sales by $x.

Explain why you think the modeled relationship exists. For example, if you find wheel size influences truck sales, tell me why you think it does. Also, do not copy and paste screenshots from your statistical program unless they are figures or charts! These tend to be difficult to read and do contain additional information that is not useful. You learned how to created advanced visualizations in Programming for Data Science I, so create amazing visualizations!

Results displayed for each model (8 pts.)
Interpretation of results (12 pts.)
Assess the Models (18 pts.)
Your models are completed and it is time to evaluate and compare them. Here you must decide which model is the best. You must assess the models based on objective or quantifiable means (i.e. compare R-Square values, accuracy assessments, etc.) as well as subjectively based on your goals and objectives. Your objective and subjective judgments may come up with separate models. Explain the strengths and weaknesses of your models. Justify the selected model of choice. Thus,

Explain your chosen assessment(s) and why you chose to employ it (them). Provide the results of your assessment(s). (6 pts.)
Discuss the strengths and weaknesses of each model. List out the strengths and weaknesses (6 pts.)
Justify the choice of your final model(s) (6 pts.)
Formatting, Style, Grammar and Spelling (16 pts.)
One or two mistakes are expected, but please make sure you proofread your work. Please include a title page, table of contents, label all figures and tables, and maintain clean margins. I want page numbers to start on the page with your executive summary, but not before then. So, your title page and table of contents will have no page numbers; note, page 1 starts on the page with the executive summary, not the title page. Your title page will include a title of your project, the team members of your project, and the date.
