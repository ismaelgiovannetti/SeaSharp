# Exercise 2 - All types of operation!

There are several types of operation in C# and programming in general. Learn now how to use them :)

## 1. Theory
---

### ✅ Arithmethic operations

- Addition : a + b
- Substraction : a - b
- Multiplication : a * b
- Division : a / b

They work like the basic math operation you already know.

Exemples:

```csharp
int a = 3;
int b = 2;
int c = 0;

c = a + b; // c = 5
c = a - b; // c = 1
c = b - a; // c = -1
c = a * b; // c = 6
c = a / b; // c = 1
```

Note : You can update a variable's value using an operator in two ways

```csharp
int a = 1;

// First way
a = a + 1; // a = 2

// Other way
a += 1; // a = 3

// Works with every operation ;)
a *= a; // a = 9
```

### ✅ Comparison operations

- Equality : a == b
- Inequality : a != b
- Less than : a < b
- Greater than : a > b
- Less than or equal : a <= b
- Greater than or equal : a >= b

As their name suggests, these operations are used to check whether a comparison condition is true or false. The returns of these operators are always Booleans (True / False).

Exemples:

```csharp
int a = 3;
int b = 2;

a == b; // false
a != b; // true
a < b; // false
a > b; // true
a <= b; // false
a >= b // true
```

### ✅ Boolean operations

- Or : a || b
- And : a && b

These two operations allows you to check the trueness of multiple conditions.

Exemples:

```csharp
int a = 3;
int b = 2;

a == b; // false
a > b; // true

a == b || a > b // true, as long as one is true
a == b && a > b // false, both of them need to be true for it to be true
```

<br>

## 2. Task
---

Now that you know all that, write a console program that displays the results of the following operations.

- int a: Divide 10 by 3, then subtract 4 and finaly multiply by 12.
- int b: Multiply 2 by 6, then add 1 and square.
- bool c : Check if a is bigger than a
- bool d : Check if a is equal to b and if c is true
- bool e : Check if c or d is true

For each of these operation, write the result on the console.
<br>

## 3. Allowed resources
---

Internet, with the exception of AI chatbots such as ChatGPT, (I'll easily see if you've used one).

<br>

## 4. Hints
---

If your end results are not :
- a : -12
- b : 169
- c : false
- d : false
- e : false

You may need to familiarize yourself with the priorities of the operation.