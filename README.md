# Project 2: Quadratic Equation

### OBJECTIVES  
- Read data from the keyboard.  
- Use arithmetic operators.  
- Use conditional logic (`if`, `else`, and `else if`).  

### PROGRAM DESCRIPTION  
The quadratic formula provides the solution(s) to a quadratic equation of the form:  

$$
ax^2 + bx + c = 0, \quad a \neq 0
$$

The formula is given by:  

$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

The discriminant of the quadratic equation is:  

$$
b^2 - 4ac
$$

- If $b^2 - 4ac > 0$, then there are **two real solutions**.  
- If $b^2 - 4ac = 0$, then there is **one real solution**.  
- If $b^2 - 4ac < 0$, then there are **two complex solutions**.  

For this program, you will prompt the user to enter the coefficients of a quadratic equation, determine the number and type of solutions, and then find and display the solution(s).  

## PROGRAM SPECIFICATIONS  
1. Create a new class called `QuadraticSolver`.  
2. In the `main` method, implement the following:  
   - Declare a `Scanner` variable called `input`.  
   - Declare three `double` variables: `a`, `b`, and `c`.  
   - Prompt the user to enter a value for each coefficient and assign them to `a`, `b`, and `c`.  
   - If `a == 0`, display an error message and terminate the program. Otherwise, use the discriminant method to determine and display the number and type of solutions.  
   - Find the solution(s) using the quadratic formula and display them using `printf`, rounded to four decimal places.  

## SAMPLE OUTPUT
```
This program solves a quadratic equation in standard form ax^2 + bx + c = 0

Please enter the following: Quadratic coefficient a: 1 Linear coefficient b: 2 Constant c: 3

The quadratic equation has two complex solutions: x = -1.0000 + 1.4142i x = -1.0000 – 1.4142i

Quadratic coefficient a: 1 Linear coefficient b: 2 Constant c: 1

The quadratic equation has one real solution: x = -1.0000

Quadratic coefficient a: 1 Linear coefficient b: 3 Constant c: 2

The quadratic equation has two real solutions: x = -2.0000 x = -1.0000
```

## CODING STANDARDS  
1. Use meaningful variable names.  
2. Remove comments generated by the IDE.  
3. Use **JavaDoc** to document your code and include the `@author` tag.  
4. Your output should be **user-friendly**.  
5. Your code must be **well-organized and easy to read**.  
