# Literally Upload

Ok, I've been talking a lot about uploading. From now, you NEED to understand this, and this is important.

>Your GIT project is done in 2 places.
>
> 1. Online(Remote)
> 2. Local(your computer)

Yep, what we have done so far is make a local git repository. How to make it online, or specifically, how do we 'push' it online?

# Use Bitbucket/Github to make online repository

Simple, head over to the website, and create a repository, they make it clear with a link to create repository.

Let's say you name your directory in the Bitbucket/Github as `HelloWorld`. After creating the directory, you will see they gave you a link. 

>Remember, git is blind, they need to know where to upload

It looks something like this : https://Xavier-IV@bitbucket.org/Xavier-IV/YourProjectName.git

Of course, Xavier will be replaced with your username you registered with the provider.

>Tell git your new online home address!

Now, to tell our git "Hey, I have create an online home for you. Let's take note of the address!"

	$ git remote add origin https://Xavier-IV@bitbucket.org/Xavier-IV/YourProjectName.git


Cool, our git project has now an online home! BUT, we have not move in our furniture yet!

# Move In The Furniture

Your furniture is all your codes and projects file, it is now inside a `local` home. To move the things to their `Remote(online)` home, we do it like this.

>You can check out your File inside the Bitbucket/Github that they have not uploaded it yet. The magic will begin soon!

	$ git push origin master --force

If it asks for password and username, just give in the password and username that you use to register with `Github/Bitbucket`.

>Why use --force? Well because this is our first push, Github/Bitbucket sometimes create a file in the Remote directory. We don't want that, this is the same as saying "Hey, whatever in that new home, throw it out. We rule now!"

Yep, that's it. After the uploading is complete, check out your Bitbucket/Github again, and see the magic.

Holy Makeroni! Your file is there now!

Fun right? Yep, they are.

# Conclusions

Let's recap again! Recap is fun, to keep you focus.

	1. Know what is local(offline) and remote(online) is
	2. Make a repository inside the Bitbucket/Github
	3. Tell git of his new `online` home
	4. Move the `furniture` online!

That's the basic!
