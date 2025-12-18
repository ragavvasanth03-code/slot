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

## PROGRAM
```
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <!DOCTYPE html>
<html> 
<head>
    <title>Timetable</title>
</head>            
<title>Google <div class="Timetable"></div></title>
    <body> 
     <center> 
     <img src="/logo.png" height="150" width="800">
     </center>
      <h3 align="center">  SLOT TIME TABLE - RAGAVAN V ( 25018843 ) </h3>
        <table align="center" border="5" cellpadding="6" cellspacing="2" bgcolor="cyan">
        <tr>
          <th bgcolor="yellow">Day</th>    
          <th bgcolor="yellow">8-10</th>
          <th bgcolor="yellow">10-12</th>
          <th bgcolor="yellow">12-1</th>
          <th bgcolor="yellow">1-3</th>
          <th bgcolor="yellow">3-5</th>
        </tr>
        <tr>
           <th bgcolor="yellow">MONDAY </th>
           <td>PYTHON  </td>
           <td>PYTHON  </td>
           <td rowspan="6">L<br>U<br>N<br>C<br>H </td>
           <td>WEB APP     </td>
           <td>FREE SLOT  </td>
        </tr>
        <tr>
            <th bgcolor="yellow">TUESDAY  </th>
            <td>WEB APP </td>
            <td>FREE SLOT</td>
            <td>PYTHON</td>
            <td>WEB APP </td>
         </tr> 
         <tr>
            <th bgcolor="yellow">WEDNESDAY </th>
            <td>WEB APP</td>
            <td>FREE SLOT </td>
            <td>MENTOR    </td>
            <td>FREE SLOT </td>
         </tr> 
         <tr>
            <th bgcolor="yellow">THURSDAY  </th>
            <td>FREE SLOT   </td>
            <td>FREE SLOT</td>
            <td>WEB APP  </td>
            <td>FREE SLOT </td>
         </tr>
          <tr>
            <th bgcolor="yellow">FRIDAY    </th>
            <td>FREE SLOT   </td>
            <td>PYTHON    </td>
            <td>PYTHON  </td>
            <td>FREE SLOT </td>
         </tr>
         <tr>
            <th bgcolor="yellow">SATURDAY  </th>
            <td>FREE SLOT</td>
            <td>FREE SLOT </td>
            <td>FREE SLOT </td>
            <td>FREE SLOT</td>
         </tr>
        </table>
        <br> 
        <table border="5" cellpadding="7" cellspacing="2" align="center">
         <tr>
           <th><h4>S.NO</h4></th>    
           <th><h4>SUBJECT CODE </h4></th>
           <th><h4>SUBJECT NAME </h4></th>
         </tr>
         <tr>
            <th>1.</th>
            <td>19AI301</td>
            <td>PYTHON PROGRAMMING  </td>
         </tr>
          <tr>
             <th>2.</th>
             <td>19AI414</td>
             <td>FUNDAMENDALS OF WEB APPLICATION DEVELOPMENT </td>
          </tr>
         </table>   
    </body>
</html>

</body>
</html>
</body>
</html>
```

## OUTPUT
<img width="1004" height="843" alt="image" src="https://github.com/user-attachments/assets/424eb2d4-8f00-4fcc-a66d-7b5093c348e0" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
