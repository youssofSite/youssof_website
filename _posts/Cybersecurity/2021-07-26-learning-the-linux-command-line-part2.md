---
title: Learn The Linux Command Line Fundamentals, Part 2
categories:
- Linux
feature_image: "https://picsum.photos/2560/600?image=872"
---

Thankfully, the bash prompt comes with some usefull information. Such as the current directory, computer name, and user name. It makes navigating your system a lot easier and quicker. You can even go on and customize what your prompt includes. Personally I leave it as it is, but you may want to change it, if you decide you do, this website can help http://bashrcgenerator.com/ Also, just to let you know, I'm using macOS which has zsh as the main shell for the terminal. 

If you ever find a command that you want to start using, it would be a good idea to get a understanding of what that command actually does. Believe me, it will make your life a whole lot easier. You can do that in either two ways, using the man pages or the help functions.

Syntax:

`user@machine-name ~ % man <tool>`

Example: 

`user@machine-name ~ % man ls`

The example showed above was done in a macOS terminal. It will look very similar on any other unix based operating system.
The output should be a long file that contains many useful information on how to better use the 'ls' command, which if you don't know basically lists everything in your current directory. You can also use the help functions.

Syntax:

`user@machine-name ~ % <tool> --help`

Example:

`user@machine-name ~ % curl --help`

Tip: -h will also work

'apropos' is another command that could make getting startes a lot easier and more enjoyable, it searches the descriptions in man pages for when a given word is mentioned.

Syntax: 

`user@machine-name ~ % apropos <keyword>`

Example:

`user@machine-name ~ % apropos nano`

Here is another website that is extremely useful when it comes to understanding longer commands is https://explainshell.com/ 
I won't make this any longer so that you don't get bored. If you made it to the end I would like to thank you for staying with me this entire time. I hope you learned something new. And I'll see you later in part 3 where we get to start our first linux machine on hack the box academy.