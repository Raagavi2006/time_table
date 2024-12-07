# Ex03 Time Table
# Date:21.10.2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<html>
<head>
    <title>MY  TIMETABLE</title>
    <center>
    <img src="/static/logo.png" width="1500px" height="120px">
    <h1 style="color: black">SLOT TIMETABLE - RAAGAVI RM (24900010)</h1>
    </center>
</head>    
<body style="background-color:pink">
    <style>
        table,th,td{
            text-align: center;
            border:3px solid black;
            border-collapse: collapse;
            height:70px;
            width: 1000px;
            vertical-align: center;
        }
        th{
            font-style: bold;
            font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            font-size:x-large;
            font-weight: 7000;
        }
        td{
            font-style:normal;
            font-family:'Times New Roman', Times, serif;
            font-size: larger;
            font-weight: 550;
        }
    </style>
    <center>
    <table>
        <tr>
            <th style="background-color:rgb(88, 113, 204);">DAY</th>
            <th style="background-color: rgb(243, 96, 121)">8-10</th>
            <th style="background-color: rgb(243, 96, 121)">10-12</th>
            <th style="background-color: rgb(243, 96, 121)">12-1</th>
            <th style="background-color: rgb(243, 96, 121)">1-3</th>
            <th style="background-color: rgb(243, 96, 121)">3-5</th>
        </tr>
        <tr>
            <th style="background-color: rgb(174, 174, 251)">MON</th>
            <td style="background-color: rgb(248, 170, 183)">19EE404</td>
            <td style="background-color: rgb(248, 170, 183)">19AI414</td>
            <th rowspan="6" style="background-color: rgb(249, 87, 114);">L<br>U<br>N<br>C<br>H<br><br>B<br>R<br>E<br>A<br>K</th>
            <td style="background-color: rgb(248, 170, 183)">19AI302</td>
            <td style="background-color: rgb(248, 170, 183)"></td>
        </tr>
        <tr>
            <th style="background-color: rgb(174, 174, 251)">TUE</th>
            <td style="background-color: rgb(248, 170, 183)"></td>
            <td style="background-color: rgb(248, 170, 183)">19MA201</td>
            <td style="background-color: rgb(248, 170, 183)">19EE404</td>
            <td style="background-color: rgb(248, 170, 183)"></td>
        </tr>
        <tr>
            <th style="background-color: rgb(174, 174, 251)">WED</th>
            <td style="background-color: rgb(248, 170, 183)">19AI302</td>
            <td style="background-color: rgb(248, 170, 183)">19CY205</td>
            <td style="background-color: rgb(248, 170, 183)">MM</td>
            <td style="background-color: rgb(248, 170, 183)"></td>
        </tr>
        <tr>
            <th style="background-color: rgb(174, 174, 251)">THU</th>
            <td style="background-color: rgb(248, 170, 183)">19AI304</td>
            <td style="background-color: rgb(248, 170, 183)"></td>
            <td style="background-color: rgb(248, 170, 183)">19AI414</td>
            <td style="background-color: rgb(248, 170, 183)"></td>
        </tr>
        <tr>
            <th style="background-color: rgb(174, 174, 251)">FRI</th>
            <td style="background-color: rgb(248, 170, 183)"></td>
            <td style="background-color: rgb(248, 170, 183)">19CY205</td>
            <td style="background-color: rgb(248, 170, 183)"></td>
            <td style="background-color: rgb(248, 170, 183)">19EY708</td>
        </tr>
        <tr>
            <th style="background-color: rgb(174, 174, 251)">SAT</th>
            <td style="background-color: rgb(248, 170, 183)"></td>
            <td style="background-color: rgb(248, 170, 183)">19MA201</td>
            <td style="background-color: rgb(248, 170, 183)">19AI304</td>
            <td style="background-color: rgb(248, 170, 183)">19AI414</td>
        </tr>
        </tr>
    </table>
    </center>
    <hr>
        <center>
        <table>
            <tr>
                <th style="background-color:rgb(88, 113, 204)">CODE</th>
                <th style="background-color: rgb(243, 96, 121)">ABBREVIATION</th>  
            </tr>
            <br>
            <tr>
                <th style="background-color: rgb(174, 174, 251)">19AI302</th>
                <td style="background-color: rgb(248, 170, 183)">Engineering Design and Modelling</td>
            </tr>
            <br>
            <tr>
                <th style="background-color: rgb(174, 174, 251)">19AI304</th>
                <td style="background-color: rgb(248, 170, 183)">Fundamentals of C programming</td>
            </tr>
            <br>
            <tr>
                <th style="background-color: rgb(174, 174, 251)">19AI414</th>
                <td style="background-color: rgb(248, 170, 183)">Fundamentals of Web Application Development</td>
            </tr>
            <br>
            <tr>
                <th style="background-color: rgb(174, 174, 251)">19CY205</th>
                <td style="background-color: rgb(248, 170, 183)">Principles of Chemistry in Engineering</td>
            </tr>
            <br>
            <tr>
                <th style="background-color: rgb(174, 174, 251)">19EE404</th>
                <td style="background-color: rgb(248, 170, 183)">Digital Electronics</td>
            </tr>
            <br>
            <tr>
                <th style="background-color: rgb(174, 174, 251)">19EY708</th>
                <td style="background-color: rgb(248, 170, 183)">Career Development Skills</td>
            </tr>
            <br>
            <tr>
                <th style="background-color: rgb(174, 174, 251)">19MA201</th>
                <td style="background-color: rgb(248, 170, 183)">Calculus and Matrix Algebra</td>
            </tr>
        </table>
        </center>
</body>
</html>
```
# OUTPUT

![alt text](<WEB 3.1.png>)

![alt text](<WEB 3.2.png>)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
