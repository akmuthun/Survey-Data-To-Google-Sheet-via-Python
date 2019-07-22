# Survey-Data-To-Google-Sheet-via-Python
An efficient way to transfer survey data to google sheets

This program was written for an education institute which collected students data in a semester. About 1000 students answered questions on their time commitments on school work. For more information on the format of the sheet please see the file """. Entering those data directly on to the google sheet is difficult and time consuming since one has to find student's name, then the date, next for the class then fillout number of hours worked and taks numbers in corresponding cells for each sheet. There is a possibility of making mistakes if one navigate cells manually. 

There are two types for programs for the same task in this repository. <b>The first program</b> starts with a selected student's name and starts to ask for which day you want to fillout then which class then hours and task numbers. It is easy to answer those questions since one have input only numerical values in sequence. After getting all those information it writes them in corresponding cells in your google sheet and move to the next student's name automatically, you dont even want to login to your sheet. The configuration the google sheet to the program can be done easily, <a href="https://www.youtube.com/watch?v=vISRn5qFrkM">this!</a> video will provide all information you need.

<b>The second program</b>, is for those who dont like to answer each question separately. You can select the name of a student to start then it asks for all details at once. There is a special format for entering data and hit enter then it splits data accordingly and write in corresponding cells in the google sheets.

