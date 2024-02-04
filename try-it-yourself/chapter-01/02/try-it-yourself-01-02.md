# Try It Yourself Solution

## 1-2 Hello World Typos

Som tests to see what happens if making typos in the following Python code:

```python
print("Hello Python world!")
```

### No Quotation Marks

Leaving out the `""` around the text:

```python
print(Hello Python world!)
```

Causes:

```txt
SyntaxError: invalid syntax. Perhaps you forgot a comma?
```

Not a very helpful error message.

### No Parentheses

Leaving out the `()` around the text:

```python
print"Hello Python world!"
```

Causes:

```txt
SyntaxError: Missing parentheses in call to 'print'. Did you mean print(...)?
```

A helpful error message.

### Ending Semicolon

Ending the line with a semicolon, which is a common syntax in some other programming languages:

```python
print("Hello Python world!");
```

Will run fine without any errors or warnings and outputs:

```txt
Hello Python world!
```

But remember that the program also runs fine without the semicolon.

### Add Spaces

Adding some spaces between parts:

```python
print ( "Hello Python world!" );
```

Will run fine without any errors or warnings and outputs:

```txt
Hello Python world!
```

Spaces seems to be largely ignored in Python.
