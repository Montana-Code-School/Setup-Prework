# Configuring your setup for Montana Code School

At Montana Code School, we all need to be running similar systems and software to make it easier for us all to share and communicate.

Here is a list of what we support here at the code school:

* macOS or Linux operating system
* Google Chrome
* Atom text editor

This walkthrough is meant to help you set up your machine for the code school, and get you more comfortable with making changes.

## Before you start

**Make sure you backup all of your data**

One of the first myths we need to dispel is that computers are fragile. As a programmer, you will be installing and configuring a lot of software, and some of these can cause issues with other software. Someday you **will** lose data, so you have to get in the habit of making backups periodically.

I would recommend keeping a hard drive around, or subscribing to a service like Dropbox to store your data.

Here is what I use to protect my data:

[Seagate Backup 1TB](https://www.amazon.com/Seagate-Backup-Portable-External-STDR1000100/dp/B00H4XH5FY)

[Dropbox Plus](https://www.dropbox.com/upgrade)

## WINDOWS?

**If you are running a Windows machine**, we will need to get you set up with another operating system, Ubuntu. Don't panic, let's set up your computer in a way that allows for both Windows and Ubuntu to run.

## Setting up a dual-boot machine (Ubuntu and Windows)

Begin by looking at the walkthrough here:

https://www.lifewire.com/ultimate-windows-8-1-ubuntu-dual-boot-guide-2200654

If you are running a Windows machine, your first challenge is going to be setting up another operating system for you to do your programming in. Windows is fine for many programmers, but many of the programs and languages that we will be using are used much more effectively with a Linux based operating system (or macOS, which is similar).

For this we will be setting up what is called a *dual-boot*. This will essentially install two operating systems on your computer, allowing you to switch between them whenever you start up your computer.

If you already backed up your data, you have nothing to worry about. Follow the walkthrough slowly, and make sure you pay special attention to the hard drive partition section.

Once this is finished, you will now be able to boot up your computer in either Windows, or in Ubuntu. Congrats!

**NOTE:** You might read about the option of setting up something called a virtual machine. Don't. Running Ubuntu from a virtual machine will only cause you problems down the line.

## Setting up your machine

As you begin programming, your computer is going to get cluttered *fast*. It's important for you to clean up your machine before class begins to minimize frustration.

At the code school, *all you really need to get started is a text-editor and a browser*. 

### Install software

We will be using Google Chrome for this class. It is fast, has great debugging tools, and establishes a standard for all of us to work with.

[Download Chrome](https://www.google.com/chrome/browser/desktop/index.html)

Now, programming is just a bunch of text editing. We use the Atom text editor. It is highly customizable and really well made.

[Download Atom](https://atom.io/)

### Remove things from your desktop

They don't need to be on your desktop, put them in a folder inside of your documents folder. This is mostly just a strongly held pet-peeve of mine.

### Uninstall unnecessary software

Clear up space and reduce clutter.

### Set up a place for your code

We will try to limit our programming within one folder, our "code" folder. We will also learn our first terminal commands in the process. Let's set that up.

* Open up Terminal
  * In the linux environment use the search bar to find the terminal
   ![linux shell search](http://linuxbsdos.com/wp-content/uploads/2012/09/Shell.png)
  * in OSX use Spotlight
   ![spotlight mac](https://support.apple.com/library/APPLE/APPLECARE_ALLGEOS/Product_Help/en_US/PUBLIC_USERS/135122/S0071_SpotlightMenu.png)
* The next commands will all be run from the Command Line, the space after the `$` is called the prompt
   ![terminal shell](https://www.howtogeek.com/wp-content/uploads/2016/10/xansiweather-mac-terminal.png.pagespeed.gp+jp+jw+pj+ws+js+rj+rp+rw+ri+cp+md.ic.eKbZVGPsfl.png)
* create a new folder: `mkdir ~/code`
* go to the folder: `cd ~/code`
* now create an empty file: `touch emptyFile.js`

Organize all of your code in this folder. If you need to get to the folder within Finder, you can navigate to your user home folder, and the code folder will be within it.

## Finally

At any point during your configuration, or your prework in general, please don't hesitate to get ahold of your instructor, either over email or Slack.
