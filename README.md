# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```
a=int(input("Enter a number:"))
if a%2==0:
    print("EVEN")
else:
    print("ODD")
```
## Output

![image](https://github.com/user-attachments/assets/2ff672e2-ec35-4387-a624-9be70efff6bb)

![image](https://github.com/user-attachments/assets/eda8c0ce-7edf-43f2-9231-965a6d82e1db)

## Result
Thus a Python program to check whether the given number is **even** or **odd** using `if...else` statements is successfully verified.



# Ex 1:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
```
a=0==True
b=False==False
c=True+True
d=False+9
print("a is",a)
print("b is",b)
print("c is",c)
print("d is",d)
```

## Output

![image](https://github.com/user-attachments/assets/17dabfd2-d63b-486d-bd02-5793981f4dcf)


## Result
Thus a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False` is successfully verified.

# Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
```
A='T'
B='a'
print(A)
print(B)
```
## Output

![image](https://github.com/user-attachments/assets/9f2d9972-2022-4d9d-a2b6-bc13d6cfbdaa)


## Result
Thus a Python program that prints the characters `'T'` and `'a'` using character literals is succcessfully verified.


# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
```
a=int(input("Enter a real number:"))
b=int(input("Enter a imaginary number:"))
x=complex(a,b)
print(x)
print(x.real)
print(x.imag)
```

## Output

![image](https://github.com/user-attachments/assets/c199bad9-3533-41c6-948d-e1f1fe6ae90b)


## Result
Thus a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts is successfully verified.


# Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
```
  men_stepped_on_the_moon=input("Enter a string:")
  print(men_stepped_on_the_moon)
```

## Output

![image](https://github.com/user-attachments/assets/4b629e6a-61c5-41a9-813c-e00dc3408e7e)


## Result
Thus a Python program to read a string from the user and then print it is successfully verified.
