# Ex03 Time Table
## Date: 20-03-2025

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
    <head>
        <title>time-table</title>
        <style>
            @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Noto+Serif+Hentaigana:wght@200..900&display=swap');
            body{
                background: linear-gradient(135deg, #ff9a9e, #fad0c4, #fad0c4, #ffdde1);
            }
            img{
                margin-top:3%;
            }
            table{
                border: 2px solid black;
                width: 75%;
                height: 45%;
                margin-top: 0%;
                margin-left: 11%;
            }
            td,th{
                border: 2px solid black;
                border-style: groove;
            }
            .text-center{
                text-align: center;
            }
            .head{
                background-color:beige;
                text-align:center;
            }
            .header{
                background: linear-gradient(120deg, #a18cd1, #fbc2eb);
            }
            .mentor-meet{
                background-color: aquamarine;
                text-align: center;
            }
            .mentor-meet:hover{
                color:#ff9a9e;
                background-color:#a18cd1;
            }
            .quote{
                text-align: center;
                font-family: "Dancing Script", cursive;
                font-size: 20;
            }
            .name{
                margin-bottom: 0%;
                margin-top:6%;
            }
            .mui{
                background-color: aqua;
                font-family: "Dancing Script", cursive;
            }
        </style>
    </head>
    <body>
        <div>
            <center><img src="/static/logo.png" height="100" width="540"></center>
        </div>
        <div class="name">
            <center><h2><span class="mui">SLOT TIME-TABLE</span>M.shantharam (212224040307)</h2></center>
        </div>
        <table>
            <tr>
                <th class="header" colspan="4">WEB DEVELOPEMENT AND FUNDAMENTALS OF AI</th>
            </tr>
            <tr>
                <th class="head">DAYS</th>
                <th class="head">8-10</th>
                <th class="head">10-12</th>
                <th class="head">1-3</th>
            </tr>
            <tr>
                <td class="head">Monday</td>
                <td class="text-center">WEB DEVELOPEMENT</td>
                <td class="text-center">TASK ASSIGNMENT</td>
                <td class="text-center">FUNDAMENTALS OF AI</td>
            </tr>
            <tr>
                <td class="head">Tuesday</td>
                <td class="text-center">TASK COMPLETION</td>
                <td class="text-center">WEB DEVELOPEMENT</td>
                <td class="text-center">MODULE COMPLETION</td>
            </tr>
            <tr>
                <td class="head">Wednesday</td>
                <td class="text-center">ASSESMENT HOUR</td>
                <td class="text-center">TASK PRESENTATION</td>
                <td class="mentor-meet">MENTOR MEET</td>
            </tr>
            <tr>
                <td class="head">Thursday</td>
                <td class="text-center">MODULE COMPLETION</td>
                <td class="text-center">FUNDAMENTALS OF AI</td>
                <td class="text-center">TASK PRESENTATION</td>
            </tr>
            <tr>
                <td class="head">Friday</td>
                <td class="text-center">TASK COMPLETION</td>
                <td class="text-center">WEB DEVELOPEMENT</td>
                <td class="text-center">TASK COMPLETION</td>
            </tr>
            <tr>
                <td class="head">Saturday</td>
                <td colspan="4" class="text-center">MODULE ASSESMENT COMPLETION</td>
            </tr>
        </table>
        <div>
        </div>
        <div class="quote">
            <h1>Success is not about being the best. It's about being better than you were yesterday.</h1>
        </div>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-03-20 111203.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
