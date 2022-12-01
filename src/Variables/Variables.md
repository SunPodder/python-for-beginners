# Variables

Variables are **containers for storing data**. If you have ever done some basic algebras you might be familiar with the concept of variables.

When you create a new variable and assign it a value in your code, the language allocates some memory in your device and stores its value there.

Don't worry if you didn't understand it. We won't go that deep. Just remember that **variables stores some sort of data** which might be a text, a number or even another variable.


## Creating Variables

In programming, variables are often used to store some data for later use.

```python
msg = "Hello World"
```
In the above code, we created a variable named `msg` and assigned it a value of `Hello World`. Later we can reference it in our code like so
```python
print(msg)
```
This code will print `Hello World` to the screen.

### Explanation

This time we are giving `print()` the `msg` variable instead of a plain text. The `print` function will receive the variable named `msg`, read its value from the memory and prints that to our screen.

**⁉️ But how do it know if we are giving it a variable or a plain text to print?**

That's where the quotes `""` comes in. Quotes differentiate plain text from variables or other texts which are not simply plain text.

Anything inside the quotes are treated as plain texts. In programming, we call it **String**. We will learn more about **Strings** latrer.

---


You can also perform various operations with variables. Like arithmetic operations
```python
a = 1
b = 3

c = a + b

print(c)
```
The above code prints 4. Feel free to change the values to other numbers and play around them.

>💡**PRO Tip:** The best way to learn programming is to play around with others' code and figure out how they work.

