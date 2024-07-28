# Google
Capstone Google

Case study: How does a bike-share navigate speedy success? ![][image1]

Introduction 

Welcome to the Cyclistic bike-share analysis case study\! In this case study, you work for a fictional company, Cyclistic, along with some key team members. In order to answer the business questions, follow the steps of the data analysis process: **Ask**, **Prepare**, **Process**, 

**Analyze**, **Share**, and **Act**. Along the way, the **Case Study Roadmap** tables — including guiding questions and key tasks — will help you stay on the right path. 

Scenario 

You are a junior data analyst working on the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, your team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, your team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve your recommendations, so they must be backed up with compelling data insights and professional data visualizations. 

Characters and teams 

● **Cyclistic:** A bike-share program that features more than 5,800 bicycles and 600 docking stations. Cyclistic sets itself apart by also offering reclining bikes, hand tricycles, and cargo bikes, making bike-share more inclusive to people with disabilities and riders who can’t use a standard two-wheeled bike. The majority of riders opt for traditional bikes; about 8% of riders use the assistive options. Cyclistic users are more likely to ride for leisure, but about 30% use the bikes to commute to work each day. 

● **Lily Moreno:** The director of marketing and your manager. Moreno is responsible for the development of campaigns and initiatives to promote the bike-share program. These may include email, social media, and other channels.  
● **Cyclistic marketing analytics team:** A team of data analysts who are responsible for collecting, analyzing, and reporting data that helps guide Cyclistic marketing strategy. You joined this team six months ago and have been busy learning about Cyclistic’s mission and business goals—as well as how you, as a junior data analyst, can help Cyclistic achieve them. 

● **Cyclistic executive team:** The notoriously detail-oriented executive team will decide whether to approve the recommended marketing program. 

About the company 

In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime. 

Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to broad consumer segments. One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members. 

Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Although the pricing flexibility helps Cyclistic attract more customers, Moreno believes that maximizing the number of annual members will be key to future growth. Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a solid opportunity to convert casual riders into members. She notes that casual riders are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs. 

Moreno has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members. In order to do that, however, the team needs to better understand how annual members and casual riders differ, why casual riders would buy a membership, and how digital media could affect their marketing tactics. Moreno and her team are interested in analyzing the Cyclistic historical bike trip data to identify trends. 

**Ask** 

Three questions will guide the future marketing program: 

1\. How do annual members and casual riders use Cyclistic bikes differently? 2\. Why would casual riders buy Cyclistic annual memberships? 

3\. How can Cyclistic use digital media to influence casual riders to become members? Moreno has assigned you the first question to answer: How do annual members and casual  
riders use Cyclistic bikes differently? 

You will produce a report with the following deliverables: 

1\. A clear statement of the business task 

2\. A description of all data sources used 

3\. Documentation of any cleaning or manipulation of data 

4\. A summary of your analysis 

5\. Supporting visualizations and key findings 

6\. Your top three recommendations based on your analysis 

Use the following Case Study Roadmap as a guide. Note: Completing this case study within a week is a reasonable goal. 

| Case Study Roadmap \- Ask |
| :---- |
| **Guiding questions**  ● What is the problem you are trying to solve?  ● How can your insights drive business decisions? |
| **Key tasks**  ● Identify the business task  ● Consider key stakeholders |
| **Deliverable**  ● A clear statement of the business task |

**Prepare** 

Use Cyclistic’s historical trip data to analyze and identify trends. Download the previous 12 months of Cyclistic trip data here. (Note: The datasets have a different name because Cyclistic is a fictional company. For the purposes of this case study, the datasets are appropriate and will enable you to answer the business questions. The data has been made available by Motivate International Inc. under this license.) This is public data that you can use to explore how different customer types are using Cyclistic bikes. But note that data-privacy issues prohibit you from using riders’ personally identifiable information. This means that you won’t be able to connect pass purchases to credit card numbers to determine if casual riders live in the Cyclistic service area or if they have purchased multiple single passes. 

Now, prepare your data for analysis using the following Case Study Roadmap as a guide:

| Case Study Roadmap \- Prepare |
| :---- |
| **Guiding questions**  ● Where is your data located?  ● How is the data organized?  ● Are there issues with bias or credibility in this data? Does your data ROCCC? ● How are you addressing licensing, privacy, security, and accessibility? ● How did you verify the data’s integrity?  ● How does it help you answer your question?  ● Are there any problems with the data? |
| **Key tasks**  ● Download data and store it appropriately.  ● Identify how it’s organized.  ● Sort and filter the data.  ● Determine the credibility of the data. |

**Deliverable** 

● A description of all data sources used 

**Process** 

Then, process your data for analysis using the following Case Study Roadmap as a guide: 

| Case Study Roadmap \- Process |
| :---- |
| **Guiding questions**  ● What tools are you choosing and why?  ● Have you ensured your data’s integrity?  ● What steps have you taken to ensure that your data is clean?  ● How can you verify that your data is clean and ready to analyze?  ● Have you documented your cleaning process so you can review and share those results? |

**Key tasks** 

● Check the data for errors. 

● Choose your tools. 

● Transform the data so you can work with it effectively. 

● Document the cleaning process.

| Deliverable  ● Documentation of any cleaning or manipulation of data |
| :---- |

**Follow these steps:** 

1\. Download the previous 12 months of trip data. 

**Note**: If you are planning on using Posit’s RStudio, use the Divvy 2019 Q1 and Divvy 2020 Q1 datasets. Choosing other data might lead to errors because the data exceeds the memory available in the free plan. 

2\. Unzip the files. 

3\. Create a folder on your desktop or Drive to house the files. Use appropriate file-naming conventions. 

4\. Create subfolders for the .csv file and the .xls or Sheets file so that you have a copy of the original data. Move the downloaded files to the appropriate subfolder. 5\. Follow these instructions for either Excel (a) or Google Sheets (b): 

a. Launch Excel, open each file, and choose to Save As an Excel Workbook file. Put it in the subfolder you created for .xls files. 

b. Open each .csv file in Google Sheets and save it to the appropriate subfolder. 6\. Open your spreadsheet and create a column called **ride\_length**. Calculate the length of each ride by subtracting the column **started\_at** from the column **ended\_at** (for example, \=D2-C2) and format as HH:MM:SS using Format \> Cells \> Time \> 37:30:55. 7\. Create a column called **day\_of\_week**, and calculate the day of the week that each ride started using the **WEEKDAY** command (for example, **\=WEEKDAY(C2,1)**) in each file. Format as General or as a number with no decimals, noting that 1 \= Sunday and 7 \= Saturday. 

8\. Proceed to the analyze step. 

If you like, continue working with the data to better familiarize yourself, and perhaps even identify new approaches to answering the business questions. 

**Analyze** 

Now that your data is stored appropriately and has been prepared for analysis, start putting it to work. Use the following Case Study Roadmap as a guide: 

**Case Study Roadmap \- Analyze** 

**Guiding questions** 

● How should you organize your data to perform analysis on it? 

● Has your data been properly formatted? 

● What surprises did you discover in the data?  
● What trends or relationships did you find in the data? 

● How will these insights help answer your business questions? 

**Key tasks** 

● Aggregate your data so it’s useful and accessible. 

● Organize and format your data. 

● Perform calculations. 

● Identify trends and relationships. 

**Deliverable** 

● A summary of your analysis 

**Follow these steps for using spreadsheets** 

Open your spreadsheet application, then complete the following steps: 

1\. Where relevant, make columns consistent and combine them into a single worksheet. 2\. Clean and transform your data to prepare for analysis. 

3\. Conduct descriptive analysis. 

4\. Run a few calculations in one file to get a better sense of the data layout. Options: ● Calculate the mean of **ride\_length** 

● Calculate the max **ride\_length** 

● Calculate the mode of **day\_of\_week** 

5\. Create a pivot table to quickly calculate and visualize the data. Options: ● Calculate the average **ride\_length** for members and casual riders. Try rows \= **member\_casual**; Values \= Average of **ride\_length**. 

● Calculate the average **ride\_length** for users by **day\_of\_week**. Try columns \= **day\_of\_week**; Rows \= **member\_casual**; Values \= Average of **ride\_length**. ● Calculate the number of rides for users by **day\_of\_week** by adding Count of **trip\_id** to Values. 

6\. Open another file and perform the same descriptive analysis steps. Explore different seasons to make some initial observations. 

7\. Once you have spent some time working with the individual spreadsheets, merge them into a full-year view. Do this with the tool you have chosen to use to perform your final analysis, either a spreadsheet, a database and SQL, or R Studio. 

8\. Export a summary file for further analysis. 

**Follow these steps for using SQL** 

Open your SQL tool of choice, then complete the following steps: 

1\. Import your data. 

2\. Explore your data, perhaps looking at the total number of rows, distinct values, maximum, minimum, or mean values.  
3\. Where relevant, use JOIN statements to combine your relevant data into one table. 4\. Create summary statistics. 

5\. Investigate interesting trends and save that information to a table. 

**Follow these steps for using R** 

Open your preferred version of R, click this link, and select “Use template.” Then, copy and paste the text from the template into an R script. 

1\. Import your data from Divvy 2019 Q1 and Divvy 2020 Q1. 

2\. Make columns consistent and merge them into a single dataframe. 

3\. Clean up and add data to prepare for analysis. 

4\. Conduct descriptive analysis. 

5\. Export a summary file for further analysis. 

**Share** 

Now that you have performed your analysis and gained some insights into your data, create visualizations to share your findings. Moreno has reminded you that they should be sophisticated and polished in order to effectively communicate to the executive team. Use the following Case Study Roadmap as a guide: 

**Case Study Roadmap \- Share** 

**Guiding questions** 

● Were you able to answer the question of how annual members and casual riders use Cyclistic bikes differently? 

● What story does your data tell? 

● How do your findings relate to your original question? 

● Who is your audience? What is the best way to communicate with them? 

● Can data visualization help you share your findings? 

● Is your presentation accessible to your audience? 

**Key tasks** 

● Determine the best way to share your findings. 

● Create effective data visualizations. 

● Present your findings. 

● Ensure your work is accessible. 

**Deliverable** 

● Supporting visualizations and key findings 

**Follow these steps:** 

1\. Take out a piece of paper and a pen and sketch some ideas for how you will visualize  
the data. 

2\. Once you choose a visual form, open your tool of choice to create your visualization. Use a presentation software, such as PowerPoint or Google Slides, your spreadsheet program, Tableau, or R. 

3\. Create your data visualization, remembering that contrast should be used to draw your audience’s attention to the most important insights. Use artistic principles including size, color, and shape. 

4\. Ensure clear meaning through the proper use of common elements, such as headlines, subtitles, and labels. 

5\. Refine your data visualization by applying deep attention to detail. 

**Act** 

Now that you have finished creating your visualizations, act on your findings. Prepare the deliverables Morena asked you to create, including the three top recommendations based on your analysis. Use the following Case Study Roadmap as a guide: 

**Case Study Roadmap \- Act** 

**Guiding questions** 

● What is your final conclusion based on your analysis? 

● How could your team and business apply your insights? 

● What next steps would you or your stakeholders take based on your findings? ● Is there additional data you could use to expand on your findings? 

**Key tasks** 

● Create your portfolio. 

● Add your case study. 

● Practice presenting your case study to a friend or family member. 

**Deliverable** 

● Your top three recommendations based on your analysis 

**Follow these steps:** 

1\. If you do not have one already, create an online portfolio. 

2\. Consider how you want to feature your case study in your portfolio. 3\. Upload or link your case study findings to your portfolio. 

4\. Write a brief paragraph describing the case study, your process, and your discoveries. 5\. Add the paragraph to introduce your case study in your portfolio.  
**Wrap-up** 

Congratulations on finishing the Cyclistic bike-share case study\! If you like, complete another case study to continue growing your portfolio. Or, use the steps from the **Ask**, **Prepare**, **Process**, **Analyze**, **Share**, and **Act** Case Study Roadmap to create a new project that’s all your own. Best of luck on your job search\!

[image1]: <data:image/png;base64,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>
