COGS 108 - Project Proposal
Names
Newton Chung
David Moon
Christine Uy
Maria Yakovlev
Zhaocheng Yang

Research Question
Include a specific, clear data science question.
Make sure what you're measuring (variables) to answer the question is clear
What is your research question? Include the specific question you're setting out to answer. This question should be specific, answerable with data, and clear. A general question with specific subquestions is permitted. (1-2 sentences)

Ideas
Does the frequency and duration of advertisements during the Super Bowl significantly impact the revenue and stock prices of participating companies in the subsequent quarter?


Company Revenue: Quarterly revenue for the companies that aired advertisements during the Super Bowl. This data should be collected for at least one quarter before and one quarter after the Super Bowl event.
Ad Airtime and Frequency: Detailed information on the duration and frequency of each advertisement aired during the Super Bowl. This includes total airtime and the number of times each ad was broadcasted.
Cost of Super Bowl Ads: The financial investment made by companies to air their advertisements during the Super Bowl, including production and airtime costs.

Background & Prior Work
HTML Inline citation format: <a name="#..."> </a>

Introduction： 
Every year, the National Football League holds its infamous championship game on the second Sunday of February. This US tradition amasses millions of views as well as a large amount of revenue, with many brands utilizing the Superbowl as a marketing tactic. Apart from watching the game, many viewers tune in to see the unique and high production ads that various companies air in-between breaks. Superbowl ads have become a cultural phenomenon of its own, garnering lots of media attention even outside the game. Due to the high viewership and popularity of the Super Bowl in the United States, many companies consider advertising during the Super Bowl as a highly important opportunity for raising their brand awareness and attracting potential consumers. This phenomena leads to a significant increase in advertising costs during the Super Bowl. According to the New York Times, for two consecutive years, the average cost of a 30-second ad spot during the Super Bowl has reached $7 million. Although the cost of advertising is high, based on the broad audience reach and high viewership of the Super Bowl, as well as its significant influence, we believe that advertising during the Super Bowl period, and the longer the duration of advertising, can potentially lead to increased revenue and stock prices for the companies advertising during subsequent quarters.
Prior work: 
A previous work observing the relationship between ads played during the Super Bowl revealed that companies that advertised saw “substantial advertising effects”. Because consumption of beer, snacks and other food is common during the Super Bowl, there is a desire among watchers to see ads of the food product being consumed. Another study that focused on finding out if Super Bowl ads were a waste of money or a good investment found that ads that improved their company’s customer-based brand equity had an increase for the likelihood of a stock price increase. It also found that when a company’s ad decreases customer-based brand equity, there was a negative impact on stock return. In addition, companies that had a pre-existing high customer-based brand equity saw little change between stock return and airing an effective ad.
References:
[https://www.nytimes.com/2024/02/06/business/super-bowl-commercials.html](#1)
[https://web.stanford.edu/~wesleyr/SuperBowl.pdf ](#2)
[https://www.sciencedirect.com/science/article/pii/S0148296316301011?casa_token=pJ7JdBOiDN4AAAAA:nN9jSBZmIC8JPLgnZd-h1SvcFmGzPPqdu4pKSDi892rGJeclAqWV-bZiObNeETx2hsduPoydLA](#3)
Hypothesis
We hypothesize that there is a positive correlation between the frequency and duration of Super Bowl ads by companies and their revenue and stock prices in the subsequent quarter. We believe that the Super Bowl’s enormous presence gives a lot of exposure to participating companies, allowing them the opportunity to attract new customers through in-person and televised advertising. In addition to the broader audiences they can advertise to, their association with the NFL may elevate companies’ prestige. We believe that these factors play a key role in increasing the revenue and stock value of the companies in the subsequent quarter.

Data
Explain what the ideal dataset you would want to answer this question. (This should include: 
What variables? 
How many observations? 
Who/what/how would these data be collected? 
How would these data be stored/organized?)

The ideal dataset for answering this question would be one that analyzes companies' quarterly revenue and stock value in correlation with their advertising at the Super Bowl. It would compare the company's revenue and stock value at least one quarter before and one quarter after the Super Bowl Event. This information would be available from companies' quarterly earnings reports and public archives of companies' stock market values in history. In addition, it would have information about each company's ad airtime and frequency, potentially using a scatter plot to plot companies' ad airtime and frequencies in relation to changes in profits in the subsequent quarter. Information about the companies' ads are publicly available in the Super Bowl commercials schedules or in superbowl-ads.com. Ideally, the dataset would have a couple thousand observations, given that there are 57 Super Bowls with available data and roughly 50 companies advertising per year. For storing/organizing the data, we plan to sort of merge all of the separate datasets into one. So for those who had a commercial in the Super Bowl advertisements dataset, would merge with the stock prices and quarterly revenue datasets to make the EDA and analysis easier.

Search for potential real datasets that could provide you with something useful for this project. You do not have to find every piece of data you will use, but you do need to have demonstrated some idea that (a) this data is gettable and (b) that this data may be different from what your ideal is.

https://www.kaggle.com/datasets/thedevastator/uncover-america-s-secrets-through-super-bowl-ads *cites the dataset from https://data.world/fivethirtyeight/superbowl-ads*
This dataset looks at the Super Bowl ads from the 10 brands that advertised the most in the Super Bowl from 2000-2020. It analyzes the content of the advertisements themselves, but we are able to look at the frequencies of advertisements from the top brands.
https://www.kaggle.com/datasets/prondeau/superbowlads/data
This dataset contains a list of Super Bowl ads from 1967-2020, and lists the advertisements’ year, product type, brand, and a description of the ad.
https://www.kaggle.com/datasets/camnugent/sandp500
This dataset looks at the stock data for S&P 500 companies in the past 5 years, which include many of the companies that advertised at the Super Bowl. 
https://www.nasdaq.com/market-activity/quotes/historical
This website shows individual companies increase/decrease/amount of stocks change per day, so we can grab the week we need to analyze an increase in stock prices after they aired their commercial during the SuperBowl
https://fortune.com/ranking/fortune500/2020/search/
This website lets us to grab data on company revenue split by sectors so we can easily see if there is an increase or decrease in revenue during the air of the SuperBowl commercials.

Ethics & Privacy
Thoughtful discussion of ethical concerns included
Ethical concerns consider the whole data science process (question asked, data collected, data being used, the bias in data, analysis, post-analysis, etc.)
How your group handled bias/ethical concerns clearly described
Acknowledge and address any ethics & privacy related issues of your question(s), proposed dataset(s), and/or analyses. Use the information provided in lecture to guide your group discussion and thinking. If you need further guidance, check out Deon's Ethics Checklist. In particular:

Are there any biases/privacy/terms of use issues with the data you proposed?
Are there potential biases in your dataset(s), in terms of who it composes, and how it was collected, that may be problematic in terms of it allowing for equitable analysis? (For example, does your data exclude particular populations, or is it likely to reflect particular human biases in a way that could be a problem?)
How will you set out to detect these specific biases before, during, and after/when communicating your analysis?
Are there any other issues related to your topic area, data, and/or analyses that are potentially problematic in terms of data privacy and equitable impact?
How will you handle issues you identified?

We hypothesize that there is a positive correlation between the frequency and duration of Super Bowl ads by companies and their revenue and stock prices in the subsequent quarter. Our investigation scope includes companies that advertise during the Super Bowl. All companies that advertise and their respective content are available online for people to read and analyze, and changes in the companies' revenue and stock prices are also accessible to the public for analysis. Hence, we are using data that has already been made publicly available by the companies and the Super Bowl, so informed consent, and privacy are not within the scope of our concerns. The stakeholders for this project will be the companies advertising during the Super Bowl. They will use our conclusions to help them decide whether to advertise during the Super Bowl period or not, thereby potentially increasing their companies' revenue. One potential outcome may include whether companies' decisions to advertise affect the advertising revenue for the Super Bowl. However, we believe that such changes are legitimate and fall within the realm of normal business decision-making effects. Hence, our project won’t generate any other negative impacts.
The Data: 
Evaluation: 
Analysis: 
TRANSPARENCY & APPEAL: 
. CONTINUOUS MONITORING
Team Expectations
Members must contribute to work equally.
Members should strictly adhere to project deadlines and must communicate in advance if they are unable to.
Members are expected to attend and actively participate in team meetings, and communicate if they are unable to.
Any conflict should be communicated and resolved in a respectful manner.
If conflict is unable to be resolved within teams, will contact TA/Professor for further assistance.
Project Timeline Proposal

Meeting Date
Meeting Time
Completed Before Meeting
Discuss at Meeting
2/8
6 PM
Discussed best form of communication for meetings, decided on meeting time, brainstorm possible topics
Deciding on final topic, weekly meeting times, start background research and project proposal
2/15
6 PM
Do a little more research and have a general idea of what role each person wants to do
Decide which person will do which part of the project and communicate which likely datasets to use for analysis
2/22
6 PM
Import dataset and wrangling and begin EDA and get as far as possible (or finish)
Go over wrangling, EDA, and revise if necessary; begin how to start on analysis part
2/29
6 PM
Finalize wrangling and EDA, begin the analysis part
Complete project-check in, discuss and make changes on analysis if necessary
3/7
6 PM
Complete analysis, come up with possible conclusions, and discussions based on analysis
Final touchings, figure out which conclusions make the most sense and wrap up the project
3/14
6 PM
Final checking of the project to make sure everything makes sense
Turn in project and do group project survey


IMPORTANT DEADLINES:
2/11: PROJECT PROPOSAL DUE
2/25: CHECKPOINT #1: DATA
3/10: CHECKPOINT #2: EDA
3/20: FINAL REPORT, FINAL VIDEO, TEAM EVALUATION DUE


