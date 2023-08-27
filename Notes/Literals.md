# 7. ****Literal in Java****

## Understanding Literals in Different Data Types

- In programming, literals are constant values that are directly written in code, representing their respective data types.
- Java supports various types of literals for different data types, including integers, floating-point numbers, characters, and more.

## Integer Literals

- Integer literals are used to represent whole numbers.
- They can be written in different bases: decimal (base 10), binary (base 2), and hexadecimal (base 16).
- Binary literals start with `0b` followed by binary digits (0 or 1), e.g., `0b101` for decimal 5.
- Hexadecimal literals start with `0x` followed by hexadecimal digits (0-9, A-F), e.g., `0x7E` for decimal 126.

## Floating-Point Literals

- Floating-point literals represent numbers with decimal points.
- They can be written using exponential notation with an optional `E` or `e` indicating the exponent.
- For instance, `1.23E3` is equivalent to `1230.0` (1.23 * 10^3).

## Character Literals

- Character literals represent individual characters enclosed in single quotes.
- Unicode characters can be represented using escape sequences, such as `\\uXXXX`, where `XXXX` is the hexadecimal Unicode value.

## String Literals

- String literals are sequences of characters enclosed in double-quotes.
- They represent text data, and the backslash `\\` can be used to escape special characters within strings.

## Boolean Literals

- Boolean literals represent the two truth values: `true` and `false`.
- They are used to express logical conditions in programs.

## Working with Different Literals

- Literal values can be assigned to variables of appropriate data types.

### Example Code

```java
class Hello 
{
    public static void main(String args[])
    {
        int num = 9;                                          // Integer literal
        System.out.println("Integer Literal: " + num);
        int binaryNum = 0b101;                                // Binary literal (5 in decimal)
        System.out.println("Binary Literal: " + binaryNum);
        int hexNum = 0x7E;                                    // Hexadecimal literal (126 in decimal)
        System.out.println("Hexa Decimal Literal: " + hexNum);
        float floatValue = 5.6E2f;                            // Exponential notation (5.6 * 10^13)
        System.out.println("Float Literal: " + floatValue);
        char charValue = 'A';                                 // Character literal
        System.out.println("Character Literal: " + charValue);
        String text = "Hello";                                // String literal
        System.out.println("String Literal: " + text);
        boolean flag = true;                                  // Boolean literal
        System.out.println("Boolean Literal: " + flag);
    }
}

```

## Underscores for Readability

- Underscores in numeric literals improve readability, especially with large numbers.
- Example: `int million = 1_000_000;`

## Key Takeaways

- Literals are constant values directly written in code, representing various data types.
- Integer literals can be decimal, binary, or hexadecimal, with optional underscores for readability.
- Floating-point literals use exponential notation for compact representation.
- Character and string literals represent individual characters and text, respectively.
- Boolean literals represent the two logical values: `true` and `false`.
- Underscores improve readability, especially with large numbers.
