# Exercise 3 - Input & Output!

Learn how to make your program talk with users and get their responses 🗣️

## 1. Theory
---

### ✅ Console Output

There are several ways to display text in the console:

```csharp
// Basic output
Console.Write("No line break");
Console.WriteLine("Adds a line break at the end");

// Combining text and variables
string name = "Mario";
int score = 100;
Console.WriteLine("Player: " + name);              // Using +
Console.WriteLine($"Score: {score}");             // Using $
Console.WriteLine("Lives: {0}", 3);               // Using format

// Empty line
Console.WriteLine();
```

### ✅ Console Input

To get information from the user:

```csharp
// Reading text
string name = Console.ReadLine();

// Reading numbers (needs conversion!)
string input = Console.ReadLine();
int age = Convert.ToInt32(input);      // For integers
double price = Convert.ToDouble(input); // For decimals

// Shorter way for numbers
int level = int.Parse(Console.ReadLine());
double health = double.Parse(Console.ReadLine());
```

### ✅ Common Mistakes to Avoid

```csharp
// WRONG: Forgetting to convert numbers
string input = Console.ReadLine();
int number = input;  // This will not work!

// RIGHT: Always convert number inputs
int number = Convert.ToInt32(Console.ReadLine());

// WRONG: Trying to read a char directly
char grade = Console.ReadLine();  // This will not work!

// RIGHT: Reading a char
char grade = Console.ReadLine()[0];  // Takes first character
```

## 2. Task
---

Create a program that asks questions about a video game character and then displays a summary:

1. Ask these questions and store the answers in variables:
   - "Enter character name: " (string)
   - "Enter character level (1-99): " (int)
   - "Enter character class initial (W for Warrior): " (char)
   - "Enter character health (0.0-100.0): " (double)

2. Then display a summary in exactly this format:
```
=== CHARACTER SHEET ===
Name: {name}
Level {level} {class}
HP: {health}/100
====================
```

## 3. Allowed resources
---

Internet, with the exception of AI chatbots such as ChatGPT (I'll easily see if you've used one).

## 4. Hints
---

If your program crashes or displays wrong information, check that you:
- Convert numeric inputs (level and health) to the right type
- Take only the first character for the class initial
- Use exact text for questions and summary
- Test with these inputs:
  - Name: "Cloud"
  - Level: 7
  - Class: 'W'
  - Health: 84.5

The output should look exactly like:
```
=== CHARACTER SHEET ===
Name: Cloud
Level 7 W
HP: 84.5/100
====================
```
