# Ex03 Time Table
## Date:7.10.25

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
<html>
<head>
  <meta charset="utf-8">
  <title>Slot Timetable</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
    }
    table {
      border-collapse: collapse;
      width: 100%;
      text-align: center;
    }
    th, td {
      border: 1px solid #333;
      padding: 10px;
    }
    th {
      background-color: #4CAF50;
      color: white;
    }
    .slot {
      background-color: #f2f2f2;
    }
  </style>
</head>
<body>
  <h2>Slot Timetable</h2>
  <table>
    <tr>
      <th>Day / Time</th>
      <th>Slot 1<br>9:00–10:00</th>
      <th>Slot 2<br>10:00–11:00</th>
      <th>Slot 3<br>11:00–12:00</th>
      <th>Slot 4<br>12:00–1:00</th>
      <th>Lunch</th>
      <th>Slot 5<br>2:00–3:00</th>
      <th>Slot 6<br>3:00–4:00</th>
    </tr>

    <tr>
      <td><b>Monday</b></td>
      <td class="slot">Maths</td>
      <td class="slot">Physics</td>
      <td class="slot">Chemistry</td>
      <td class="slot">English</td>
      <td rowspan="5"><b>Break</b></td>
      <td class="slot">Lab</td>
      <td class="slot">Sports</td>
    </tr>

    <tr>
      <td><b>Tuesday</b></td>
      <td class="slot">Biology</td>
      <td class="slot">Maths</td>
      <td class="slot">Computer</td>
      <td class="slot">Library</td>
      <td class="slot">English</td>
      <td class="slot">Physics</td>
    </tr>

    <tr>
      <td><b>Wednesday</b></td>
      <td class="slot">Chemistry</td>
      <td class="slot">Maths</td>
      <td class="slot">Lab</td>
      <td class="slot">Computer</td>
      <td class="slot">Biology</td>
      <td class="slot">Library</td>
    </tr>

    <tr>
      <td><b>Thursday</b></td>
      <td class="slot">English</td>
      <td class="slot">Physics</td>
      <td class="slot">Sports</td>
      <td class="slot">Maths</td>
      <td class="slot">Chemistry</td>
      <td class="slot">Biology</td>
    </tr>

    <tr>
      <td><b>Friday</b></td>
      <td class="slot">Library</td>
      <td class="slot">Lab</td>
      <td class="slot">Computer</td>
      <td class="slot">Physics</td>
      <td class="slot">English</td>
      <td class="slot">Maths</td>
    </tr>
  </table>
</body>
</html>
```



## OUTPUT
![323](https://github.com/user-attachments/assets/eb4566b6-d13e-4ba8-8330-0325b31c275a)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
