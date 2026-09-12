# C Programming Basics

## 1. Data Types

| Data Type | Description |
|---|---|
| `int` | Stores integer values. |
| `float` | Stores single-precision floating-point values. |
| `double` | Stores double-precision floating-point values. |
| `char` | Stores a single character. |
| `bool` | Stores a Boolean value (true or false). |
| `void` | Represents no value or no data type. |

## 2. Format Specifiers

| Format Specifier | Description |
|---|---|
| `%d` | Signed decimal integer |
| `%u` | Unsigned decimal integer |
| `%o` | Octal integer |
| `%x` | Hexadecimal integer (lowercase) |
| `%X` | Hexadecimal integer (uppercase) |
| `%f` | Floating-point value |
| `%e` | Floating-point value in exponential notation |
| `%c` | Character |
| `%s` | String |
| `%ld` | Long integer |

## 3. Input/Output Functions

### scanf()

`scanf()` is used to take formatted input from the user.

### printf()

`printf()` is used to display formatted output.

### getchar()

`getchar()` reads a single character from the input.

### putchar()

`putchar()` displays a single character.

### fgets()

`fgets()` is used to read a string, including spaces.

### puts()

`puts()` displays a string followed by a new line.

## 4. Escape Sequences

| Escape Sequence | Meaning | Example |
|---|---|---|
| `\n` | New line | `printf("Hello\n");` |
| `\t` | Horizontal tab | `printf("Name\tAge");` |
| `\\` | Backslash | `printf("\\");` |
| `\"` | Double quotation mark | `printf("\"Hello\"");` |
| `\'` | Single quotation mark | `printf("\'A\'");` |

## 5. Precision

Precision specifies the number of digits displayed after the decimal point for floating-point output.

For example:

```c
printf("%.2f", value);
