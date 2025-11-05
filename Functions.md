[[Python]]

I am pragnyan ramtha , and this is my team, and today we are going to be explaining arguably the most important concept in python, however before we begin , i want to show you a short yet popular video from a professor from the clay mathematical institute.


**Video** - FUNCTIONS DESCRIBE THE WORLD 

Truly Incredible spirit my Mr. Thomas , and as you might have guessed we are going to be explaining the functions today. 

But what is even a Function ? 
what is it used for ?
why does it exist ? isn't it more clear to rewrite the whole code ?

well these were the some of the first questions that crossed my mind when i first learnt about functions... and these are indeed the some of the questions that even others ask themselves , when first learning about functions, 
So understand about these doubts we must indeed go all the way back to the time i or anyone was learning to code. 

So i want you all to remember the first line of code that most of us have written

And in most scenarios , i bet it is this line 

``` python
print("Hello, world")
```

with the output,
```
Hello, World
```

Well now let's take a step back and consider, what is it that we actually just did and what is it we're looking here on the screen?

well first and foremost on almost any programming language, we tend to have access to something known as functions. 

and a functions is something like an actions or verb that let you do something in the program , and generally speaking every language comes with a predetermined set of functions , known as the standard library , aka the things that the computer already knows how to do for you.  

that the language, really,
will know how to do for you. And you, the programmer, the developer, the human, can use those functions at will to get the computer to do those things.

Now the program in question here, is using one function.

That function is, of course, going to be this function print and that print function, 

of course, and which of course doesn't print some preordained string of text. That is to say, it prints whatever it is you want it to print.

And here too, do we have another piece of terminology in the world of programming, namely arguments.

An argument is an input to a function that somehow influences its behavior.

The people who invented Python, of course, didn't necessarily know what it is you and I are going to want to print to the screen, so they designed this print function using these parentheses with the ability to take as input some string of text.

And what is it that the program is ultimately doing on the screen? Well, it's printing, of course. It's showing us hello, world on the screen.

And that's generally in programming known as a side effect. It can be visual, it can be audio. In this case, it's something that appears on the screen

and functions unlike in mathematics , can indeed have these side effects. One of the things they can do is to display on the screen as a side effect, something like those words that we wanted -- hello, world.

---

Let's go about improving this program to make it a little more interactive and not just assume that everyone is going to want to be greeted

more generically as hello, world. Let's see if I can't get this program to say something like Hello, David or Hello, Jeremiah or Hello, Horatio or whatever the actual user's name is.

Well to do this I'm going to go back up to Hello to pi and I'm going to add another line of code at the very top that simply says,

for instance, what's your name, quote unquote with an extra space at the end.

So I'm printing to the user asking them a question for some input, but now I need another function to actually get input from the user.

And, perfectly, enough Python comes with a function named input. So here I'm going to go ahead and call a function input, open paren,

close paren. And that's going to prompt the user with just a blinking cursor waiting for them to type something in.