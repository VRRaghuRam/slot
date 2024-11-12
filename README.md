# Ex03 Time Table
## Date: 12/11/2024

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
    <body>
        <img src="logo.png" width="800" height="200"> 
        <table border="1" cellspacing="15" cellpadding="2">
            <caption>Timetable  NAME:V.R.Raghu Ram   REF.NO:24900512</caption>
            <tr bgcolor="green">
                <th>day/time</th>
                <th>monday</th>
                <th>tuesday</th>
                <th>wednesday</th>
                <th>thursday</th>
                <th>friday</th>
                <th>saturday</th>
            </tr>
            <tr>
                <td>8-10</td>
                <td colspan="1">free time</td>
                <td>EDM</td>
                <td>EDM</td>
                <td>ENG</td>
                <td>WEB</td>
                <td>DE</td>

            </tr>
            <TR>
                <td>10-12</td>
                
                <td colspan="1">ENG</td>
                <td>Maths</td>
                <td>C Program</td>
                <td>Career</td>
                <td>WEB</td>
                <td>Maths</td>
                

            </TR>
            <tr>
                <td>12-1</td>
                <td colspan="6" align="center">LUNCH</td>
                


            </tr>
            <tr>
                <td>1-3</td>
                <td colspan="1">Web</td>
                <td>Web</td>
                <td>Mentor meeting</td>
                <td>C program</td>
                <td>WEB</td>
                <td>free time</td>


            </tr>
        </table><br>





        <table border="1" cellspacing="15" cellpadding="2">
        <caption>Timetable  NAME:V.R.Raghu Ram    REF.NO:24900512</caption>
        <tr>
            <td>s.no</td>
            <td>subject code</td>
            <td colspan="4" align="center">subject name </td>
        </tr>
        <tr>
            <th>1</th>
            <th colspan="2">19AI414</th>
            <th colspan="3">fundamental of web application development(FWAD)</th>
        </tr>
        <tr>
            <th>2</th>
            <th colspan="2">19EN101</th>
            <th colspan="3">Communnicative English</th>
        </tr>
        <tr>
            <th>3</th>
            <th colspan="2">19EY708</th>
            <th colspan="3">Career Development Skills</th>
        </tr>
        <tr>
            <th>4</th>
            <th colspan="2">SH5616</th>
            <th colspan="3">Yoga</th>
        </tr>
        <tr>
            <th>5</th>
            <th colspan="2">19MA201</th>
            <th colspan="3">calculus and matrix algebra</th>
        </tr>
        <tr>
            <th>6</th>
            <th colspan="2">19EE404</th>
            <th colspan="3">Digital Electronics</th>
        </tr>
        <tr>
            <th>7</th>
            <th colspan="2">19AI302</th>
            <th colspan="3">EDM</th>
        </tr>
        
        
        
    
    </table>
    </body>
</html>
```


## OUTPUT
![Alt text](<slot timetable.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
