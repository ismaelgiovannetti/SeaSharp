# Exercise 1 - Types and Variables!

Learn how to store information in your programs using different types of variables 🎮

## 1. Theory
---

### ✅ What is a variable?

A variable is like a box where you can store different types of information. Each box (variable) has:
- A name (to find it later)
- A type (what kind of information it can hold)
- A value (the actual information)

### ✅ Basic Types in C#

Here are the most common types you'll use:

```csharp
// Numbers
int age = 13;           // Whole numbers
double price = 9.99;    // Decimal numbers

// Text
string name = "Mario";  // Any text between quotes
char grade = 'A';       // Single character (use single quotes!)

// True/False
bool isGameOver = false;  // Can only be true or false
```

### ✅ Creating Variables

To create a variable, you need to:
1. Choose its type
2. Give it a name
3. Give it a value

```csharp
// First way (all at once)
int score = 100;

// Second way (in two steps)
int lives;      // Create the variable
lives = 3;      // Give it a value later
```

### ✅ Changing Values

You can change a variable's value anytime after creating it:

```csharp
int coins = 0;      // Start with no coins
coins = 10;         // Found some coins!
coins = 5;          // Lost some coins...

string playerName = "Luigi";
playerName = "Mario";   // Changed player

char rank = 'C';
rank = 'S';            // Got a better rank!
```

## 2. Task
---

Create a program with these variables and final values:

```csharp
int health = 100;      // Should end up as 50
double magic = 20.5;   // Should end up as 75.5
string weapon = "Dagger";   // Should end up as "Sword"
bool isAlive = true;   // Should end up as false
char level = 'D';      // Should end up as 'A'
```

Make the necessary changes to reach these final values. Use comments to show your understanding!

## 3. Allowed resources
---

Internet, with the exception of AI chatbots such as ChatGPT (I'll easily see if you've used one).

## 4. Hints
---

If your values don't match exactly:
- Check that you're using the right type for each variable
- Remember to use single quotes for char ('A') and double quotes for string ("Sword")
- Make sure you're changing the values correctly
- Don't forget to add comments explaining what you're doing
