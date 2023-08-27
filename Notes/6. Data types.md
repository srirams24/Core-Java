# 6. ****Data types in Java****

## Understanding Data Types

- Data types in Java categorize the type of data a variable can hold.
- There are two main categories: primitive data types and Non-primitive data types types.
- In this guide, we are only focusing on primitive data types

## Primitive Data Types

- Primitive data types are the basic building blocks for variables in Java.
- They include integer, float, character, and boolean types.

### Integer Data Types

- Integers are whole numbers without decimal points.
- Java offers different integer types with varying ranges and sizes:
    - `byte`: 1 byte, range from -128 to 127
    - `short`: 2 bytes, range from -32,768 to 32,767
    - `int`: 4 bytes, range from -2^31 to 2^31 - 1 ( as we are counting 0, so we are subtracting 1 in the positive range)
    - `long`: 8 bytes, range from -2^63 to 2^63 - 1 (Use suffix `'L'`  while variable value assignment)

### Floating-Point Data Types

- Floating-point types represent numbers with decimal points.
- Two types are available:
    - `float`: 4 bytes, stores decimal values with limited precision (Use suffix `'f’`, while variable value assignment)
    - `double`: 8 bytes, stores decimal values with higher precision (default for decimal literals)

### Character Data Type

- The `char` data type is used to store a single character.
- It uses 2 bytes to represent Unicode characters.
- Characters are enclosed in single quotes ('A', '5', etc.).

### Boolean Data Type

- The `boolean` data type represents true or false values.
- It is used for logical operations and conditions.
- Variables of type boolean can only have two possible values: true or false.

## Creating Variables with Different Data Types

- Variables are created by specifying the data type, followed by the variable name and an optional value assignment.

### Example Code

```java
class Hello 
{
    public static void main(String args[])
    {
        byte byteValue = 127;
        short shortValue = 558;
        int intValue = 5;
        long longValue = 1234567890L;
        float floatValue = 5.8f;
        double doubleValue = 5.8;
        char charValue = 'K';
        boolean booleanValue = true;

    }
}
```

## Key Points:

- Understanding the purpose and characteristics of each data type is crucial for choosing the appropriate one for different scenarios.
- Naming conventions, data size, and ranges must be considered when selecting a data type.
- Variables store and manage data, allowing for data manipulation and processing in Java programs.

## Conclusion

- Data types define the nature of the data that variables can hold.
- Java's primitive data types cater to various needs for storing integers, floating-point numbers, characters, and boolean values.
- Choosing the right data type helps optimize memory usage and program performance.
