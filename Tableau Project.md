
# Introduction

In this project, I create an explanatory data visualization using Tableau Public from Prosper Loan dataset; explore the Prosper load market share distribution across USA, borrowers credit risk control, borrowers credit risk affecting factors and how Prosper bursting their market. In general, Prosper did not manage borrowers information well and struggled before 2009. In 2009, a Prosper rating system was introduced and market got recoverd. New risk control system made Prosper burst in 2013. 

Initial Visualization: https://public.tableau.com/profile/xuefei.yu#!/vizhome/Udacity_Tableau_Project_1st/Project_v1 

Final   Visualization: https://public.tableau.com/profile/xuefei.yu#!/vizhome/Udacity_Tableau_Project_r444/Project_v1

# Summary

By exploring Prosper Loan Amount map across America, 13 states sharing 65% market(California, Texas, New York, Florida, Illinois, Georgia, Ohio, New Jersey, Virginia, Pennsylvania, Michigan, North Carolina and Maryland) were selected to compare their loan amount and debt ratio. Most of them have around 0.25 debt ratio or lower while most of midland states have around 0.30 debt ratio. The Prosper developed their market in these coastal states more than midland states.



# Design

### Initial Design

After reading Prosper loan dateset features definition, I list all the features related to my story: loan origin amount, Loan origination date, Prosper ratings, states name, etc. The design idea is natually followed my thought. 

For the first version of visualization, chart type, format settingsand axis names for all the sheets were set to default. 

Firstly, I plot a line chart of loan amount per date to clearly view the trend of Prosper's marketing development. 

Then I created histogram sheet of loan amount in each states. A colored loan amount map using states names was designed to view the distribution more intuitional. 

Then I explored the relationship between Prosper rating(categorical) with other credit risk affecting factors(numerical) separately by histograms. These histograms showed that all credit affecting factors are highly related. I choose Prosper rating and debt ratio to dig more.

At last, I mapped a market share under different categorised Prosper rating in selected states to make readers understand dominant market share more clearly.

An animated visualization of loan amount per debt ratio by using 'pages' shelf.

'Year' filter(2009 - 2014) was applied to all related data sources.


### Design after Feedback


Animation were added so that the reader can understand story better. Unfortunately, when I using the Page Control feature to save in my public profile, an error always occurred.

Remove some redundant sheet titles, expand some axis title to make the feature more understandable.

Added some annotation to key points. 

More detailed story Comments were updating to make the story more comprehensible

Replace 'Pages' shelf features by filter shelf 'Year of date' because of unfixable error. 

# Feedback


- There is no title for the whole story, need some time to figure out what is this story talking about

- Explanation for some abbreviation axis names(e.g. HR:high risk)

- Need some key points in plots to support story

- Some dashboard have too less space,  plots are crowded together

- Wrong spelling in story 

- Better to make showed filter floating, bigger visualization

- there is no story in some Visualizations

- Some graphs are hard to understand.


# Resources

https://en.wikipedia.org/wiki/Prosper_Marketplace#2009_post_SEC_relaunch

https://stackoverflow.com/questions/47136002/how-to-convert-strings-in-tableau-desktop-like-we-use-text-function-in-ms

https://community.tableau.com/thread/123287

https://onlinehelp.tableau.com/current/pro/desktop/en-us/publish_workbooks_tableaupublic.html
