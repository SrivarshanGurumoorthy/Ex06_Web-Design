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
<title>JavaScript program to display the result of a student</title>
<head>

 <script type="text/javascript">

 function fun()

      { 
         var mark1, mark2, mark3, mark4, mark5, total, percentage;

              mark1 = parseInt(prompt("Enter Subject-1 Marks")); 
              mark2 = parseInt(prompt("Enter Subject 2 Marks")); 
              mark3 = parseInt(prompt("Enter Subject 3 Marks"));
              mark4 = parseInt(prompt("Enter Subject 4 Marks")); 
              mark5 = parseInt(prompt("Enter Subject 5 Marks")); 
              total = mark1 + mark2 + mark3 + mark4 + mark5; 
              percentage = total / 5;

if (percentage >= 91 && percentage <= 100)
{
    alert("O Grade");
}
else if (percentage >= 81 && percentage <= 90)
{
    alert("A+ Grade");
}
else if (percentage >= 71 && percentage <= 80)
{
    alert("A Grade");
}
else if (percentage >= 61 && percentage <= 70)
{
    alert("B+ Grade");
}
else if (percentage >= 51 && percentage <= 60)
{
    alert("B Grade"); 
}
else
{
    alert("RA Grade");
}
}  
</script>
</head>
<body >
<h1 onclick="fun()">

CLICK ME TO FIND THE RESULT
</h1>
</body>
</html>
```


## OUTPUT
![Screenshot (45)](https://github.com/SrivarshanGurumoorthy/Ex06_Web-Design/assets/127816583/50ffc671-2b24-4096-81f4-c217de957641)
![Screenshot (48)](https://github.com/SrivarshanGurumoorthy/Ex06_Web-Design/assets/127816583/7e23eb0c-5fe9-4da2-95bd-1dad01a17bdd)
![Screenshot (49)](https://github.com/SrivarshanGurumoorthy/Ex06_Web-Design/assets/127816583/2b5d354d-49d5-43aa-ac8e-34a3c7c9bd01)
![Screenshot (50)](https://github.com/SrivarshanGurumoorthy/Ex06_Web-Design/assets/127816583/1c54c22e-6b04-4f5a-8a4e-7fbc81183a9a)
![Screenshot (51)](https://github.com/SrivarshanGurumoorthy/Ex06_Web-Design/assets/127816583/aa487de3-cf15-47cd-8caf-25328b24f62f)
![Screenshot (53)](https://github.com/SrivarshanGurumoorthy/Ex06_Web-Design/assets/127816583/018084cb-6fd9-48ca-8ca9-88f6a388fcbb)
![Screenshot (52)](https://github.com/SrivarshanGurumoorthy/Ex06_Web-Design/assets/127816583/b903495d-0c0f-46e5-b1c6-8c79b5262961)



## RESULT
  Student result using JavaScript is created successfully.
