# Getting Started

It's time to write our first python program.

You can use any text editor to write your python code. I recommend using [Visual Studio Code](https://code.visualstudio.com/) with the [Python Extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python) for writing python code.

You can also try **NeoVim** with the [coc.nvim](https://github.com/neoclide/coc.nvim) and [PyRight](https://github.com/fannheyward/coc-pyright) plugin which I will be using throughout this tutorial.


## Hello World

Let's write our first python program. Open up your favorite text editor and create a new file named `hello.py` and write the following code in it:

```python
print("Hello World")
```

Now save the file and run it from your terminal with:
```bash
$ python3 hello.py
```

You should see the following output:
```
Hello World
```

Interesting, right? Let's break down the code.

In the above code we are asking python to print the text `Hello World` to the terminal.

In python, we use the `print()` function to print something to the terminal. And whatever you put inside the parentheses, will be printed to the terminal.

Notice that the text is wraped inside double quotes `""`. It's necessary to wrap normal texts inside quotes.

However, if you want to print a number, you don't need to wrap it inside quotes. For example:
```python
print(1)
```
Running the above code will print `1` to the terminal.


## Excercise

Write a program that prints your name to the terminal.

