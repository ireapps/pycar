```
.-,--.      ,--.     ,.  .-,--.
 '|__/ . . | `-'    / |   `|__/
 ,|    | | |   .   /~~|-. )| \ 
 `'    `-| `--'  ,'   `-' `'  `
        /|
       `-'
```

# Python mini bootcamp

In this two-day workshop, we'll learn the basics of the Python programming language and how to begin analyzing data in a Jupyter Notebook. What's a Notebook? It's an interactive coding environment that lets you blend words and code.

Confused? Of course.

Bear with us. It will all make sense soon.

> Instructors, check out the [Teacher's Guide](teachers_guide.md).

## Day 1

### Intros

* Who are you, what do you do, what do you want to learn?
* What will we learn?
* What can I do with it?
* GOAL: Learn how to solve problems with code.

### [The Basics](basics/README.md)
Key concepts of programming in Python:

- Basic data types - strings, integers, lists
- Lists are your friend!
- etc

> Bonus: a [discussion on debugging][] and handy [cheatsheet](debug/DebugginginPython.pdf)

[discussion on debugging]: https://docs.google.com/presentation/d/e/2PACX-1vTCwzQnH0Ps8xmqnxGBYayCyas8-53qJyo-yjIy5qy4P2xUOA-kiAOQCNTiCzRBVX7TxeBabx1pvpBQ/pub?start=false&loop=false&delayms=3000

## Day 2

### [Project #1](project1/README.md)

As with many data analyses, it all starts with a CSV. After a white board exercise, we'll start with a file of pseudocode, and we'll walk through writing the program in Python code, running each line in the Jupyter interpreter. We'll hold your hand through each step of the process.

### [Project #2](/project2/README.md)

> This project is out-of-date. We'll try to update it in the near future.

This section covers gathering data from the web in two common formats.

In the first part, we'll scrape structured data from an HTML page using a GET request and write the data to a CSV. In the second part, we'll request data from an API to get information programmatically to create a spreadsheet. Our data comes in a new format: JSON. We'll do some more with the white board to show how it's basically a combination of data structures we already know about: Lists and dictionaries (arrays and objects).

### [Project #3](project3/analyzing_data_with_pandas_notebook.ipynb)

Now we get to the heart of data analysis with an introduction to the powerful [pandas](https://pandas.pydata.org/docs/index.html) library. Building on the basics we've already learned, and a little knowledge of [SQL](https://en.wikipedia.org/wiki/SQL), we'll clean two related tables of data, join and filter them.

At the end of the day, we'll __[send you home with](takehome/README.md)__:

* A [lightning dash](takehome/PyCAR_basics_takehome_notebook_complete.ipynb) through basic variables, types and functions
* The [working, commented code](completed/) for each project from our git repo
* A walkthrough for [setting up your machine at home with Python](https://github.com/thejqs/pycar/blob/master/takehome/Installing%20Python%20The%20IRE%20Way%E2%84%A2.pdf), version control and virtualenvs
* Good libraries to explore with strong tutorials
* A lifetime support guarantee [from us](CONTRIBUTORS.md) & [PythonJournos](https://groups.google.com/forum/#!forum/PythonJournos)

## Help!

If you're working through this code at home and have trouble, please let us know.

The best way to reach us is by [submitting an Issue](https://github.com/ireapps/pycar/issues?q=is%3Aopen+is%3Aissue) on GitHub.