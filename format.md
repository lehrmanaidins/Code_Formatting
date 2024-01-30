# Code Formatting
- [Indents](#indents)
- [Spacing](#spacing)
  - [Exceptions](#exceptions)
- [Python](#python)

## Indents
All code indents/tabs should be 4 spaces in width.
> Hint: You can change the output of your tab key to type 4 spaces.
```java
for (int i = 0; i < 10; i++) {
⎵⎵⎵⎵System.out.println(i);
}
```

## Spacing
All program kewwords (Ex: for, in, while, not, etc.) \
and operators (Ex: +, -, *, /, %, (), etc.) shall be seperated \
by a space.
```java
if⎵(condition)⎵{
    ...
}
```
```java
int⎵x⎵=⎵1⎵+⎵2;
```

### Exceptions
#### Inside of Parentheses
The "inside" of a parentheses shall not have a space character.
```java
int x = (1 + 2);
//       ^    ^ No Spaces
```

#### Outside of Parentheses
The "outside" of a parentheses shall not have a space if it is used as a "calling" operator.
```java
int x = getNumber();
//               ^ No Space
```
However, if a parentheses is used as a mathmatical grouping operator, a space shall be placed /
on the outside of the parentheses.
```java
int x = (1 + 2)⎵*⎵(3 + 4);
```

#### Arrays and Lists
Square bracket array operators shall not be seperated from variable name by a space.
```java
int value = array[0];
//               ^ No Space
```

#### References and Pointers
Memory address operators like '&' and '*' shall be placed after DataType declaration and before variable name. \
There shall also be no space used to seperate operator from operatee.
```cpp
int* i; // '*' operator goes after datatype "int": "int*"
i = &j; // '&' operator goes before 
std::cout << *i << "\n"; // Dereference goes before variable name: "*i"
std::cout << &j << std::endl; // Reference operator goes before variable name: "&j"
```

## Python
```python
def function_name(a: Type1, b: Type1 | Type2) -> ReturnType:
    ''' funcion_name takes two variables {a} and {b} and does ...

    Args:
        a (Type1): The variable to ...
        b (Type1 | Type2): The variable to...

    Returns:
        Returns 'variable' of type 'Type' and ...
    '''
    variable: Type = Type('something')
    return variable
```
