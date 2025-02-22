Now, the first thing we're going to do is to perform a version check using this command in the command

line; node -v, go ahead and open up Visual Studio code and open up a new window.

Now, in this new window, you won't have any files, you won't have anything else,

but that's not important.

We're going to go to View and we're going to open up the Terminal.

Now, another way to get to this is actually to hover down right to the bottom until you see this little

arrow pop up

and if you click and drag it up, you'll also be able to open up the Terminal.

I'm going to get rid of anything that I don't need.

And inside my terminal, I'm going to write that command, node -v to check the version of Node and hopefully

you're on the same version as me,

if you've completed all of the installation steps correctly.

Now, if you don't see the same version, it might be because you are on a more recent version, so

maybe the number is higher.

Alternatively, maybe you've installed Node in the past and you've got a lower version for some reason

or other.

Have a look at the text and the FAQs in the last lesson where we did the installation and you'll find

some instructions on how to fix this.

But hopefully, when you check your Node version, you should see a version number show up, starting

with a v and it should be 18 or higher.

So 19, 20, whatever it may be.

Now that we've made sure that we've got the right version of Node, the next thing to learn to use is

the Node REPL.

So REPL stands for Read Eval Print Loop

and this is not unique to Node.

It's something that we can do with most programming languages and it's basically an environment like

the node runtime environment where we can put in user inputs in the form of code,

and what we write is read by the computer and evaluated line by line, and then it prints out the result

back to us in the command line or in the console. And to initiate the node

REPL, all we have to do is to type the command "node". Going back to our Visual Studio window, let's go

ahead and type the node command. Here

it should tell you, "Welcome to Node.js" and you should see this little arrow here (>) which tells you that

you have successfully entered the Node REPL. Now in the Node REPL what we're going to do is we can type

some commands such as the ".help" that they've already told you about and this gives you some of the other

commands that you can use.

For example, .break, .clear, .editor etcetera.

But the most important one, because very often the hardest thing with REPLs is how to exit them,

we can use the ".exit" to get out of this and you can see we no longer have that little arrow sign

showing up anymore.

That's ended.

Alternatively, you can simply type Ctrl+C and then Ctrl+C again in order to exit.

Now, Ctrl+C is usually the way to get out of anything in the command line.

So in the future, even if you see some sort of process running and you're not getting your usual command

line interface, just try Ctrl+C a few times and that should hopefully get you out of trouble.

Now let's go back into the Node REPL and I'm just going to raise this window up a little bit because

I know that very often the subtitle goes at the bottom and it can be hard for students to read what

I'm writing.

All right, so inside our Node REPL, let's try to do a Read Eval Print Loop. Let's write some code.

Let's do something really simple like 5+8, hit Enter and you can see it's read my code,

it's evaluated it and then it's printed it out.

So Read, Evaluate, Print, Loop done.

Now remember that Node is a JavaScript runtime, so you can write anything that is JavaScript.

So let a = 3, and then a + 12 will work just as you would expect.

Have a play around with the Node REPL and hopefully by the end, you'll see that this is really similar

to what you've been able to do using the JavaScript console in the browser.

But in this case we've just taken it out of the browser and we're using Node to enable us to run that

JavaScript code.

Now the final thing I want to show you in terms of using Node.js is how we can write a JavaScript file

and use Node to run the entire file.

Because as useful as a REPL is in the command line, what we actually need to do is to write full

code files and to use Node as the runtime environment.

So head over to the course resources in this lesson and hopefully you'll see a zipped file there called

2.1 Using Node,

and I want you to download and extract that file and open that folder inside VS Code.

If you don't know how to access the course resources or how to unzip and actually get hold of the file

and make it work,

and if you've just skipped to this section, make sure you take a look at one of the earliest lessons

in the course right at the beginning in Section 1, where we talk about, "How to get hold of the course

resources," it's really important.

And if anything doesn't work in the next steps, be sure to review that.

All right.

But hopefully you've got this working and you can see in here all there is, is just a blank index.js

file.

But what's important is our folder structure.

I want to show you how we can write code into this code file.

I'm just going to write console.log(

"Hello from Node"); and that's all we got.

Let's hit Save and let's open up our terminal.

And the first thing I want to do is to navigate to that folder.

So remember, we can use cd to change directory.

And the directory I want to get hold of is the one that contains this index.js file.

So I'm going to drag that folder, 2.1 Using Node, and then hit Enter in order to navigate into

that folder in the command line.

Now that I'm here, I can use the node command and instead of just writing node where we enter the REPL,

I'm going to type in the name of my file,

and one of the things that a lot of developers do when they are trying to access different files etcetera,

is you can actually just type the first few words, hit the Tab key on your keyboard and it should autofill

the rest of the file name.

On one hand, this is really great because you didn't have to type out the rest of the file name, but

on the other hand, it's also a sense check for figuring out whether if you're in the right directory,

because if I went up one level and I did the "node index..." and you can see even if I keep hitting tab,

nothing happens.

There isn't a file called that in this directory.

So let's go back into the folder that we want to be in and then go ahead and use node, and then add the

name of the file we want to run, hit Enter, and you can see that Node has found this file, used the

Node runtime to run the code inside Index.js,

and here we see the outcome, which is exactly what we would expect.

There you have it.

Hopefully this has worked just as well for you.

And if you want some extra practice, I recommend creating another JavaScript file inside the same folder

and write some code in there and use node to run that file just so you can have practice using node.

But in the next lesson, we're going to move on to look at some of the native node modules and see how

we can leverage them in order to add more power to our node applications.
