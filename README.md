# Day-40-Celsius-to-Fahrenheit
Day 40/100 - Python Program to Convert Celsius to Fahrenheit

# Convert Celsius to Fahrenheit
A program to calculate and convert a temperature reading from degrees Celsius to degrees Fahrenheit using the standard mathematical formula.

## 📝 Description

This program prompts the user to input a temperature value in Celsius. It then mathematically translates that value into the Fahrenheit scale.

The core of the program is a dedicated function `celsius_to_fahrenheit(celsius)` that applies the standard conversion formula: `Fahrenheit = (Celsius * 9/5) + 32`. By explicitly casting the user's input to a floating-point number (`float()`), the script ensures it can accurately handle both whole integers (like 0 or 100) and precise decimal readings (like 37.5) without losing data.

---

## 🎯 Problem Statement

### Input:

* **Input 1:** A floating-point number representing the temperature in degrees Celsius.

### Output:

* A formatted string stating: "[celsius]℃ is equal to [fahrenheit]°F".

### Rules:

1. The program must accept numerical input from the user.
2. The input must be converted to a `float` data type to support decimal temperatures.
3. The program must use a function to calculate the conversion using the formula `(C * 9/5) + 32`.
4. The program must print the final calculated temperature utilizing Python's f-string formatting.

---

## 💡 Examples

### Example 1 (Freezing Point of Water)

**Input:**

```
0

```

**Output:**

```
0.0℃ is equal to 32.0°F

```

**Explanation:** The formula processes `(0 * 9/5) + 32`. The multiplication results in 0, leaving exactly 32.0.

### Example 2 (Boiling Point of Water)

**Input:**

```
100

```

**Output:**

```
100.0℃ is equal to 212.0°F

```

**Explanation:** The formula processes `(100 * 9/5) + 32`. `100 * 1.8 = 180`. `180 + 32 = 212.0`.

### Example 3 (Negative Temperature)

**Input:**

```
-40

```

**Output:**

```
-40.0℃ is equal to -40.0°F

```

**Explanation:** -40 is the unique intersection point where the Celsius and Fahrenheit scales are exactly equal. `(-40 * 1.8) + 32 = -72 + 32 = -40.0`.

### Example 4 (Standard Decimal)

**Input:**

```
37.5

```

**Output:**

```
37.5℃ is equal to 99.5°F

```

**Explanation:** The floating-point logic accurately converts normal human body temperature (37.5°C) to its Fahrenheit equivalent (99.5°F).

---

## 🚀 How to Use

1. **Clone this repository** (or save the script)

```bash
git clone https://github.com/adiaryaz/Day-40-Celsius-to-Fahrenheit.git
cd celsius-to-fahrenheit

```

2. **Run the program**:

```bash
python main.py

```

Enter a temperature value in Celsius when prompted to see its Fahrenheit equivalent printed to the console.
