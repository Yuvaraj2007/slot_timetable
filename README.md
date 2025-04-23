# Ex03 Time Table
## Date:
23/04/25
## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
     ''''
    <html>
    <head>
        <title> Course Schedule </title>
    </head>
    <body><center><img src="/static/logo.png" height="100" width="540" ></center>
        <br>
        <table align="center" width="540" cellspacing="2" cellpadding="4"
        border="5" bgcolor="cyan">
        <caption><b>SCHEDULE OF ALL COURSES</b></caption>
        <tr align="center">
            <th bgcolor="yellow">Day/Time</th>
            <th bgcolor="yellow">Monday</th>
            <th bgcolor="yellow">Tuesday</th>
            <th bgcolor="yellow">Wednesday</th>
            <th bgcolor="yellow">Thursday</th>
            <th bgcolor="yellow">Friday</th>
        </tr>
        <tr align="center">
            <th bgcolor="yellow">8-10</th>
            <td>C PROGRAMMING</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>PHYSICS </td>
            <td>NUMERICAL METHODS</td>
            <td>ADVANCED C PROGRAMMING</td>
        </tr>
        <tr align="center">
            <th bgcolor="yellow">10-12</th>
            <td>C PROGRAMMING</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>PHYSICS </td>
            <td>NUMERICAL METHODS</td>
            <td>ADVANCED C PROGRAMMING</td>
        </tr>
        <tr align="center">
            <th bgcolor="yellow">1-3</th>
            <td>C PROGRAMMING</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>PHYSICS </td>
            <td>NUMERICAL METHODS</td>
            <td>ADVANCED C PROGRAMMING</td>
        </tr>
        </table>
        <br>
        <table align="center" width="540" cellspacing="2" cellpadding="4"
        border="5" bgcolor="blue">
        <tr  align="center"> 
        <th bgcolor="PINK">  YUVARAJ.M (24900173) </th>
        
        </tr>
    </table>
    <br>
    <table align="center" cellspacing="2" cellpadding="4" border="2">
        <tr align="center">
            <th>S.no</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td align="center">1.</td>
            <td align="center">19AI303</td>
            <td>ENGINEEERING MECHANICS AND PRODUCT DEVELOPMENT</td>
        </tr>
        <tr>
            <td align="center">2.</td>
            <td align="center">19AI304</td>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
        </tr>
        <tr>
            <td align="center">3.</td>
            <td align="center">19AI414</td>
            <td>FUNDAMENTALS OF WEB APPLICATION</td>
        </tr>
        <tr>
            <td align="center">4.</td>
            <td align="center">19EE404</td>
            <td>DIGITAL ELECTRONICS</td>
        </tr>
        <tr>
            <td align="center">5.</td>
            <td align="center">19MA222</td>
            <td>STATISTIC AND NUMERICAL METHOD</td>
        </tr>
        <tr>
            <td align="center">6.</td>
            <td align="center">19PH814</td>
            <td>PHYSICS FOR QUANTUM COMPUTING</td>
        </tr>
        <tr>
            <td align="center">6.</td>
                <td align="center">19PH814</td>
                <td>ENGINEERING DESIGN AND MODELLING</td>
            </tr>
        </table>
      </body>
    </html>

    ''''          

## OUTPUT
![alt text](<Screenshot 2025-04-23 174609.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
