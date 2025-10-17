# Ex03 Time Table
## Date:17.10.2025
## NAME:ANISH ADAN THIVAKARAN
## REF.NO: 25017997

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using <table> tag in html.

### STEP 4
Add header row using <th> tag.

### STEP 5
Add your timetable using <td> tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM

<html>
    <body>
        <h3 align='center'>SLOT TIME TABLE- ANISH ADAN THIVAKARAN (25017997)</h3>
        <table border ="5" cellpadding="5" cellspacing="5" align='center'>
            <tr bgcolor="grey">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr bgcolor="cyan" align='center'>
                <th bgcolor="grey">8-10 </th>
                <td>FREE</td>
                <td>FREE</td>
                <td>WEB</td>
                <td>DS</td>
                <td>C PROGRAMMING</td>
                <td>FREE</td>
            </tr>
            <tr bgcolor="cyan" align='center'>
                <th bgcolor="grey">10-12</th>
                <td>FREE</td>
                <td>DS</td>
                <td>WEB</td>
                <td>C PROGRAMMING</td>
                <td>DS</td>
                <td>FREE</td>
            </tr>
            <tr bgcolor="cyan">
                <th bgcolor="grey">12-1</th>
                <th cOlspan="7">LUNCH</th>
            </tr>
            <tr bgcolor="cyan" align='center'>
                <th bgcolor="grey">1-3</th>
                <td>C PROGRAMMING</td>
                <td>DS</td>
                <td>MENTOR MEET</td>
                <td>WEB</td>
                <td>DS</td>
                <td>FREE</td>
            </tr>
            <tr bgcolor="cyan" align='center'>
                <th bgcolor="grey">3-5</th>
                <td>FREE</td>
                <td>WEB</td>
                <td>C PROGGRAMMING</td>
                <td>C PROGRAMMING</td>
                <td>FREE</td>
                <td>WEB</td>
            </tr>
        </table>
        <table border="2" cellpadding="5" align='center'>
            <tr>
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development(FWAD)</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI304</td>
                <td>C Programming</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19AI403</td>
                <td>Introduction to Data Science</td>
            </tr>
        </table>
    </body>
</html>

## OUTPUT

<img width="1920" height="1080" alt="Screenshot 2025-10-17 070032" src="https://github.com/user-attachments/assets/0dd88fa6-14b7-49e7-871e-fff0a77ae890" />

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully
