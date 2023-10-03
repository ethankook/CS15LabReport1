[cd #1,2,3](https://github.com/ethankook/cse15l-lab-reports/blob/main/Screenshot%202023-10-03%20at%2011.13.56%20AM.png)
1. The working directory is the home directory. 'cd' switches the current working directory, and because there was no argument, there was no output or change in directory. This is not an error.
2. The working directory is still the home directory. There was no ouput because the 'cd' command only changes the directory, and this time, a proper argument was given. This is not an error.
3. The working directory is lecture1. The output shown in the screenshot was due to the fact that the argument used for the 'cd' command was a text file, not a directory. This is not an error.

[ls #1,2,3](https://github.com/ethankook/cse15l-lab-reports/blob/main/Screenshot%202023-10-03%20at%2011.22.17%20AM.png)
1. The working directory is the home directory. Because the 'ls' command displays the files and folders in the given path and no argument was given, the output is the only available folder in the home directory, which was lecture1. This is not an error. 
2. The working directory is still the home directory. The 'ls' command displays the files and folders in the given path, which was the lecture1 directory, so the outputs, Hello.class, Hello.java, messages, and README were all files/ folders in the lecture1 directory. This is not an error.
3. The working directory is still the home directory, because the 'ls' command does not change it. The output shows the path given in the argument because it is a file, and there are no other files or folders in the path. I believe that the output *is* and error because it should say that there are no files or folders in the given path.

[cat #1](https://github.com/ethankook/cse15l-lab-reports/blob/main/Screenshot%202023-10-03%20at%2011.26.53%20AM.png)

[cat #2,3](https://github.com/ethankook/cse15l-lab-reports/blob/main/Screenshot%202023-10-03%20at%2011.27.02%20AM.png)
1. The working directory is the home directory. Because the 'cat' command prints the contents of the files given by the path, and an argument was not given, there is no output and it waits for an argument to be given. I believe that the output *is* an error because rather than waiting for an argument, it should just return an error message. 
2. The working directory is still the home directory. As the 'cat' command prints the contents of the files given by the path, and the argument given was the directory lecture1, the output message "cat: lecture1/: Is a directory" explains that a file path must be given rather than a directory. It is not an error.
3. The working directory is still the home directory, as the 'cat' command does not change the path. The output, "Hello World!" is simply printing the contents of the file given by the path, which was lecture1/messages/en-us.txt in this case. This is not an error.
