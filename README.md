Project Overview:
In this project, I was asked to imagine that I was hired as a data science consultant by a realty company called PA-VA Realty. I was tasked with creating a model that predicts the price of a house so realtors can identify undervalued and overvalued homes when comparing predicted price to list price. 

I was given two datasets: train.csv and test.csv. When creating a model, I was expected to use most of the models and approaches that we discussed in class, even if they weren’t exactly the most appropriate for the situation.

We were given approximately one week to complete the assignment from start to finish. Our work was graded in accordance with the tight deadline. In a section at the end of this readme, I will explain what I would’ve done differently with more time and what I would have done if the rubric was slightly different. Overall, I received an A- on the final project.

Project Deliverables:
Predictions (10%): a single CSV with 600 test observations that include the property ID, predicted price, and student ID number. These are the predictions on test.csv, where all predictor variables are included but price is unknown and must be predicted.
Technical report (50%): a pdf report that outlines your process from start to finish. Limit of 4 pages double spaced. It must touch on the following:
• Introduction and description of exploratory data analysis.
 • Identification of Data oddities e.g. missing data, extreme values, etc. and how you handled them. 
• Summary of models considered. How many models seemed to perform “best” in terms of predictive accuracy? How’d you measure?
 • What were the most important variables? How did you measure variable importance? Were the variables deemed most important consistent across the top-performing models? 
• What were the most challenging aspects of this particular dataset? Were you able to mitigate these issues? Do you really trust your “best” model? If your job depended on this model, how worried would you be?

Final (non-technical) Report (30%): Discuss your findings to a non-technical decision maker, in this case the CEO and realtors of PA-VA realty. Introduce your project and summarize a couple of your key findings from your research that could be useful to understand housing prices in Pittsburgh and Richmond. Limit 1.5 pages (double-spaced). 

Code (10%): thoroughly commented code from start to finish, including brainstorming/some failed ideas if needed for clarity.

A Retrospective Look:
My biggest enemy when working on this project was time. If I had been given a few more days, I would have done a lot more than I did. For example, I omitted the variable “zipcode” from my analysis. Any realtor will tell you that the most important part of any home is “location, location, location.” I had some legitimately good reasons for omitting zipcode, like the fact that AvgIncome is a numerical value that represented the average income in each zipcode, so there were collinearity issues and a lot of the signal contained in zipcode was likely also well represented by AvgIncome. The biggest reason that I removed zipcode was that it was a factor variable with a large number of levels. I’ve never worked with a factor variable like zipcode in this project, and I didn’t really have enough time to wrap my head around solutions. If I had more time, I would have loved to play with the inclusion of zipcode and how to work around it and give it a chance. 

My second biggest enemy was page limits. I consider myself quite good at brevity and writing. I can normally take my writing and boil it down to the essentials. With the sheer amount of work done and the level of detail required in the rubric, I found myself well over the page limit even with my best efforts to be concise. I ended up needing to guess the most important part of the rubric, and I sent about 10 emails back and forth with my professor to try and find out what he was really looking for. With even one extra page, I could include some extra info and make that graph in the technical report less awful on the eyes.

My final enemy was the fact that we didn’t have complete freedom to approach this project in our own way. Our instructor made it clear that we had to include as many models as possible that we learned in class. I would’ve liked to focus on just a few of the models and go into greater depth. 

