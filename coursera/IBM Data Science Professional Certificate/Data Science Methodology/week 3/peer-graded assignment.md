## 1. Which topic did you choose to apply the data science methodology to? (2 marks)  

Data Science Methodology: is the routine for finding solutions to a specific problem. It is a cyclic process that undergoes critical behavior guiding data scientists to act accordingly. It includes organizing your work, analyzing different types of data, and solving their problem.  

Topic for Case Study: 'Spam E-mail Detection & Classification':  
The question to be answered: Whether or not the e-mail is a "spam" and classify it accordingly.  

This is one of the first case studies I came across while getting started pursuing Machine Learning as a career. The motive here is to train an e-mail filter using a collection of spam and non-spam (aka “ham”) emails. So, by providing the right answers to train the filter, and later in the prediction phase, its output for a given message would be either “spam” or “ham”. This filter is a classic example of a supervised classification algorithm.  

## 2. Next, you will play the role of the client and the data scientist.  

Using the topic that you selected, complete the Business Understanding stage by coming up with a problem that you would like to solve and phrasing it in the form of a question that you will use data to answer. (3 marks)  

You are required to:  
Describe the problem, related to the topic you selected.  
Phrase the problem as a question to be answered using data.  

For example, using the food recipes use case discussed in the labs, the question that we defined was, "Can we automatically determine the cuisine of a given dish based on its ingredients?".  

Assuming the roles of both a Data Scientist and a Stakeholder, I have completed the "Business Understanding" phase of the Data Science Methodology by coming up with a 'problem' I'd like to solve and phrasing it in the form of a 'question' that needs to be answered using the data.  

Business Understanding:  

1. The 'Problem':  
This is one of the first case studies I came across while getting started pursuing Machine Learning as a career. The motive here is to train an e-mail filter using a collection of spam and non-spam (aka “ham”) emails. So, by providing the right answers to train the filter, and later in the prediction phase, its output for a given message would be either “spam” or “ham”. This filter is a classic example of a supervised classification algorithm. We get tens or hundreds of e-mails into our inbox every day. They might include the ones from our employers, friends, subscriptions, etc. On the contrary, we also do get loads of fishy e-mail trying to steal our password, give discounts, and ask for personal information to win the lucky draw award.  

2. The 'Question' to be answered based on the problem:  
Whether or not the e-mail is a "spam" and then classify them accordingly as "spam" and "ham" using the appropriate classification technique(s). Here are a few E-mail SPAM trigger words: meet singles, be your own boss, work at home, money back, no credit check, freedom, lose weight, valium, winner, risk-free, etc.
The basic business question to be asked in this phase is: Can we detect such spam mails automatically, and put them in the spam folder?  

## 3. Briefly explain how you would complete each of the following stages for the problem that you described in the Business Understanding stage, so that you are ultimately able to answer the question that you came up with. (5 marks):  

Analytic Approach  
Data Requirements  
Data Collection  
Data Understanding and Preparation  
Modeling and Evaluation  
You can always refer to the labs as a reference with describing how you would complete each stage for your problem.  

NOTE: For the ease of reading and nature of the flow, I've included all the phases in this section.  

Case Study: 'Spam E-mail Detection & Classification':  
The question to be answered: Whether or not the e-mail is a "spam" and classify it accordingly.  

Abstract/Introduction:  
This is one of the first case studies I came across while getting started pursuing Machine Learning as a career. The motive here is to train an e-mail filter using a collection of spam and non-spam (aka “ham”) emails. So, by providing the right answers to train the filter, and later in the prediction phase, its output for a given message would be either “spam” or “ham”. This filter is a classic example of a supervised classification algorithm.  

1. Business Understanding:  
We get tens or hundreds of e-mails into our inbox every day. They might include the ones from our employers, friends, subscriptions, etc. On the contrary, we also do get loads of fishy e-mail trying to steal our password, give discounts, and ask for personal information to win the lucky draw award. Here are a few E-mail SPAM trigger words: meet singles, be your own boss, work at home, money back, no credit check, freedom, lose weight, valium, winner, risk-free, etc.  

The basic business question to be asked in this phase is: Can we detect such spam mails automatically, and put them in the spam folder?  
2. Analytic Approach:  
Our motive in this phase is to classify the e-mails we receive to "spam" and "ham" in our E-mail Id. The fundamental question is, then, whether the mail received is a spam or not. So, the classification model will be used as it gives us the answer as yes or no. If the result is a 'yes', then the e-mail will go to the spam folder and if 'no', it will be sent to our Inbox as a regular e-mail.  

3. Data Requirements:  
This phase includes the need for all of the e-mails that we have received. The identification of the data thus satisfies the data requirement stage of the data science methodology. To ensure a more accurate/optimal model, we need to make sure that we have a huge amount of data.  

4. Data Collection:  
After having established our data requirements, we will start collecting the data for this phase. We have some e-mails (both spam and ham) in our inbox. But that doesn't suffice to train a model. We shall collect more e-mail samples from our credible sources or the Internet to increase our data samples. The data thus collected can be structured, unstructured or semi-structured.  

5. Data Understanding:  
Now that we have the data, we'll understand its content, access its accuracy, discover any new insights and decide whether additional data are needed to fill in the gaps. We're seeing some e-mails purposely with spelling errors like med1icine, w4tches, etc. Some e-mails do have errors in punctuation. Some offer us deals and offer discounts.  
Some e-mails ask us for our login credentials and personal details. All these e-mails look fishy and might be spam. We then try to create a relationship between them. We map the histogram and other charts to see the distribution of the variables. See their parameters of average, minimum, mean and other. We see that the term 'win' occurring in different forms: win, winner, winning. In Machine Learning & NLP, this is known as the 'Bag-of-words' model to identify the occurrences of the same word in different forms.  

6. Data Preparation:  
Data preparation, also known as data cleaning, requires 70 percent to 90 percent of our project time and will give us a correct model if done properly. We remove all redundant e-mails that have the same content. We find all the e-mails including SPAM trigger words: meet singles, be your own boss, work at home, money back, etc. We do some adat analysis and add or remove columns accordingly. This phase might include various techniques including matrix and vector operations, statistical analysis, data visualization.  

Once all the other operations on our data have been removed, added and done, we merge all the data into one table which is 'data frame'. This concludes our data preparation phase.  

7. Data Modelling:  
Now that we have a data frame, we can now create models using the different algorithms and libraries which we can download and install. Again, choosing a model is an art or science. Try different algorithms, and choose the one that gives you the greatest precision that answers your needs and intended questions. To order to achieve this, you need to understand the question for which you are solving the problem, in our case, whether or not the e-mail is spam. Next, pick a tool or an empirical approach accordingly.  

8. Evaluation:  
We split our data set into a train set and a test set. Follow the 70/30 Train/Test rule for better results. The motive behind this phase is to check the quality of the model we built in the earlier phase. We create our model using the train set. Then we'll test the model on the test set and compare the spam emails expected by the model to the real spam emails.  

9. Deployment:  
This is where we produce our results directly to our stakeholders through storytelling. This is where the model is rolled into the production for real-world applications and direct use by potential consumers. In order to identify the e-mail as spam and ham, we deploy our model and the spam e-mail is classified correctly under the spam folder.  

10. Feedback:  
The stakeholder/client tests this whether the model delivers the correct output or not. If it provides the correct results answering the original questions, then we set it up for the client. If it doesn't give the right result, then we start the modeling process again with new input from the client. If we need new data to collect, we'll collect it. It is an iterative process and will proceed until the client obtains the correct result.  

Conclusion:  
With incredible research happening across the world, there are numerous techniques that solve the problem of insufficient data or small data. Examples include Transfer Learning, Self-supervised Learning, Synthetic Data Generation, etc. Please read this brief article for a quick overview:
https://www.industryweek.com/technology-and-iiot/digital-tools/article/21122846/making-ai-work-with-...
