# It all started with a plain dumb Excel sheet...
where we were adding data for new sales requests for my Company. So I improvised and moved it to Google Spreadsheet,
but the idea was dropped by management for unknown reason. So the challenge came up how multiple people can work on same file as excel won't allow it , so there was inefficiency in the work.
In addition to that entering and editing the data just in rows and columns was time consuming and was a mess.
  So I designed a data entry form using visual basics which reduced the data entry and update time significantly, but now the issue was how multiple people can work on same file at the same time. 
  So i used a trick and created multiple entry worksheets for individual agents and whenever they enter/update data on their file it automatically sync with a main data file. Before adding new data in the main file it compares the data with agent's file and make sure there are no duplicates.The trick here was the agnet file will pull data from main data file and once the data is entered/ updated in agents's entry form,  after pressing the submit button it will save the agent's file as new main data file and delete the old one. 
