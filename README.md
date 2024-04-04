# Ex03 Time Table

## Date: 04/04/2024

## AIM:
To write a html webpage page to display your slot timetable.

## ALGORITHM:
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

## PROGRAM:
```
<html>
<head>
<title> TIME TABLE </title>   
</head>
<body>
<center>
<img src="/static/logo.png"height="80"width="900">
</center>

<table align="center" width="1200" height="80" border="2" bgcolor="Lavender" cellspacing="5" cellpadding="5">
<caption><b>SLOT TIME TABLE - YUGENDARAN G (212221220063)</b></caption>

<tr bgcolor="pink">
     <th> Day/Time </th>
     <th> Monday </th>
     <th> Tuesday </th>
     <th> Wednesday </th>
     <th> Thursday </th>
     <th> Friday </th> 
     <th> Saturday </th>
</tr>
<tr align="center">
   <th bgcolor="pink"> 8-10 </th>
   <td bgcolor="goldenrod"><b> Fundamentals Of Web Application Development</b></td>
   <td bgcolor="teal"><b>Biomedical Sensors and Measurements</b></td>
   <td bgcolor="lightgreen"><b>MERN Full Stack</b></td>
   <td> Free Slot </td>
   <td bgcolor="lightgreen"><b> MERN Full Stack </b></td>
   <td> Free Slot </td>
</tr>
<tr align="center">
    <th bgcolor="pink"> 10-12 </th>
    <td bgcolor="orchid"><b> Artificial Intelligence </b></td>
    <td bgcolor="lightgreen"><b>MERN Full Stack</b></td>
    <td bgcolor="teal"><b>Biomedical Sensors and Measurements</b></td>
    <td> Free Slot </td>
    <td bgcolor="lightsalmon"><b> Yoga and Meditation </b></td>
    <td bgcolor="darkorchid"><b>Artificial Intelligence</b></td>
</tr>
<tr align ="center">
    <th bgcolor="pink"> 12-1 </th>
    <th colspan="3">LUNCH</th>
    <th bgcolor="white" colspan="1">MENTOR MEET</th>
    <td colspan="2" align="center"><b>LUNCH</b></td>
</tr>
<tr align ="center">
    <th bgcolor="pink"> 1-3 </th>
    <td > Free Slot </td>
    <td bgcolor="crimson"><b>Gender Sensitization</b> </td>
    <td> Free Slot </td>
    <td bgcolor="lightgreen"><b> MERN Full Stack</b> </td>
    <td> Free Slot </td>
    <td> Free Slot </td>
</tr>
<tr align ="center">
    <th bgcolor="pink"> 3-5 </th>
    <td bgcolor="lightgreen"><b> MERN Full Stack </b> </td>
    <td>Free Slot</td>
    <td>Free Slot</td>
    <td bgcolor="goldenrod"> <b> Fundamentals Of Web Application Development</b>
    <td bgcolor="aqua"> <b> Company Specific Assessments for Employability</b> </td>
    <td bgcolor="goldenrod"> <b> Fundamentals Of Web Application Development</b></td>
</tr>
</tr>
</table>
<br>

<table align="center" width="800" height="100" border="5" cellspacing="10" cellpadding="10">
<tr align="center">
<th> S.NO. </th>
<th> Subject Code</th>
<th> Subject Name </th>
</tr>
<tr align="center">
<td bgcolor="lightgreen"> 1. </td>
<td bgcolor="lightgreen"> 19AI512C </td>
<td bgcolor="lightgreen"> MERN Full Stack </td>
</tr>
<tr align="center">
<td bgcolor="goldenrod"> 2. </td>
<td bgcolor="goldenrod"> 19AI414 </td>
<td bgcolor="goldenrod"> Fundamentals Of Web Application Development </td>
</tr>
<tr align="center">
<td bgcolor="teal"> 3. </td>
<td bgcolor="teal"> 19MD601 </td>
<td bgcolor="teal"> Biomedical Sensors and Measurements </td>
</tr>
<tr align="center">
<td bgcolor="orchid"> 4. </td>
<td bgcolor="orchid"> 19CS413 </td>
<td bgcolor="orchid"> Artificial Intelligence </td>
</tr>
<tr align="center">
<td bgcolor="crimson"> 5. </td>
<td bgcolor="crimson"> 19EN609 </td>
<td bgcolor="crimson"> Gender Sensitization </td>
</tr>
<tr align="center">
<td bgcolor="lightsalmon"> 6. </td>
<td bgcolor="lightsalmon"> 19EN616 </td>
<td bgcolor="lightsalmon"> Yoga and Meditation  </td>
</tr>
<tr align="center">
<td bgcolor="aqua"> 7. </td>
<td bgcolor="aqua"> 19EY706 </td>
<td bgcolor="aqua"> Company Specific Assessments for Employability  </td>
</tr>
</html>
```

## OUTPUT:
![image](https://github.com/Yugendaran/slot/assets/128135616/d4a68701-54a2-4a0f-bbf3-c74a225f6d6f)

![image](https://github.com/Yugendaran/slot/assets/128135616/dc9b70ec-de8a-4fb8-a496-ceae32e3f732)



## RESULT:
The program for creating slot timetable using basic HTML tags is executed successfully.
