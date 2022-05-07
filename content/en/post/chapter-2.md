---
title: "Things to Keep in Mind: LAMP Stacks"
date: 2022-04-26T22:02:30-04:00
draft: true
---


Setting up a LAMP stack can be very intimidating for developers who have never messed around with PHPmyadmin and developing on local servers.

Let's back up a bit, LAMP stands for Linux(the OS), Apache(the server), MySQL(the database) and PHP(the code). LAMP stacks are very popular among the developing world and are used to develop web applications and websites. It's a very reliable framework for many things, such as development on a domain.

I recently stood up a LAMP stack on my Domain and ran into a few issues that caused me way more trouble than it should have. A lot of developing for new developers is code not working and commands from the CLI showing errors for reasons that seem inexplicable and then realizing you didn't use sudo or you're sending commands from root when you were suppose to command from a user you created. If you're like me, you might have installed multiple versions of the same application and your computer gets so confused that it just stops running commands. Hopefully, you don't get to that point. Without further ado, here are a few things to keep in mind when setting up a LAMP stack.

## Sudo if All Else Fails

One of the most important things I learned when setting up my LAMP stack was the value of sudo commands from the CLI. Unfortunately, this one is for the IOS developers. If you develop from a Windows machine, I feel the utmost sympathy for you. There were so many times, where I would type in a command and it would give me errors, type back "sorry" in a very passive aggressive way, or just not give me anything. This was incredibly frustrating for awhile and resulted in my desire to give up developing forever, until I discovered the sudo command. If all else fails, just put sudo in front of your command, type in your passord, and that should work. Although, it might not be the issue everytime so don't rely to heavily on it.

## Make Sure Your Commanding From the Right User

Another issue I ran into was installing PHPmyadmin and the issue was really annoying, but only needed one tiny fix that I wasn't paying attention to. When installing PHPmyadmin, you have to create a user and then command from that user and switch out of root. I was trying to develop in root and not in the user I had created. If you try to develop from root PHPmyadmin will not show up on your domain or where ever you plan to use it.


## Don't Over-Install Out of Frustration

If you install the same applications, databases, servers, etc multiple times that's going to cause more issues. I became very frustrated many times when I would install something and the steps that came after the installation wouldn't work. My first thought was to keep installing the application until the steps worked. In retrospect, it screwed with my process when I moved on with later steps and resulted in a deep search for my installations and a purge of the duplicates.

I hope these tips are helpful. Don't be like me and make sure you read over documents carefully. Happy developing.
