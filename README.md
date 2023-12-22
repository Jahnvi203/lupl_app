# lupl_app


**PROBLEM STATEMENT**

To get the required data insights from the raw data obtained from Zoho for Lupl usage specifically within Rajah & Tann Singapore for different Practice Groups and types of users (Lawyer/Secretary/Other) across the months.


**WHAT DOES THE APP DO & HOW DOES THE APP WORK?**


**Input**

Before viewing the statistics, you will first be required to upload 3 files.
  1. Lawyers List
      
       - The uploaded file must have the first 3 columns as Name, Email and Department/Practice Group in the same order. Column A should be Name, Column B should be Email and Column C should be Department/Practice Group.
      
       - Please ensure that Column C i.e. Department/Practice Group contains consistent values. For example, for a particular row, if the Department/Practice Group is written as "Appeals & Issues", please ensure that all the rows where the Department/Practice Group is Apepals & Issues, it is written as "Appeals & Issues" and not "Appeals and Issues" or "Appeals Issues", otherwise, the app will treat the different versions of the same Department/Practice Group as different Practice Groups.
  2. Secretaries List
      
       - The uploaded file must have the first 3 columns as Name, Email and Department/Practice Group in the same order. Column A should be Name, Column B should be Email and Column C should be Department/Practice Group.
      
       - Please ensure that Column C i.e. Department/Practice Group contains consistent values. For example, for a particular row, if the Department/Practice Group is written as "Appeals & Issues", please ensure that all the rows where the Department/Practice Group is Apepals & Issues, it is written as "Appeals & Issues" and not "Appeals and Issues" or "Appeals Issues", otherwise, the app will treat the different versions of the same Department/Practice Group as different Practice Groups.
  3. Monthly Activity Data
       - The raw data downloaded from Zoho can directly be uploaded without any editing required.

NOTE: All the uploaded files must be in .CSV format.


**Overview**

The Overview section consists of the following sub-sections:
  1. Count of Total Monthly Users - Shows how the number of active users change over the months.
  2. Count of Total Monthly Users by Type (Lawyer/Secretary/Other) - Shows how the number of active users change over the months by type.
  3. Count of Total Monthly Users per PG by Type - Shows how the number of active users change over the months by type separated for particular Practice Groups.

NOTE: The Overview section related to data for Rajah & Tann Singapore only.


**Detailed**

The Detailed section consists of the following sub-sections:
  1. Lists all the branches in the entire Rajah & Tann organisation.
  2. Provides a Macro and Micro view for each branch for all users within the particular branch.
       - The Macro view provides an average change over the month in usage for each user within a branch.
       - The Micro view provides the raw data for each user’s Days Active (“Days”) and Time (in minutes) (“Time”) of usage within a branch.

**Top 2 Power Users per PG**

The Top 2 Power Users per PG section lists the top 2 power users for each Practice Group along with the type (whether a Lawyer or a secretary).



**HOW TO START USING THE APP?**

To start using the app, please go to [https://jahnvi203-lupl-app-home-pa8fu6.streamlitapp.com/](https://jahnvi203-lupl-app-home-eyk9y4.streamlit.app/).



**TROUBLESHOOTING**

In case of any issues with the app, please submit an issue on GitHub at https://github.com/Jahnvi203/lupl_app/issues along with any description or attachments that may help with understanding the issue.
