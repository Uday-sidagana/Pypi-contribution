# Pypi-contribution
# Greatest Module

The `Greatest` module provides a class `Greatest` with a static method `setGreat` that finds the greatest value from a list or a series of numbers. Users can either pass a predefined list or specify the number of values they want to enter manually.

## Installation

To use the `Greatest` module, simply download or clone this repository. Once you have the files, you can import the `Greatest` class directly into your project.

## Usage

### Method: `setGreat`
The `setGreat` method allows you to find the greatest number in a list or by providing a count of numbers to input.

#### Parameters:
- **arg**: Accepts either an `int` or `list`. If an integer is passed, it is treated as `n` (the number of values you want to enter manually). If a list is passed, the list values are used directly.
- **n** (optional): Specifies the number of values to input if a list is not provided.
- **listofchoice** (optional): A list of numbers to find the maximum from. Ignored if `arg` is an integer.

#### Returns:
- **int**: The greatest number from the provided or entered values.

### Example

```python
from Greatest import Greatest

# Option 1: Provide a number of inputs directly
greatest_value = Greatest.setGreat(5)  # Prompts for 5 values
print("Greatest Value:", greatest_value)

# Option 2: Provide a list directly
greatest_value = Greatest.setGreat([1, 3, 7, 2, 5])
print("Greatest Value:", greatest_value)
