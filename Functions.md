[[Python]]

I am Pragnyan Ramtha, and this is my team. Today, we are going to be explaining arguably the most important concept in Python. However, before we begin, I want to show you a short yet popular video from a professor from the Clay Mathematical Institute.

**Video** - FUNCTIONS DESCRIBE THE WORLD

Truly incredible spirit by Mr. Thomas, and as you might have guessed, we are going to be explaining functions today.

But what is even a function?
What is it used for?
Why does it exist? Isn't it more clear to rewrite the whole code?

Well, these were some of the first questions that crossed my mind when I first learned about functions, and these are indeed some of the questions that even others ask themselves when first learning about functions.
So, to understand these doubts, we must indeed go all the way back to the time I or anyone was learning to code.

So I want you all to remember the first line of code that most of us have written.

And in most scenarios, I bet it is this line:

```python
print("Hello, world")
```

with the output,

```
Hello, World
```

Well, now let's take a step back and consider what it is that we actually just did and what it is we're looking at here on the screen.

Well, first and foremost, in almost any programming language, we tend to have access to something known as functions.

And a function is something like an action or verb that lets you do something in the program. Generally speaking, every language comes with a predetermined set of functions, known as the standard library, aka the things that the computer already knows how to do for you.

That the language, really, will know how to do for you. And you, the programmer, the developer, the human, can use those functions at will to get the computer to do those things.

Now, the program in question here is using one function.

That function is, of course, going to be this function `print`, and that `print` function, of course, doesn't print some preordained string of text. That is to say, it prints whatever it is you want it to print.

And here too, we have another piece of terminology in the world of programming, namely arguments.

An argument is an input to a function that somehow influences its behavior.

The people who invented Python, of course, didn't necessarily know what it is you and I are going to want to print to the screen, so they designed this `print` function using these parentheses with the ability to take as input some string of text.

And what is it that the program is ultimately doing on the screen? Well, it's printing, of course. It's showing us "hello, world" on the screen.

And functions, unlike in mathematics, can indeed have these side effects. One of the things they can do is to display on the screen as a side effect, something like those words that we wanted—"hello, world."

---

Let's go about improving this program to make it a little more interactive and not just assume that everyone is going to want to be greeted more generically as "hello, world." Let's see if I can't get this program to say something like "Hello, David" or "Hello, Jeremiah" or "Hello, Horatio" or whatever the actual user's name is.

Well, to do this, I'm going to go back up to `hello.py` and I'm going to add another line of code at the very top that simply says, for instance, "What's your name?" with an extra space at the end.

So I'm printing to the user, asking them a question for some input, but now I need another function to actually get input from the user.

And, perfectly enough, Python comes with a function named `input`. So here, I'm going to go ahead and call a function `input()`. And that's going to prompt the user with just a blinking cursor waiting for them to type something in.