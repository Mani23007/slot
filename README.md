# Ex03 Time Table
## Date: 03-10-2025

## AIM:
To write a html webpage page to display your slot timetable.

## ALGORITHM:
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

## PROGRAM:
```
Developed by: MANIKANDAN K
Reg no: 212224230150
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TimeTable</title>
</head>
<body>
    <center>
        <img src="C:\Users\admin\Documents\SEC Logo.jpg" height="135" width="800"> 
    </center>
    <h3 align="center" style="font-size:22px">SLOT TIMETABLE-MANIKANDAN K (212224230150)</h3>
    <table align="center" border="5" cellpadding="7" cellspacing="2" bgcolor="aqua">
    <tr>
        <th bgcolor="yellow">Day</th>
        <th bgcolor="yellow">8:00AM-10:00AM</th>
        <th bgcolor="yellow">10:00AM-12:00AM</th>
        <th bgcolor="yellow">12:00PM-1:00PM</th>
        <th bgcolor="yellow">1:00PM-3:00PM</th>
        <th bgcolor="yellow">3:00PM-5:00PM</th>
    </tr>
    <tr>
        <th bgcolor="yellow">MONDAY</th>
        <td>EDM (1371)</td>
        <td>Operating System (2852)</td>
        <td rowspan="6" style="text-align:center;font-size:20px;width:80px">L<br>U<br>N<br>C<br>H </td>
        <td>Maths for AI (1371)</td>
        <td>Free Slot</td>
    </tr>
    <tr>
        <th bgcolor="yellow">TUESDAY</th>
        <td>Free Slot</td>
        <td>Advance C programming (2332)</td>
        <td>Maths for AI (2481)</td>
        <td>Operating System (2651)</td>
    </tr>
    <tr>
        <th bgcolor="yellow">WEDNESDAY</th>
        <td>BEEE (5873)</td>
        <td>Free Slot</td>
        <td>Mentor Meet (3331)</td>
        <td>Computer Networks (2851)</td>
    </tr>
    <tr>
        <th bgcolor="yellow">THURSDAY</th>
        <td>Maths for AI (2482)</td>
        <td>EDM (1512)</td>
        <td>Free Slot</td>
        <td>Free Slot</td>
    </tr>
    <tr>
        <th bgcolor="yellow">FRIDAY</th>
        <td>Advance C programming (2512)</td>
        <td>Free Slot</td>
        <td>Fundamentals of Web (1561)</td>
        <td>Reasoning Ability (4332)</td>
    </tr>
    <tr>
        <th bgcolor="yellow">SATURDAY</th>
        <td>Fundamentals of Web (2651)</td>
        <td>Computer Networks (1512)</td>
        <td>BEEE (5371)</td>
        <td>Free Slot</td> 
    </tr>
    </table>
    <br>
    <table align="center" border="5" cellpadding="7" cellspacing="2">
        <tr>
            <th><h4>S.NO</h4></th>
            <th><h4>SUBJECT CODE</h4></th>
            <th><h4>SLOT NO</h4></th>
            <th><h4>SUBJECT NAME</h4></th>
            <th><h4>FACULTY NAME</h4></th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI305</td>
            <td>4K1-1</td>
            <td>Advance C Programming</td>
            <td>RENUGADEVI R</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19AI302</td>
            <td>4K2-2</td>
            <td>Engineering Design and Modelling</td>
            <td>CALEB DANIEL R</td>
        </tr>
            <td>3.</td>
            <td>19MA220</td>
            <td>6K1-1</td>
            <td>Mathematics For Artificial Intelligence</td>
            <td>BHUVANESWARI G</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19CS405</td>
            <td>4D5-1</td>
            <td>Operating System</td>
            <td>KOLLI AMOS DANIEL</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19CS406</td>
            <td>4K5-2</td>
            <td>Computer Networks</td>
            <td>VINOTHINI M</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19EE305</td>
            <td>4X1-30</td>
            <td>Basic Electrical,Electronics and Measurement Engineering</td>
            <td>GOKUL KANNAN K</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>19EY709</td>
            <td>2U1-2</td>
            <td>Reasoning Ability</td>
            <td>SARANYA V </td>
        </tr>
        <tr>
            <td>8.</td>
            <td>19AI414</td>
            <td>4N2-1</td>
            <td>Fundamentals of Web Application Development</td>
            <td>JEEVANANDHAM M</td>
        </tr>
    </table>
    </body>
</html>
```

## OUTPUT:
<img width="1241" height="857" alt="image" src="https://github.com/user-attachments/assets/e39f03bb-7b55-45f2-a7f9-31e6f447dffa" />

## RESULT:
The program for creating slot timetable using basic HTML tags is executed successfully.
