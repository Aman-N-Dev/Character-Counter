# Character Frequency Counter

A lightweight, efficient Python script designed to count the occurrences of all characters in a given string. The program processes an input string and outputs a dictionary (hash map) mapping each unique character to its respective frequency count.

## Features
- **Single-Pass Efficiency**: Processes the string in a single iteration ($O(n)$ time complexity).
- **Graceful Edge-Case Handling**: Correctly returns an empty dictionary literal (`{}`) if an empty string is provided.
- **Pure Python**: Implemented entirely with native types without requiring external dependencies.

## Problem Specification
- **Input**: A string `s` containing any combination of alphanumeric text, whitespaces, or symbols.
- **Output**: A dictionary where keys are unique characters from the string and values are integers representing their totals.

### Examples
```python
count("aba")  # Returns: {'a': 2, 'b': 1}
count("")     # Returns: {}