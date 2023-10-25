# Ex03 Time Table

## Date: 

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

## CODE

```html
<html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Timetable</title>
    <style>
        .table1{
            background-color:darkgoldenrod ;
            border-color: gray;
            text-align: center;
            width: 800px;
            height: 250px;
        }
        .table2{
            border-color: gray;
            text-align: center;
            width: 800px;
            height: 250px; 
        }
        .name{
            padding-left: 185px;
        }
        .row1{
            background-color: bisque;
        }
        .c1{
            background-color: bisque;
        }
    </style>
</head>
<body>
    <img src = "http://training.saveetha.in/pluginfile.php/1/core_admin/logo/0x150/1623542614/logo_1.png" width = "800" height="150">
    <h3 class = "name">SLOT TIMETABLE - MUGILAN P (212221040107)</h3>
    <table border="1" class = "table1">
        <tr class = "row1">
            <th class="c1">Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <td class="c1">8-10</td>
            <td>DAA</td>
            <td>MC</td>
            <td>Free</td>
            <td>FWAD</td>
            <td>EES</td>
            <td>FWAD</td>
        </tr>
        <tr>
            <td class="c1">10-12</td>
            <td>Free</td>
            <td>CNS</td>
            <td>CNS</td>
            <td>Free</td>
            <td>DAA/DW</td>
            <td>Free</td>
            
        </tr>
        <tr>
            <td class="c1">12-1</td>
            <th colspan="6">LUNCH BREAK</th>
        </tr>
        <tr>
            <td class="c1">1-3</td>
            <td>MAD</td>
            <td>Free</td>
            <td>DW</td>
            <td>Free</td>
            <td>CD</td>
            <td>Free</td>
        </tr>
        <tr>
            <td class="c1">3-5</td>
            <td>Free</td>
            <td>FWAD</td>
            <td>CD</td>
            <td>Free</td>
            <td>MC</td>
            <td>MAD</td>
        </tr>
    </table>
    <br>
    <br>
    <table border="1" class="table2">
        <tr>
            <th>S.No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Applications Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19CS402</td>
            <td>Design Analysis and Algorithm (DAA)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19CS412</td>
            <td>Cryptography and Network Security (CNS)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19CS517</td>
            <td>Mobile Computing (MC)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19CS521</td>
            <td>Data Warehousing and Data Mining (DW)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19EY705</td>
            <td>Employment Enhancement Skills (EES)</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>19CS409</td>
            <td>Complier Design (CD)</td>
        </tr>
        <tr>
            <td>8.</td>
            <td>19CS414</td>
            <td>Mobile Application Development (MAD)</td>
        </tr>
    </table>
</body>
</html>
```

## OUTPUT
![image](https://github.com/Mugilan212/slot/assets/144508901/3bc62504-bb88-49bf-b5d8-f4be177c881b)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
