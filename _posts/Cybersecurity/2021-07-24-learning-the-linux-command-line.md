---
title: Learn The Linux Command Line Fundamentals, Part 1
categories:
- Linux 🐧
feature_image: "https://picsum.photos/2560/600?image=872"
---

In case you don’t know what linux is, it is one of the most used operating systems around the world. Linux is trusted by many big companies to run their servers. Linux is free, open-source, and most importantly secure. Hence why people run their servers with linux. The aim of me writing this it to teach people and give them an idea about what it is like to get into cybersecurity and maybe even inspire people. It’s to make a difference in someone’s life. That’s my main goal. Since there is no way for me to talk about all of the room in this single post, I will split it up into parts. That way we can digest the information better.

Today I’ll be learning about the linux command line, and since it’s impossible to learn everything in one day, I will only be focusing on the fundamentals of it. I didn’t want to do this alone, so I thought it would be a good idea to share this journey with you. I will be learning most cybersecurity skills from hackthebox academy so go check them out, they offer a free plan to their website: https://academy.hackthebox.eu/. After you’ve signed up navigate to the sidebar and click on ‘modules’ then ‘all modules’ you will find the linux fundamentals room near the top, it costs 10 cubes but you already have 30, and if you finish the room it will give you the 10 back. So it’s basically for free!

File system

Something I never knew was the everything in the linux operating system is stored in a file no matter what it is. Including your passwords. Linux itself isn’t an operating system, rather its the kernel of many different flavours of linux, such as parrot, ubuntu, kali, etc. I’m sure you all have heard these somewhere. If not, now you know, I taught you something new.

![Linux File System](/images/Linuxfilesystem.png)

I do not own this image, this is from hackthebox academy linux fundamentals.
The linux file system is structured in a way that looks like a tree, the top level is the ‘/’ directory. It is called the root file system, which makes sense. The rest of the folders that you see in the image above are also important and contain important files that run the operating system. For example, ‘/bin’ contains the command binaries. If you open terminal and run ‘ls’ it will list everything inside the current directory, ‘ls’ is stored inside ‘/bin’ the same applies for the rest of the commands. If you signed up you should see what all the paths in the image above do. In case you didn’t, here they are. Put in mind that i’m also learning.

![Linux Folders](/images/Linuxfolders.png)

I do not own this image, this is from hackthebox academy linux fundamentals
Terminal Emulators

A linux terminal can also be called a shell or command line, I knew about command line but never about shell. The terminal doesn’t have a fancy GUI because it only provides text-based input/output. For short we can say (I/O). This communication happens between the user and the kernel, aka the system. Terminal emulators also exist, they are very often used for this. There are many terminal emulators that you can use, XTerm, XFCE4, Terminal, etc.

Shell

The most known shell is called BASH which stands for “Bourne-Again Shell”, it is widely used around the world. But it isn’t the only shell that exists, Tcsh, Csh, Zsh, etc. Recently on macOS they switched from BASH to Zsh. Personally I use a mac as my everyday laptop. And that change affected many people but at the time I wasn’t really into computers and it didn’t affect me that much.

I think that I’m gonna end it here so that I don’t make this too long and boring for you. If you made it to the end I really appreciate that you sticked around and joined me in my journey into learning cybersecurity. Feel free to send me feedback using the form down bellow, and I will try my best to respond as fast as I can. Thank you again, and I’ll see you next time, Bye!

