# Your first program

Now after all the installation step, we are now ready for our first program.

To check if your Java is properly installed, run this command, no matter if you're using Windows or Linux.

	$ java -version

If it shows your Java versions, it works properly. If not, mostly because you have not set up the $PATH.

# Writing Code

Open up your Notepad or any of your favorite editor. We will type in our first code, and I will explain later.

Seeing the code runs is always better than seeing explaination!

`HelloWorld.java`

	class HelloWorld {
	
	public static void main(String[] args) {

			System.out.println(“Hello World!”); // Display the string.

		}

	}

Save it, remember, save it as `HelloWorld.java`, not as `HelloWorld.java.txt`, you can change that using Save As option.

# Compiling

Remember, computer is fast, but dumb. After writing our code, we need to compile it, so that it can be converted into **bytecodes**, not those binary. We will learn more later.

So how do we do that? Open up your terminal or command prompt, and run this:

	$ javac HelloWorld.java

JavaC is for Java Compile, and it is pronounced as **Java See**, not **Javak**.

What it does? It simple compile your code, and if you check your directory, you will see a new `HelloWorld.class` file. Don't bother to open it, as it contains `bytecode` you won't even understand.

# Done, how to run?

Simply type in:

	$ java HelloWorld

You can see that `Hello World` is printed out!

Fun right? Let's get into more coding, explaination later, I promise!
