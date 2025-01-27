# Ex03 Time Table
## Date: 14-03-2024

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
        <title>
            My Time table
        </title>
    </head>
    <body>
        <img src="logo.png" height="200" width="1200">
        <h3 class="name">SLOT TIMETABLE - K.Tharani (212221040080)</h3>
        <table border="2" bgcolor="cyan" cellspacing="6" cellpadding="8" height="10" width="20">
            <tr>
                <th bgcolor="blue">Day/time</th>
                <th bgcolor="blue">Monday</th>
                <th bgcolor="blue">Tuesday</th>
                <th bgcolor="blue">Wednesday</th>
                <th bgcolor="blue">Thursday</th>
                <th bgcolor="blue">Friday</th>
                <th bgcolor="blue">Saturday</th>
            </tr>
            <tr>
                <th bgcolor=" blue">8-10</th>
                <th bgcolor=" green">MAD</th>
                <th bgcolor=" green">FREE SLOT</th>
                <th bgcolor=" green">MPMC</th>
                <th bgcolor=" green">MAD</th>
                <th bgcolor=" green">FWAD</th>
                <th bgcolor="green">FREE SLOT</th>
            </tr>
            <tr>
                <th bgcolor="blue">10-12</th>
                <th bgcolor=" green">FREE SLOT</th>
                <th bgcolor=" green">MPMC</th>
                <th bgcolor="green">FREESLOT</th>
                <th bgcolor=" green">SPM</th>
                <th bgcolor="green">MPMC</th>
                <th bgcolor=" green">DS</th>
            </tr>
            <tr>
                <th>12-1</th>
                <th colspan="6">LUNCH BREAK</th>
            </tr>
            <tr>
                <th bgcolor="blue">1-3</th>
                <th bgcolor=" green">FREE SLOT</th>
                <th bgcolor=" green">FWAD</th>
                <th bgcolor=" green">AI</th>
                <th bgcolor=" green">FWAD</th>
                <th bgcolor=" green">FREESLOT</th>
                <th bgcolor="green">FREE SLOT</th>
            </tr>
            <tr>
                <th bgcolor="blue">3-5</th>
                <th bgcolor="green">AI</th>
                <th bgcolor="green">DS</th>
                <th bgcolor="green">FREE SLOT</th>
                <th bgcolor="green">FREE SLOT</th>
                <th bgcolor="green">COMPANY SPECIFIC</th>
                <th bgcolor="green">FREE SLOT</th>
            </tr>

        </table>
    </table>
    <br>
    <table border="1" class="table2">
      <tr>
        <th>S.No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
      </tr>
      <tr>
        <td>1.</td>
        <td>19EC408</td>
        <td>Microprocessor and Microcontroller (MPMC)</td>
      </tr>
      <tr>
        <td>2.</td>
        <td>19AI403</td>
        <td>Introduction To DataScience</td>
      </tr>
      <tr>
        <td>3.</td>
        <td>19CS414</td>
        <td>Mobile Application Development</td>
    </tr>
    <tr>
      <td>4.</td>
      <td>19AI414</td>
      <td>Fundamentals of Web Applications Development (WEB)</td>
    </tr>
    <tr>
      <td>5.</td>
      <td>19CS504</td>
      <td>Software Project Management(SPM)</td>
    </tr>
    <tr>
      <td>6.</td>
      <td>19CS413</td>
      <td>Artificial Intelligence</td>
    </tr>
    <tr>
      <td>7.</td>
      <td>19EY705</td>
      <td>Company Specific Assessments for Employability</td>
    </tr>
  </table>


       </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (208).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
