# Code Formatting
- [Indents](#indents)
- [Spacing](#spacing)
- [Python](#python)
  
## Indents
All code indents/tabs should be 4 spaces in width to improve readability.
 > Hint: You can change the output of your tab key to type 4 spaces.
```java
	for (int i = 0; i < 10; i++) {
	⎵⎵⎵⎵System.out.println(i);
	}
```

## Spacing
All program kewwords (Ex: for, in, while, not, etc.) \
and operators (Ex: +, -, *, /, %, (), <, >, <=, >=, ^, **, etc.) shall be seperated \
by a space.
```cpp
	if⎵(condition)⎵{
	    ...
	}
```
```cpp
	int x = 1⎵+⎵2⎵-⎵3⎵*⎵4⎵/⎵5;
```

#### Outside of Parentheses
The "outside" of a parentheses shall not have a space if it is used as a "calling" operator.
```cpp
	int x = getNumber();
	                 ^ No Space
```
```cpp
	int value = array[0];
	                 ^ No Space
```
But if used for mathmatical grouping, a space shall be insetred between paratheses and mathmatical operator.
```cpp
	int x = (a + b)⎵*⎵(c - d);
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
