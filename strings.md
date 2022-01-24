Linux strings command is used to return the string characters into files. It primarily focuses on determining the contents of and extracting text from the binary files (non-text file).

It is a complex task for a human to find out text from an executable file. The binary files, such as program files, contain human-readable text. These files are large-sized if we use a cat or less command; it may cause the terminal to hang up.

There can be two types of characters in a file; printable and non-printable. The alphanumeric characters, punctuation, or whitespaces are known as printable characters; except the printable character, all the characters are known as non-printable characters.

In simple words, we can say that it extracts printable characters from files so that other commands can use the strings without non-printable characters.

Here, the question arises why do we put text in executable files? When an application or software is deployed, most developer packages the binary files. But it is good to pack some ASCII text in the binary file. It will be helpful for the users and for the developers to understand more about the executable file.

So, the strings command is useful to determine the contents of non-text files.

How to use it?
Use of strings command is straight forward, just pass the file name as an argument and execute it. Let's understand it with an example.

We have a system file called gyp.el. To extract the string from this file, execute the command as follows:

"strings gyp.el"  
