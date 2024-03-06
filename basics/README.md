# THE BASICS


> Approx. 1 hour, 15 minutes

What is a [number](https://docs.python.org/3/tutorial/introduction.html#numbers)? What is a [string](https://docs.python.org/3/tutorial/introduction.html#strings)? What is a [list](https://docs.python.org/3/tutorial/introduction.html#lists)?

Nevermind that, what's a [Python](https://docs.python.org/3/)?

Before we get started with learning programming concepts, let's take a step back and get a high-level overview of what programming even is.

Programming is not mystical, magical or special. Programming is more of a craft than an art. It’s more like learning how to build cabinetry than it is learning how to watercolor. There’s nothing glamorous in it, and you should be suspicious of anyone who tries to tell you otherwise.

You already know the components of programming. You have been exercising the reasoning programming relies on for your entire life, probably without even realizing it. Programming is just a way to take the logic you already use on a daily basis and express it in a way a computer can understand and act upon.

Card games and games like tic-tac-toe are classic programming tests because they require you to encapsulate the way you reason about those games in a way a computer can understand. So we'll use a card game, solitaire, to talk about some basic programming concepts over in the [basics_notebook.ipynb](basics_notebook.ipynb). Head over there, and then come back here for some reference.

## About Python

Python is a programming language. It was created around 1991 by an individual named [Guido van Rossum](https://en.wikipedia.org/wiki/Guido_van_Rossum).

You may hear others call Python a [scripting language](https://en.wikipedia.org/wiki/Scripting_language). You may also hear it called an ["interpreted"](https://en.wikipedia.org/wiki/Interpreter_(computing)) language. In essence, these are interchangeable terms. In Python you write programs that are interpreted line by line. These programs - or scripts - automate tasks that would otherwise be completed one by one.

The Python interpreter can be accessed through the command line (terminal, shell, etc). On Unix-based (Mac OS) or Linux machines, which come with Python installed by default, you enter the Python interpreter by typing ```python``` followed by the return key. On a Windows machine, things are a bit more cumbersome.

One feature of Python that takes some getting used to is its use of indentation to organize blocks of code. One way to remember this is to think of creating an outline. You have main bullet points and you might have an item indented beneath that relates to something above it. In essence, this is Python.

       the python interpreter reads this line first and takes action
           and then reads this line and takes action
               and so on and so forth
       and then you can jump back out if you'd like

Before we get started, this is meant to be an overview of Python and show you some of the things you can do with it in a newsroom context. If you find it useful we hope you continue to practice and become better. It's like Zed Shaw wrote in the intro to [Learn Python the Hard Way](http://learnpythonthehardway.org/book/index.html):

> While you are studying programming, I'm studying how to play guitar. I practice it every day for at least two hours a day. I play scales, chords, and arpeggios for an hour and then learn music theory, ear training, songs, and anything else I can. Some days I study guitar and music for eight hours because I feel like it and it's fun. To me repetitive practice is natural and just how to learn something. I know that to get good at anything you have to practice every day, even if I suck that day (which is often) or it's difficult. Keep trying and eventually it'll be easier and fun.

Anyways, let's get started by looking at some key components of any programming language - numbers, text, comparisons and variables.

All of the following is contained within the [official Python tutorial](https://docs.python.org/3/tutorial/introduction.html#).

We'll work on the below exercises in [basics_reference_notebook.ipynb](basics_reference_notebook.ipynb).

> Solutions to the exercises can be found in 
[completed/basics_reference_completed.ipynb]([../completed/basics_reference_completed.ipynb]).

## Side note: Comments

Throughout the day you will see - and hear us refer to - something called comments. We're not referring to that wasteland of negativity that you find at the bottom of articles on news websites. But just the same, ideally these comments are meant to be constructive.

* Comments are annotations; a method for programmers to offer notes, advice or justification for why the did something in a script.

Python has a couple ways to comment code:

One is to use the pound symbol, aka hashtag or [octothorp](https://en.wikipedia.org/wiki/Number_sign). Here's an example:

```
# this part of the code is where I make the magic happen
```

Another method for multiline comments is to use a series of three quote marks or three apostrophes.

```
"""
this is a multiline comment
so i can pack more information
about what i'm doing
"""
```

## Variables

* A variable is a named container for a value.

* A backbone of any programming language

* Variables have a scope

* Variables have a value

    * Can be None

    * Can be True or False

    * Or it could be something else... a number or a string

* When declaring the value of for a variable in Python the format is 'variable = value'

    * ```my_variable = "the value of my variable"```

## Text

[Text](https://docs.python.org/3/tutorial/introduction.html#text) (or more formally in Python, "strings").

* Generally, synonymous with characters.

* You can use double quotes or single quotes to create strings

* If using single quotes, apostrophes and single quotes within string must be escaped

* Learning about strings

    * double quotes vs. single quotes

            # double quotes
            double_quotes_string = "We're going to learn Python at #NICAR16"
            print double_quotes_string

            # single quotes
            single_quotes_string = 'We\'re going to learn Python at #NICAR16'
            print single_quotes_string

    * get its type

    * get its length

    * [lowercase](https://docs.python.org/3/library/stdtypes.html?highlight=strip#str.lower)

    * [uppercase](https://docs.python.org/3/library/stdtypes.html?highlight=strip#str.upper)

    * [titlecase](https://docs.python.org/3/library/stdtypes.html?highlight=strip#str.title)

    * [split](https://docs.python.org/3/library/stdtypes.html?highlight=strip#str.split)

    * join

    * [replace a character](https://docs.python.org/3/library/stdtypes.html?highlight=strip#str.replace)

    * strip whitespace

        * [all](https://docs.python.org/3/library/stdtypes.html?highlight=strip#str.strip)

        * [leading whitespace](https://docs.python.org/3/library/stdtypes.html?highlight=strip#str.lstrip)

        * [trailing whitespace](https://docs.python.org/3/library/stdtypes.html?highlight=strip#str.rstrip)

## Numbers
    
[Numbers](https://docs.python.org/3/tutorial/introduction.html#numbers)

* Whole numbers have a type and that type is integer

* Fractions have a type and that type is float

* Learning about numbers

    * get the [type](https://docs.python.org/3/library/functions.html#type)

    * addition

    * subtraction

    * multiplication

    * division

    * order of operations

        * used when we want to determine percent change right?
            ```
            (new - old) / old
            ```

## Lists

[Lists](https://docs.python.org/3/tutorial/introduction.html#lists)

* We learned that integers and strings are data types

    * Python has specific types that allow you to group items. The list is one of these collections.

        *  A list is sortable and a list has an index

            *  Index starts at 0

        * You can add and remove content

            * You can add and remove items from specific indexes

        * Lists might contain items of different types, but usually the items all have the same type.

    * append() allows you to add items to a list

    * pop() returns the element you want to remove. Useful to remove and keep an item from a list

        * By default, pop without any arguments removes the last item

    * del deletes the item at the specified index

## Dicts

TK


## Indentation

As mentioned in the introduction, Python uses indentation to structure "blocks" of code instead of braces, brackets, or keywords. For example:

```python
    if user_input is None:
        output = "I have nothing"
    else:
        output = "I have something"
```

* Lines are indented by four spaces.


## Conditionals & Comparisons

### Conditional statements

* "[A conditional statement](https://en.wikipedia.org/wiki/Conditional_(computer_programming)), conditional expressions and conditional constructs are features of a programming language which perform different computations or actions depending on whether a programmer-specified boolean condition evaluates to true or false."

    * [for](https://docs.python.org/3/tutorial/controlflow.html#for-statements)

        * The ```for``` statement iterates through a list or a string in the order they appear.
            ```python
            my_list = [1, 2, 3, 4, 5, 6]
            for x in my_list:
                print x
            ```

    * [if / elif / else](https://docs.python.org/3/tutorial/controlflow.html#if-statements)

        * The `for` statement iterates through a list or a string in the order they appear.

                value = 4
                if 4 == value:
                    print "it's the same"
                else:
                    print "it's not the same"

### Comparisons

[Comparisons (python docs)](https://docs.python.org/3/library/stdtypes.html#comparisons)

* equals (`==`)

    * are two values the same?

* not equals (`!=`)

    * are two values different?

* greater than (`>`)

    * is value larger than the other?

* greater than equal to (`>=`)

    * is value larger or equal to the other?

* less than (`<`)

    * is value smaller than the other?

* less than equal to (`<=`)

    * is value smaller or equal to the other?

* `is`

    * Are two items the exact same thing?

* `is not`

    * Are two items not the exact same thing?
