# Ex03 Time Table
# Date:31.03.2025
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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>𝐓𝐈𝐌𝐄 𝐓𝐀𝐁𝐋𝐄</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: blanchedalmond;(247, 246, 246);
        }
        table {
            border-collapse: collapse;
            margin: 20px auto;
            background-color: whitesmoke;(125, 202, 215);
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        th, td {
            border: 2px solid black;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: rgb(142, 177, 226);
        }
        td {
            background-color: whitesmoke;
        }
        .header img {
            width: 1000px;
            align-items: center;
            margin-left: auto;
            margin-right: auto;
            display: block;

            
        }
        h3{
            text-align: center;
            font-size: x-large;
            font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="header" style="text-align: center;">
        <img src="C:\Users\admin\OneDrive\Pictures\Screenshots\Screenshot 2024-12-29 155546.png" alt="Saveetha logo" width="300"
        <h3> <b>TIME TABLE - KRITHIKA LAKSHMI M (24900558)</b></h3>
    </div>
    
    <table border="1" width="80%">
        <tr>
            <th>Day/Time</th>
            <th> 8-10 </th>
            <th> 10-12 </th>
            <th> 12-1 </th>
            <th> 1-2 </th>
            <th> 3-5 </th>
        </tr>
        <tr>
            <th>Monday</th>
            <td>Free slot</td>
            <td rowspan="2">Free slot</td>
            <td rowspan="6">Lunch</td>
            <td>Free slot</td>
            <td>Computer Networks</td>
        </tr>
        <tr>
            <th>Tuesday</th>
            <td>Cloud security</td>
            <td>Web</td>
            <td>Python</td>
        </tr>
        <tr>
            <th>Wednesday</th>
            <td>Free slot</td>
            <td>Human values</td>
            <td>Mentor meet</td>
            <td>Cloud security</td>
        </tr>
        <tr>
            <th>Thursday</th>
            <td>Python </td>
            <td>Computer Networks</td>
            <td>Python</td>
            <td>Free slot</td>
        </tr>
        <tr>
            <th>Friday</th>
            <td>Free slot</td>
            <td>Python</td>
            <td>Web</td>
            <td rowspan="2">Free slot</td>
        </tr>
        <tr>
            <th>Saturday</th>
            <td>Free slot</td>
            <td>Free slot</td>
            <td>Reasoning ability</td>
        </tr>
    </table>

    <table border="4" width="300" height="400" style="margin: 20px auto;">
        <tr>
            <th>S.NO</th>
            <th>Subject Name</th>
            <th>Subject Code</th>
        </tr>
        <tr>
            <th>1.</th>
            <td>Fundamentals of Web Applications</td>
            <td>19AI401</td>
        </tr>
        <tr>
            <th>2.</th>
            <td>Maths for AI/Python/Linear Algebra</td>
            <td>19MA301</td>
        </tr>
        <tr>
            <th>3.</th>
            <td>Computer networks</td>
            <td>19CS406</td>
        </tr>
        <tr>
            <th>4.</th>
            <td>Cloud security</td>
            <td>19CS416</td>
        </tr>
        <tr>
            <th>5.</th>
            <td>Reasoning ability</td>
            <td>19EY709</td>
        </tr>
        <tr>
            <th>6.</th>
            <td>Human Values and Professional Ethics</td>
            <td>SH7801</td>
        </tr>
    </table>
</body>
</html>
```

# OUTPUT

![Screenshot 2025-03-31 121206](https://github.com/user-attachments/assets/a7af6be9-dd55-4bc1-92fa-8072308ef2be)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
