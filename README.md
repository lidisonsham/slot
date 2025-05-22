# Ex03 Time Table
## Date:15.03.2025

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=!, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <center>
    <img src="logo.jpg">
    </center>
    <center><h3>SLOT TIME TABLE-DIVYA DHARSHINI.S(24900891)</h3></center>
    <center> <table border="6"></center>
        <tr>
            <td bgcolor="skyblue">Day/Time</td>
            <td bgcolor="skyblue">Monday</td>
            <td bgcolor="skyblue">Tuesday</td>
            <td bgcolor="skyblue">Wednesday</td>
            <td bgcolor="skyblue">Thursday</td>
            <td bgcolor="skyblue">Friday</td>
        </tr>
        <tr>
            <td bgcolor="skyblue">8-10</td>
            <th bgcolor="pink" colspan="3">FREE SLOT</th>
            <td bgcolor="pink">PHY</td>
            <td bgcolor="pink">CHE</td>
        </tr>
        <tr>
            <td bgcolor="skyblue">10-12</td>
            <td bgcolor="pink">BEEE</td>
            <td bgcolor="pink">FREE SLOT</td>
            <td bgcolor="pink">BEEE</td>
            <td bgcolor="pink">DE</td>
            <td bgcolor="pink">CHEM</td>
        </tr>
        <tr>
            <td bgcolor="skyblue">12-1</td>
            <th bgcolor="pink" colspan="6">LUNCH</th>
        </tr>
        <tr>
            <td bgcolor="skyblue">1-3</td>
            <td bgcolor="pink">C</td>
            <td bgcolor="pink">FREE SLOT</td>
            <td bgcolor="pink">MM</td>
            <td bgcolor="pink">MaT</td>
            <td bgcolor="pink">C</td>
            
        </tr>
        <tr>
            <td bgcolor="skyblue">3-5</td>
            <td bgcolor="pink">RA</td>
            <th bgcolor="pink"> FREE SLOT</th>
            <td bgcolor="pink">CHEM</td>
            <td bgcolor="pink">FREE SLOT</td>
            <td bgcolor="pink">FREE SLOT</td>
        </tr>
    </table></center>
        <br>
        <center> <table border="6"</center>
            <tr>
                <td>S.NO.</td>
                <td>Subject Code</td>
                <td>Subject Name</td>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI414</td>
                <td>Fundamental of web application</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI304</td>
                <td>C Programming</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19PH206</td>
                <td>Basis Electrical,Electronics and Measurement Engineering</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19CY205</td>
                <td>Principle of chemistry in engineering</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19MA222</td>
                <td>Probability and Queueing Models</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19EY709</td>
                <td>Reasoning Ability</td>
            </tr>
            <tr>
                <td>7.</td>
                <td>19EE404</td>
                <td>Digital Electronics</td>
            </tr>
    </body>
</html>
```


## OUTPUT
![Screenshot 2025-03-14 211222](https://github.com/user-attachments/assets/613b1051-0ab5-46b5-9832-ed7e31e5acae)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
