# Ex03 Time Table
## Date:27.04.2025

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
```
<html>
     <body>
        <img src="/static/logo.png">
        <table border="5" bgcolor="violet" cellspacing="20" cellpading="20">
            <caption>SLOT TIMETABLE - AGASH S (24900273)</caption>
               <tr bgcolor="yellow"> 
                <th bgcolor="yellow">Day/Time</th>
                <td>Monday</td>
                <td>Tuesday</td>
                <td>Wednesday</td>
                <td>Thursday</td>
                <td>Friday</td>
                <td>Saturday</td>
               </tr> 
                <tr>
                    <th bgcolor="yellow">8-10</th>
                    <td>Free Slot</td>
                    <td>Free Slot</td>
                    <td>Advanced C</td>
                    <td>Free slot</td>
                    <td>Free slot</td>
                    <td>DE</td>
                    </tr>
                <tr>
                        <th bgcolor="yellow">10-12</th>
                        <td>SE</td>
                        <td>CN</td>
                        <td>CN</td>
                        <td>CHEM</td>
                        <td>CHEM</td>
                        <td>SE</td>
                </tr>
                         <tr>
                            <th bgcolor="yellow">12-01</th>
                            <th colspan="6">LunchBreak</th>
                        </tr>
                         <tr>
                            <th bgcolor="yellow">01-03</th>
                            <td>Advanced C</td>
                            <td>RA</td>
                            <td>MentorMeet</td>
                            <td colspan="2">PQM</td>
                            <td>FOWAD</td>
                         </tr>
                        </tr>
                    </tr>
                </tr>
        </table>
<br>
<table border="5">
    <tr>
        <th>S.No</th>
        <th>SubjectCode</th>
        <th>Subject name</th>
    </tr>
    <tr>
        <td>1</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development</td>
    </tr>
    <tr>
        <td>2</td>
        <td>19CS408</td>
        <td>Software Engineering</td>
    </tr>
    <tr>
        <td>3</td>
        <td>19CY205</td>
        <td>Principles of Chemistry in Engineering</td>
    </tr>
    <tr>
        <td>4</td>
        <td>19MA222</td>
        <td>Probability and Queueing Models</td>
    </tr>
    <tr>
        <td>5</td>
        <td>19AI305</td>
        <td>Advanced C Programming</td>
    </tr>
    <tr>
        <td>6</td>
        <td>19CS406</td>
        <td>Computer Networks</td>
    </tr>
    <tr>
        <td>7</td>
        <td>19EY709</td>
        <td>Reasoning Ability</td>
    </tr>
    
</table>
     </body>
</html>


```

## OUTPUT


![Screenshot 2025-04-27 114952](https://github.com/user-attachments/assets/65ddae11-f9d1-4196-9464-4d9b01a2037e)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
