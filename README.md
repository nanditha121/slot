# Ex03 Time Table
## Date:14-03-2024

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
        <title>MY TIME TABLE</title>
    </head>
    <body>
        <center>
           <img src="logo.png" height="150" width="1000">   
        </center>
           <br>
           <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="khaki">
           <caption><b>SLOT TIME TABLE - NARRA NANDITHA(212221040111)</b></caption>
           <tr align="center">
           <th bgcolor="olivedrab">Day/Time</th>
           <th bgcolor="olivedrab">MONDAY</th>
           <th bgcolor="olivedrab">TUESDAY</th>
           <th bgcolor="olivedrab">WEDNESDAY</th>
           <th bgcolor="olivedrab">THURSDAY</th>
           <th bgcolor="olivedrab">FRIDAY</th>
           <th bgcolor="olivedrab">SATURDAY</th>
           </tr>
           <tr align="center">
           <th bgcolor="olivedrab">8-10</th>
           <td> FRENCH </td>
           <td> FREE SLOT </td>
           <td> MPMC </td>
           <td> FRENCH</td>
           <td> WEB </td>
           <td> FRENCH </td>
           </tr>
           <tr align="center">
           <th bgcolor="olivedrab">10-12</th>
           <td> FREE SLOT </td>
           <td> SPM </td>
           <td> FREE SLOT </td>
           <td> SPM</td>
           <td> MPMC </td>
           <td> DS</td>
           </tr>
           <tr>
           <th bgcolor="olivedrab">12-1</th>
           <td colspan="6" align="center">L U N C H</td>
           </tr>
           <tr align="center">
           <th bgcolor="olivedrab">1-3</th>
           <td> FREE SLOT </td>
           <td> WEB </td>
           <td> MAD</td>
           <td> WEB </td>
           <td> FREE SLOT </td>
           <td> MAD </td>
           </tr>
           <tr align="center">
           <th bgcolor="olivedrab">3-5</th>
           <td> FREE SLOT</td>
           <td> DS</td>
           <td> FREE SLOT </td>
           <td> FREE SLOT</td>
           <td> COMPANY</td>
           <td> FREE SLOT</td
           </tr>
           </table>
           <br>
           <table align="center" cellspacing="2" cellpadding="4" border="2">
           <tr align="center">
           <th>S.NO.</th>
           <th>SUBJECT CODE</th>
           <th>SUBJECT NAME</th>
           </tr>
           <tr>
           <td align="center">1.</td>
           <td align="center">19AI414</td>
           <td>FUNDAMENTALS OF WEB APPLICATION</td>
           </tr>
           <tr>
           <td align="center">2.</td>
           <td align="center">19EC408</td>
           <td>MICRO PROCESSOR MICRO CONTROLLER</td>
           </tr>
           <tr>
           <td align="center">3.</td>
           <td align="center">19EY706</td>
           <td>COMPANY SPECIFIC ASSESMENTS AND EMPLOYABILITY</td>
           </tr>
           <tr>
           <td align="center">4.</td>
           <td align="center">19EN611C</td>
           <td>FRENCH BASIC AND ADVANCED</td>
           </tr>
           <tr>
           <td align="center">5.</td>
           <td align="center">19AI403</td>
           <td>INTORDUCTION TO DATASCIENCE</td>
           </tr>
           <tr>
           <td align="center">6.</td>
           <td align="center">19CS414</td>
           <td>MOBILE APPLICATION DEVOLOPMENT</td>
           </tr>
           <tr>
            <td align="center">6.</td>
            <td align="center">19CS504</td>
            <td>SOFTWARE PROJECT MANAGMENT</td>
            </tr>
           </table>
    </body>
</html>

```


## OUTPUT

![alt text](<Screenshot (10).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
