# Make A Project

What will we make? A simple Hello World message inside a notepad, no programming no nothing. Simple plain notepad/gedit project, to save you from confussion!

Let's make a folder called "HelloWorld".

Open up your terminal/command prompt inside it, and type in this magic word:

	$ git init 

What does it do? Well, it simply initiate your folder!


# Git Is Blind!

Yes, they are blind! Consider Git is a way to upload your code online, and manage it. Well, it needs to know what you want to 'upload'.

So how do we tell git what to upload? Using the charming `git add` command:

	$ git add yourfile.ext

For real example, create a file called "helloworld.txt" and put anything inside it, like your favorite lecturer that you have a crush on or your place where you hide your exam results. Anyway, once done, let's make git a little bit less blind.


	$ git add helloworld.txt

Consider you have other .txt file, you can add all of them using wildcard `*.txt`.

# People Need to Know

People need to know what your project is about, to do so, you can set up `README.md` file, you will see why later. It uses markdown syntax, but that is easy to learn. Inside it, put these lines:

`README.md`

	# About HelloWorld
	Heyya, we are just starting out!

		This is fun!
	
	`This is some message`
	**This is bold**
	*This is emphasized*

Make sure you copy the whole line, and paste it into `README.md`.

Remember, git is blind. We will want to upload it. So tell this fella, "Hey, I made an awesome README file, be sure to put it online later!"

	$ git add README.md

# Commit!

Hey, that's a new term, no fair! But it's ok, it is our way to tell git, "Hey sexy, we have add up our files, we are commit to upload it!"

	$ git commit -m "Initial commit honey"

Well, of course you need to commit with professional 'message'. That -m is an option for telling git what we want to say about our commit! Simple.


# What we did?

All is confusing? Just read slowly friend, and let's recap.

	1. We `init` our directory
	2. Git is blind, we `add` our files
	3. Tell people about our project with `README.md`
	4. `Commit` what we add

	
Want to hear some fun fact? Git and Github is 2 different things.
Ready for more facts? You have learned 50 percent of the whole git thingy!

Fresh in mind? Cool! Let's head to the next lesson!
