# Orientation

## DO THIS FIRST

For Phase Zero, we'll be using a "virtual machine". This is a "computer within a computer".

Essentially, it means that you download our "machine" to yours, and then when you run it, it's like you have another computer running inside your computer. This is called a virtual machine.

When you're in our virtual Ubuntu, it is *exactly as if* you were on an actual Ubuntu machine. Because you are. It's a full Ubuntu installation. But it runs inside a "sandbox" on your computer, so it can't hurt your computer.

The reasons we use the virtual machine is because it ensures that everyone has exactly the same set up. This makes teaching much, much easier, and that means that we have more time to *teach*, rather than spending a lot of time dealing with frustrating computer issues.

That said, running two computers on one set of hardware does put a little strain on your computer, so if you have a really old computer or one with very little power, then try to borrow a better one for Phase Zero. If you can't borrow one, and despite your best efforts the virtual machine won't run on your computer, then let us know and we'll try to help you get set up otherwise.

## How to set up the box

1. Go to [VirtualBox]() and download and install the correct VirtualBox application for your operating system.
2. Go to [Vagrant]() and download and install the correct Vagrant application for your operating system.
3. From a **terminal**, enter the following line of code to download and run the Phase Zero virtual machine. NOTE: This download will take *hours*, so start it ASAP.

```sh
vagrant init chas/phase-zero; vagrant up --provider virtualbox
```

### Whoa! What is this "terminal" of which you speak?

The terminal is essentially a window directly into your operating system. It runs an application, called a "shell", that let's you talk to the computer directly using typed "shell commands". You'll be using the terminal a lot throughout your career, so the sooner you get comfortable with it, the better.

On a Mac, you can find the terminal in your Applications/Utilities folder. On Ubuntu, type "terminal" in the application search bar to find it. On Windows, it's not as simple. Looks like you want to install the PuTTY application (a tty is a terminal, get it?). You can skim this article for instructions: [Getting Started with Vagrant on Windows](http://www.sitepoint.com/getting-started-vagrant-windows/). You only need to install the PuTTY app and then run the above line of code. Disregard the rest of the tutorial.

**PLEASE LET US KNOW IMMEDIATELY IF YOU ARE HAVING TROUBLE WITH INSTALLING THE VIRTUAL MACHINE**. The good news is that this is probably the most difficult part of the course: installing things. Somehow it never really gets easier.

Now follow the links below (while your virtual box is downloading) to complete the orientation.

## Table of contents

1. [Best practices for success in Phase Zero](/1-best-practices/)
2. [Expectations](/2-expectations/)
3. [Tools you'll need](/3-tools/)
4. [Resources you will use](/4-resources/)
5. [Empathy](/5-empathy/)
6. [Accessibility to persons with disabilities](/6-accessibility/)
