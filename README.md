# Ex03 Time Table
## Date: 14.03.2024
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
<html>
<head>
<title>My Time Table</title>
</head>
<body>
<center>
<img src="logo.png"height="100"width="540">
</center>
<br>
<table align="center" width="540"cellspacing="2"cellpadding="1" border="5" bgcolor="silver">
<caption><b>>MY TIMETABLE</b></caption>
<tr align="center">
<th bgcolor="blue">Day/Time></th>
<th bgcolor="blue">Monday</th>
<th bgcolor="blue">tuesday</th>
<th bgcolor="blue">wednesday</th>
<th bgcolor="blue">thursday</th>
<th bgcolor="blue">friday</th>
<th bgcolor="blue">saturday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td>FREE SLOT</td>
<td>DIGITAL ELECTRONICS</td>
<td>THEORY OF COMPUTATION6</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>DIGITAL ELECTRONICS</td>
<td>CREATIVE SKILLS</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>COMMUNICATIVE ENGLISH</td>
<td>COMPUTER NETWPORKS</td>
<td>FREE SLOTS</td>
<td>COMPUTER NETWORRKS</td>
<td>fundamentals of c</td>
<td>THEORY OF COMPUTATION</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H </td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>EMPD</td>
<td>FUNDAMENTALS OF WEB</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>EMPD</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>FUNDAMENTALS OF C</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S.No</th>
<th>Subject code</th>
<th>Subject name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB </td> 
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>
<td>FUNDAMENTALS OF C </td> 
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CP205</td>
<td>THEORY OF COMPUTATION</td> 
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19AI414</td>
<td>PRINCIPLES OF CHEMISTRY </td> 
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA211</td>
<td>COMPUTER NETWORKS</td> 
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EY701</td>
<td>FUNDAMENTALS OF WEB </td> 
<tr>
<td align="center">7.</td>
<td align="center">19EE404</td>
<td>DIGITAL ELECTRONICS</td> 
</tr>
</tr>
</table>
</body>
</html>

## OUTPUT
![Screenshot 2024-03-14 133145](https://github.com/ajinajoshpin/slot/assets/148514578/9b95d7e8-c913-4ef0-8dbd-4f409395af07)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
