# This all started witha plain dumb Excel sheet 
where we were adding data about new sales requests for my Company. So I improvised and moced it to Google Spreadsheet,
but the ides was dropped by management for unknow reason. So the challenge was for multiple peoples work on same file which excel won't allow so there was inefficiency in the work.
Also entering and editing the data just in rows and couplms was time consuming and was a mess.
  So I designed a data entry form using visual basics which reduced the data entry time significantly but now the issue was how multiple people can work on same file at the same time. 
  So i used a trick and created multiple entry worksheets for individual agents and whenever they enter/update data on their file it automatically sync with a main data firle. 
  Before adding new data in the main file it compares the data with agent's file and make sure there are no duplicates.The trick here was the agnet file will pull data from main date file
  and once the data is entered/ updated in agents's entry form  after pressing the submit button it will save the agent's file as new main data file and delete the old one.
  Sync module was used to accomplish this. 
