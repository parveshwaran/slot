# Ex02 Time Table
## Date:27-11-2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>

    <head>

        <title>My Timetable</title>

    </head>

    <body bgcolor="gray">

        <img src="logo.png" width="1200">
        <br>
        <br>

        <table border="1" cellspacing="6" cellpadding="11">
            <caption><b>SLOT  TIME  TABLE - PARVESHWARAN(25018243)</b></caption>

            <tr style="text-align: center;">

                <td bgcolor="black" style="color: white;">Day/Time</td>

                <td bgcolor="black" style="color: white;">Monday</td>

                <td bgcolor="black" style="color: white;">Tuesday</td>

                <td bgcolor="black" style="color: white;">Wednessday</td>

                <td bgcolor="black" style="color: white;">Thursday</td>

                <td bgcolor="black" style="color: white;">Friday</td>

                <td bgcolor="black" style="color: white;">Saturday</td>

            </tr>

            <tr bgcolor="silver" bgstyle="text-align: center;">

                <td bgcolor="black" style="color: white;">8-10</td>

                <td >English</td>

                <td >English</td>

                <td >FWAD</td>

                <td >Python</td>

                <td>Free Slot</td>

                <td >FWAD</td>

            </tr>

            <tr style="text-align: center;">

                <td bgcolor="black" style="color: white;">10-12</td>

                <td bgcolor="silver" colspan="3">FWAD</td>

                <td bgcolor="silver" colspan="2">Free Slot</td>

                <td bgcolor="silver">English</td>

            </tr>

            <tr style="text-align: center;">

                <td bgcolor="black" style="color: white;">12-1</td>

                <td colspan="6" bgcolor="silver" style="text-align: center;">LUNCH</td>

            </tr>

            <tr style="text-align: center;">

                <td bgcolor="black" style="color: white;">1-3</td>

                <td bgcolor="silver">Python</td>

                <td bgcolor="silver ">Free Slot</td>

                <td bgcolor="silver">Mentor Meet</td>

                <td bgcolor="silver">English</td>

                <td bgcolor="silver">Free Slot</td>

                <td bgcolor="silver">Python</td>

            </tr>

            <tr style="text-align: center;">

                <td bgcolor="black" style="color: white;">3-5</td>

                <td bgcolor="silver">Python</td>

                <td bgcolor="silver" colspan="3" style="text-align: center;">Free slot</td>

                <td bgcolor="silver">Python</td>

                <td bgcolor="silver">Free Slot</td>

            </tr>

        </table>
        <br>
        <br>

        <table border="3" cellspacing="5" cellpadding="10">

            <tr style="text-align: center;">

                <th bgcolor="black" style="color: white;">S. No</th>

                <th bgcolor="black" style="color: white;">Subgect Code</th>

                <th bgcolor="black" style="color: white;">Subject Name</th>

            </tr>

            <tr style="text-align: center;">

                <td bgcolor="black" style="color: white;">1.</td>

                <td>19AI414</td>

                <td>Fundamental of Web Application Development (FWAD)</td>

            </tr>

            <tr style="text-align: center;">

                <td bgcolor="black" style="color: white;">2.</td>

                <td>19EN101</td>

                <td>Comunicative English</td>

            </tr>

            <tr style="text-align: center;">

                <td bgcolor="black" style="color: white;">3.</td>

                <td>19AI301</td>

                <td>Python</td>

            </tr>

        </table>

    </body>

</html>
```

## OUTPUT
![alt text](<Screenshot 2025-11-27 090246.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
