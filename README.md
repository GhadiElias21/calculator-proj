# calculator project

simple calculator application with dark mode feature 

[online demo](https://calc-proj.netlify.app/)

 - To store the information of the operand and all the other methods ,i decided to create a calculator class.

 - In the constructor we put previousOperandTextElement,currentOperandTextElement because we need to know where to place the display text of our calculator

 - We use the clear function at the start because we need to clear all the inputs when creating a new calculator

  - so to append the selected operation or number we need to loop over all the number and operations buttons without creating a new array we use forEach
  
  - every time we click on a number or an operation the display will be updated

 - We convert the inputs to a string because javascript will try to add these as actual number so we need 1+1=2 instead of 1+1=11

 - we check if the user have chosen 2 operands and an operation ,then we can compute and get an output that we replace current operand with
 
 - then we should format the output so we convert the number to a string ,then we seperate the integer and decimal digits

 - integerDisplay = integerDigits.toLocaleString("en", {
        maximumFractionDigits: 0,
      }); 
      - we use toLocaleString to format the output
      - we use maximumFractionDigits so there can never be any decimal places after this value when it gets converted to a string with a bunch of commas


![image](https://github.com/GhadiElias21/calculator-proj/assets/92365477/8006d855-7d1d-44db-be4d-f2fcd6f2eb88)

![image](https://github.com/GhadiElias21/calculator-proj/assets/92365477/e6d2a419-e365-4342-ae17-e13bee758e5c)
