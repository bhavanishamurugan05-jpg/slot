# Ex03 Time Table
## Date: 09-10-2025

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
  <title>Slot Time Table</title>
  <style>
    img {
      display: block;
      margin: 0 auto;
    }
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      text-align: center;
    }
    h2 {
      margin-bottom: 10px;
      color: darkblue;
    }
    table {
      border-collapse: collapse;
      margin: 15px auto;
      width: 80%;
    }
    table, th, td {
      border: 2px solid black;
    }
    th, td {
      padding: 10px;
      text-align: center;
    }
    th {
      background: gold;
    }
    .slot {
      background: #66e0ff;
    }
    .subject-table th {
      background: #ddd;
    }
  </style>
</head>
<body>

  <img src="/static/sec_logo.png" height="100" width="540" alt="Banner Image">

  <h2>SLOT TIME TABLE - BHAVANISHA.M (25018505)</h2>

  <!-- Timetable -->
  <table>
    <tr>
      <th>Day/Time</th>
      <th>Monday</th>
      <th>Tuesday</th>
      <th>Wednesday</th>
      <th>Thursday</th>
      <th>Friday</th>
      <th>Saturday</th> 
    </tr>
    <tr>
      <td>8-10</td>
      <td class="slot">FWAD</td>
      <td class="slot">CE</td>
      <td class="slot">FWAD</td>
      <td class="slot">CE</td>
      <td class="slot">FCP</td>
      <td class="slot">CE</td>
    </tr>
    <tr>
      <td>10-12</td>
      <td class="slot">FREE</td>
      <td class="slot">CE</td>
      <td class="slot">FWAD</td>
      <td class="slot">FCP</td>
      <td class="slot">FWAD</td>
      <td class="slot">FWAD</td>
    </tr>
    <tr>
      <td>12-1</td>
      <td colspan="6"><b>L U N C H</b></td>
    </tr>
    <tr>
      <td>1-3</td>
      <td class="slot">FCP</td>
      <td class="slot">FREE</td>
      <td class="slot">ECA-M</td>
      <td class="slot">CE</td>
      <td class="slot">FREE</td>
      <td class="slot">CE</td>
    </tr>
    <tr>
      <td>3-5</td>
      <td class="slot">FREE</td>
      <td class="slot">FREE</td>
      <td class="slot">FCP</td>
      <td class="slot">FCP</td>
      <td class="slot">FREE</td>
      <td class="slot">FREE</td>
    </tr>
  </table>

  <!-- Subject Codes Table -->
  <h3>Subject Details</h3>
  <table class="subject-table">
    <tr>
      <th>S. No.</th>
      <th>Subject Code</th>
      <th>Subject Name</th>
    </tr>
    <tr><td>1</td><td>19AI414</td><td>Fundamentals of Web Application Development (FWAD)</td></tr>
    <tr><td>2</td><td>19AI304</td><td>Fundamentals of C Programming (FCP)</td></tr>
    <tr><td>3</td><td>19EN101</td><td>Communicative English (CE)</td></tr>
    <tr><td>4</td><td>ECM-M</td><td>Mentor Meet</td></tr>
  </table>

</body>
</html>

```
## OUTPUT
![expt3](https://github.com/user-attachments/assets/f547f98d-a6a3-47d5-95fe-c49b39e56dae)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
