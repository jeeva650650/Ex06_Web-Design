# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
<title>Javascript program to display result of a student</title>
<script type="text/javascript">
function student()
{
var mark1,mark2,mark3,total,percentage;
mark1=parseInt(prompt("Enter Subject-1 Marks"))
mark2=parseInt(prompt("Enter Subject-2 Marks"))
mark3=parseInt(prompt("Enter Subject-3 Marks"))
mark4=parseInt(prompt("Enter Subject-4 Marks"))
mark5=parseInt(prompt("Enter Subject-5 Marks"))
total=mark1+mark2+mark3+mark4+mark5
percentage=total/5;
if((percentage>=91)&&(percentage<=100))
{
alert("O Grade");
}
else if((percentage>=81)&&(percentage<=90))
{
    alert("A+ Grade");
}
else if((percentage>=71)&&(percentage<=80))
{
    alert("A Grade");
}
else if((percentage>=61)&&(percentage<=70))
{
    alert("B+ Grade");
}
else if((percentage>=51)&&(percentage<=60))
{
    alert("B Grade");
}
else
{
    alert("No Grade");
}
}
</script>
</head>
<body>
<h1 onclick="student()">
Click here to Find Grade Result of a Student
</h1>
</body>
</html>
```
## OUTPUT
![Screenshot (840)](https://github.com/jeeva650650/Ex06_Web-Design/assets/167397876/035e1ce2-308e-4713-a7e0-cd2f0b4b93e4)
![Screenshot (839)](https://github.com/jeeva650650/Ex06_Web-Design/assets/167397876/c4ea93dc-00fc-4036-92f4-27731e3389a6)
![Screenshot (838)](https://github.com/jeeva650650/Ex06_Web-Design/assets/167397876/aaeefc35-7a5d-440d-9c4c-6f429092c8a3)
![Screenshot (837)](https://github.com/jeeva650650/Ex06_Web-Design/assets/167397876/b95c7d1e-3c1a-4dae-8499-1356797c13cd)
![Screenshot (836)](https://github.com/jeeva650650/Ex06_Web-Design/assets/167397876/91708b3b-43dc-4b71-b95f-ee3e1b6fec44)
![Screenshot (835)](https://github.com/jeeva650650/Ex06_Web-Design/assets/167397876/ca77a827-088c-4927-9684-4f3a9bcc0508)


## RESULT
  Student result using JavaScript is created successfully.
