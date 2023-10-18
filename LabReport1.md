# Lab Report 1


![`cd` #1,2,3](cd1.png)
1. The working directory is the home directory. The command, `cd`, switches the current working directory, and if no argument is given, returns you to the home directory. Because there was no argument and I was already in the home directory, there was no output or change in directory. This is not an error.
2. The working directory is still the home directory. There was no ouput because the `cd` command only changes the directory, and this time, a proper argument was given. This is not an error.
3. The working directory is `/lecture1`. The output shown in the screenshot was due to the fact that the argument used for the `cd` command was a text file, not a directory. This is not an error.

![`ls` #1,2,3](ls1.png)
1. The working directory is the home directory. Because the `ls` command displays the files and folders in the given path and no argument was given, the output is the only available folder in the home directory, which was lecture1. This is not an error. 
2. The working directory is still the home directory. The `ls` command displays the files and folders in the given path, which was the `/lecture1` directory, so the outputs, Hello.class, Hello.java, messages, and README were all files/ folders in the `/lecture1` directory. This is not an error.
3. The working directory is still the home directory, because the `ls` command does not change it. When using the `ls` command, giving a file as the argument displays information about the file depending on the request options. Because the argument I gave was a file and no extra information was requested, the only path was the output for the file. This is not an error.

![`cat` #1](cat1.png)

![`cat` #2,3](cat2.png)
1. The working directory is the home directory. Because the `cat` command prints the contents of the files given by the path, and an argument was not given, there is no output and it waits for an end-of-file signal to be input. Any other keyboard input will cause `cat` to repeat the input and output it in the terminal. This is not an error.
2. The working directory is still the home directory. As the `cat` command prints the contents of the files given by the path, and the argument given was the directory `/lecture1`, the output message "cat: lecture1/: Is a directory" explains that a file path must be given rather than a directory. It is not an error.
3. The working directory is still the home directory, as the `cat` command does not change the path. The output, "Hello World!" is simply printing the contents of the file given by the path, which was `lecture1/messages/en-us.txt` in this case. This is not an error.
