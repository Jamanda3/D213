# D213-Advanced_Data_Analytics

## Task 1
As a data analyst, you will assess continuing data sources for their relevance to specific research questions throughout your career.

In your previous coursework, you have performed data cleaning and exploratory data analysis on your data. You have seen basic trends and patterns and now want to start building more sophisticated statistical models. In this course, you will use time series modeling. We will explore time series models and their implications.

For this task, you will select one of the Data Sets and Associated Data Dictionaries from the following link:

Data Sets and Associated Data Dictionaries

After you choose your organizational data set, you will review the data dictionary and considerations related to the raw data file you have chosen and prepare the data for time series modeling. You will then analyze that data set using time series modeling, create visualizations, generate forecasts, and deliver the results of your analysis.

As part of the “readmission” project, executives would like to see consider a time series on 
revenue from the first years of operation. Once they understand any patterns in that data, 
they feel confident in understanding the impact of readmission in current times. The given 
time series data records the daily revenue, in million dollars, during the first two years of 
operation.

Data Dictionary:
The data set consists of 731 rows (days) and two columns or variables:
• Day: Day during first two years of operation
• Revenue: Revenue in million dollars.

Choose one of the data files and corresponding spreadsheet provided in the Web Links section and use the information to complete the following:

Part I:  Research Question    
A.  Describe the purpose of this data analysis by doing the following:
1.  Summarize one research question that is relevant to a real-world organizational situation captured in the selected data set and that you will answer using time series modeling techniques.
2.  Define the objectives or goals of the data analysis. Ensure that your objectives or goals are reasonable within the scope of the scenario and are represented in the available data.

Part II:  Method Justification      
B.  Summarize the assumptions of a time series model including stationarity and autocorrelated data.

Part III:  Data Preparation
C.  Summarize the data cleaning process by doing the following:     
1.  Provide a line graph visualizing the realization of the time series.
2.  Describe the time step formatting of the realization, including any gaps in measurement and the length of the sequence.
3.  Evaluate the stationarity of the time series.
4.  Explain the steps used to prepare the data for analysis, including the training and test set split.

Part IV:  Model Identification and Analysis     
D.  Analyze the time series dataset by doing the following:
1.  Report the annotated findings with visualizations of your data analysis, including the following elements:     
•   the presence or lack of a seasonal component    
•   trends    
•   autocorrelation function        
•   spectral density      
•   the decomposed time series      
•   confirmation of the lack of trends in the residuals of the decomposed series
2.  Identify an autoregressive integrated moving average (ARIMA) model that takes into account the observed trend and seasonality of the time series data.
3.  Perform a forecast using the derived ARIMA model.
4.  Provide the output and calculations of the analysis you performed.
5.  Provide the code used to support the implementation of the time series model.

Part V:  Data Summary and Implications    
E.  Summarize your findings and assumptions, including the following points:
1.  Discuss the results of your data analysis, including the following:
•   the selection of an ARIMA model
•   the prediction interval of the forecast
•   a justification of the forecast length
•   the model evaluation procedure and error metric
2.  Provide an annotated visualization of the forecast of the final model compared to the test set.
3.  Recommend a course of action based on your results.

Part VI:  Reporting      
F.  Create your report from part E using an industry-relevant interactive development environment (e.g., a Jupyter Notebook). Include a PDF or HTML document of your executed notebook presentation.

G.  List the web sources used to acquire data or segments of third-party code to support the application.

H.  Acknowledge sources, using in-text citations and references, for content that is quoted, paraphrased, or summarized.

I.  Demonstrate professional communication in the content and presentation of your submission.

## Task_2    
Throughout your career as a data analyst, you will assess continuing data sources for their relevance to specific research questions. Organizations use data sets to analyze their operations. Organizations have many possible uses for these data sets to support their decision-making processes.

In your previous coursework, you have explored a variety of supervised and unsupervised data mining models. You have seen the power of using data analytical techniques to help organizations make data-driven decisions and now want to extend these models into areas of machine learning and artificial intelligence. In this course, you will explore the use of neural networks and natural language processing (NLP).

In this task, you will choose a data file from the Web Links section. The available data sets are as follows:
•  Amazon Product Data set
•  UCSD Recommender Systems Data sets
•  UCI Sentiment Labeled Sentences Data set

For this task, you will build a neural network designed to learn word usage and context using NLP techniques. You will provide visualizations and a report, as well as build your network in an interactive development environment.

Note: You cannot use the same data set that was provided in the exemplar for this course.
REQUIREMENTS
________________________________________
Choose one dataset from the Web Links section and use it to complete the following:

Part I:  Research Question     
A.  Describe the purpose of this data analysis by doing the following:
1.  Summarize one research question that you will answer using neural network models and NLP techniques. Be sure the research question is relevant to a real-world organizational situation and sentiment analysis captured in your chosen dataset.
2.  Define the objectives or goals of the data analysis. Be sure the objectives or goals are reasonable within the scope of the research question and are represented in the available data.
3.  Identify a type of neural network capable of performing a text classification task that can be trained to produce useful predictions on text sequences on the selected data set.

Part II:  Data Preparation     
B.  Summarize the data cleaning process by doing the following:
1.  Perform exploratory data analysis on the chosen dataset, and include an explanation of each of the following elements:
•   presence of unusual characters (e.g., emojis, non-English characters, etc.)
•   vocabulary size
•   proposed word embedding length
•   statistical justification for the chosen maximum sequence length
2.  Describe the goals of the tokenization process, including any code generated and packages that are used to normalize text during the tokenization process.
3.  Explain the padding process used to standardize the length of sequences, including the following in your explanation:
•   if the padding occurs before or after the text sequence
•   a screenshot of a single padded sequence
4.  Identify how many categories of sentiment will be used and an activation function for the final dense layer of the network.
5.  Explain the steps used to prepare the data for analysis, including the size of the training, validation, and test set split.
6.  Provide a copy of the prepared dataset.

Part III:  Network Architecture      
C.  Describe the type of network used by doing the following:
1.  Provide the output of the model summary of the function from TensorFlow.
2.  Discuss the number of layers, the type of layers, and total number of parameters.
3.  Justify the choice of hyperparameters, including the following elements:
•   activation functions
•   number of nodes per layer
•   loss function
•   optimizer
•   stopping criteria
•   evaluation metric

Part IV:  Model Evaluation     
D.  Evaluate the model training process and its relevant outcomes by doing the following:
1.  Discuss the impact of using stopping criteria instead of defining the number of epochs, including a screenshot showing the final training epoch.
2.  Provide visualizations of the model’s training process, including a line graph of the loss and chosen evaluation metric.
3.  Assess the fitness of the model and any measures taken to address overfitting.
4.  Discuss the predictive accuracy of the trained network.

Part V:  Summary and Recommendations      
E.  Provide the code used to save the trained network within the neural network.

F.  Discuss the functionality of your neural network, including the impact of the network architecture.

G.  Recommend a course of action based on your results.

Part VI: Reporting     
H.  Create your neural network using an industry-relevant interactive development environment (e.g., a Jupyter Notebook). Include a PDF or HTML document of your executed notebook presentation.

I.  List the web sources used to acquire data or segments of third-party code to support the application.

J.  Acknowledge sources, using in-text citations and references, for content that is quoted, paraphrased, or summarized.

K.  Demonstrate professional communication in the content and presentation of your submission.
