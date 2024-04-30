## Ex.06 JavaScript - Student Result
## DATE:30/04/2024
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
<title>WEB_EX NO_06</title>

<script type="text/javascript">
function gomathy()
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
    alert("U Grade");
}
}
</script>
</head>
<body bgcolor="pink">
<h1 onmouseover="gomathy()">
TOUCH HERE</h1> <BR>
  <H2>   To Find Grade Result of the Student</H2>

</body>
</html>
```

## OUTPUT

![1](https://github.com/GOMATHY1719/Ex06/assets/165985023/7f77e733-141d-4310-885c-0b8fe8dddcbd)

![2](https://github.com/GOMATHY1719/Ex06/assets/165985023/b1b6f73f-2555-4086-9c0d-5763dcfa6eed)

![3](https://github.com/GOMATHY1719/Ex06/assets/165985023/29ef141a-37fc-49d6-af9d-6e6608ceed7a)

![4](https://github.com/GOMATHY1719/Ex06/assets/165985023/f717b177-2171-4059-9cfa-a35384a81cdd)

![5](https://github.com/GOMATHY1719/Ex06/assets/165985023/b8349510-3a43-4264-9a3b-dfee682618c7)

![6](https://github.com/GOMATHY1719/Ex06/assets/165985023/ecbd0e43-f489-44a2-94e3-743efe60cab3)

![7](https://github.com/GOMATHY1719/Ex06/assets/165985023/e4204ae6-9607-4d26-af98-3aad7d739e38)


## RESULT
  Student result using JavaScript is created successfully.
