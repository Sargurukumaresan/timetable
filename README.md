# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
```
<!DOCTYPE html> 
<html> 
 <head> 
 <title>TIME TABLE</title> 
 </head> 
 <body> 
 <table border = "1" cellspacing="1" bordercolor="black"  bgcolor="grey"> 
 <img src="logo.png">
 <tr> 
 <th colspan="8">TIME TABLE</th> 
 </tr> 
 <tr>
<th colspan="2" align="center"><b>Reference Number:</b></th> <td colspan="2" align="center"><b>21000733</b></td> <td colspan="2" align="center"><b>Name:</b></td> <td colspan="2" align="center"><b>Vetrivel</b></td>
</tr>
 <tr> 

 <th>DAYS</th> 
 <th>1</th> 
 <th>2</th> 
 <th>3</th> 
 <th>4</th>  
 <th>5</th> 
 <th>6</th>
<th>7</th> 
 </tr> 
  
 <tr> 
 <td>MONDAY</td>  <td colspan="2" align="center">-</td>  <td colspan="2">19MA221-Linear Algebra Laboratory</td> <th rowspan="2">lunch break</th> 
 <td colspan="2">19MA220-Mathematics for Artificial Intelligence</td>  </tr>

<tr>
 <td>TUESDAY</td>  <td colspan="2">19AI402-Web Technology Laboratory</td>  <td colspan="2">19AI303-Engineering Mechanics and Product Development</td> 
 <td colspan="2">19AI302-Engineering Design and Modeling</td>  </tr>

<tr>
 <td>WEDNESDAY</td>  <td colspan="2">19AI401-Fundamentals of Web Technology</td>   
 <td colspan="2">19MA220-Mathematics for Artificial Intelligence</td><td>ECA051-Mentoring</td>   
 <td colspan="2">-</td>  </tr>

<tr>
 <td>THURSDAY</td>  <td colspan="2">19AI302-Engineering Design and Modeling</td>  <td colspan="2">19AI301-Python Programming</td>  <th rowspan="2">lunch break</th>
  <td colspan="2">19AI303-Engineering Mechanics and Product Development</td>  </tr>

<tr>
 <td>FRIDAY</td>  <td colspan="2">19AI401-Fundamentals of Web Technology</td>  <td colspan="2">19AI301-Python Programming</td> 
   <td colspan="2" >19EY703-System of Numerical and Logical Terminologies</td>  </tr>

<tr>
 <td>SATURDAY</td>  <td colspan="7" align="center">Leave</td>  
<tr>
 <td>SUNDAY</td>   <td colspan="7" align="center">Leave</td>

  
 </table> 
  
 </body> 
</html>

```

# OUPUT


<!DOCTYPE html> 
<html> 
 <head> 
 <title>TIME TABLE</title> 
 </head> 
 <body> 
 <table border = "1" cellspacing="1" bordercolor="black"  bgcolor="grey"> 
 <img src="logo.png">
 <tr> 
 <th colspan="8">TIME TABLE</th> 
 </tr> 
 <tr>
<th colspan="2" align="center"><b>Reference Number:</b></th> <td colspan="2" align="center"><b>22002828</b></td> <td colspan="2" align="center"><b>Name:</b></td> <td colspan="2" align="center"><b>SARGURU K</b></td>
</tr>
 <tr> 

 <th>DAYS</th> 
 <th>8-9</th> 
 <th>9-10</th> 
 <th>10-11</th> 
 <th>11-12</th>  
 <th>12-1</th> 
 <th>1-2</th>
<th>2-3</th> 
 </tr> 
  
 <tr> 
 <td>MONDAY</td>  <td colspan="2" align="center">python programing</td> <td colspan="2">free</td> <th rowspan="2">lunch break</th> 
 <td colspan="2">Mathematics for Artificial Intelligence</td>  </tr>

<tr>
 <td>TUESDAY</td>  <td colspan="2">Web developement </td>  <td colspan="2">digital electronics</td> 
 <td colspan="2">physics for quantum computing</td>  </tr>

<tr>
 <td>WEDNESDAY</td>  <td colspan="2">Web development</td>   
 <td colspan="2">Mathematics for Artificial Intelligence</td><td></td>   
 <td colspan="2">-</td>  </tr>

<tr>
 <td>THURSDAY</td>  <td colspan="2">liner alzebra</td>  <td colspan="2">Python Programming</td>  <th rowspan="2">lunch break</th>
  <td colspan="2">web Development</td>  </tr>

<tr>
 <td>FRIDAY</td>  <td colspan="2">Web developement</td>  <td colspan="2">Python Programming</td> 
   <td colspan="2" >comunicative english</td>  </tr>

<tr>
 <td>SATURDAY</td>  <td colspan="7" align="center">working based on monday to friday time table</td>  
<tr>
 <td>SUNDAY</td>   <td colspan="7" align="center">holiday</td>

  
 </table> 
  
 </body> 
</html>