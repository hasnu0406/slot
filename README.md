# Ex04 Time Table
## Date: 17-10-2024

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
<html></html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="sec1.png"height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="4" border="5" bgcolor="gold">
<caption><b>SLOT TIMETABLE - HASNA MUBARAK AZEEM (212223240052)</b></caption>
<tr align="center">
	<th bgcolor="blue">Day/Time</th>
	<th bgcolor="blue">Monday</th>
	<th bgcolor="blue">Tuesday</th>
	<th bgcolor="blue">Wednesday</th>
	<th bgcolor="blue">Thursday</th>
	<th bgcolor="blue">Friday</th>
    <th bgcolor="blue">Saturday</th>
</tr>
<tr align="center">
	<th bgcolor="blue">8-10</th>
	<td>FREE </td>
	<td>OPERATING SYSTEM</td>
	<td>WEB</td>
	<td>COMPILER DESIGN</td>
	<td>PMC</td>
    <td>OPERATING SYSTEM</td>
</tr>
<tr align="center">
	<th bgcolor="blue">10-12</th>
	<td>FREE</td>
	<td>FREE</td>
	<td>FREE</td>
	<td>INTRO TO ML </td>
	<td>TRANSFORMS</td>
    <td>INTRO TO ML</td>
</tr>
<tr>
	<th bgcolor="blue">12-1</th>
	<td colspan="6" align="center">L U N C H   B R E A K</td>
</tr>
<tr align="center">
	<th bgcolor="blue">1-3</th>
	<td>PMC</td>
	<td>FREE</td>
	<td>MENTOR MEET</td>
	<td>FREE</td>
	<td>FREE</td>
    <td>FREE</td>
</tr>
<tr align="center">
	<th bgcolor="blue">3-5</th>
	<td>TRANSFORMS</td>
	<td>FREE</td>
	<td>FREE</td>
	<td>FREE</td>
	<td>FREE</td>
    <td>COMPILER DESIGN</td>
</tr>
</table>
</br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19EE309</td>
<td>PROGRAMMING MICROCONTROLLER</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19MA219</td>
<td>TRANSFORMS AND ITS APPLICATION</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS405</td>
<td>OPERATING SYSTEM</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19AI410</td>
<td>INTRODUCTION TO MACHINE LEARNING</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19CS409</td>
<td>COMPILER DESIGN</td>
</tr>
<td align="center">9.</td>
<td align="center">ECA-M</td>
<td>MENTOR MEET</td>
</tr>


</table>
</body>
</html>
```

## OUTPUT
![image](https://github.com/user-attachments/assets/b0bb4910-59b5-486d-a76b-4975d8ff97a0)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
