# Environment Setup

## Missoula Campus Edition

At Montana Code School to make it easier for us all to share and communicate we all need to be running similar systems and software.

This walkthrough is meant to help you set up your machine for the code school, and get you more comfortable with making changes.
*****

## First Steps

### Your Computer

Without a computer coding is difficult.  Let's talk about what you need to start out.

For the sake of simplicity, we have recently transitioned to a mac-only campus. Macs are definitely more expensive, but they ship with a lot of solid starting options for developers which will get you into the code much quicker.  For those interested in a Linux build or god forbid Windows, we can talk, but in the meantime go grab a Mac.

If for some reason you simply cannot run a MacOS, we can talk about other options.  The viability of these options will depend a great deal on you ability to debug your own machine. Setting up a single tricky environment will take time away from your learning and the learning of your fellow students.

If you have questions about what to purchase check the [FAQ](./FAQ.md) or email/Slack/text an Instructor.

### <a name='find_your_terminal'></a>Finding Your Terminal

The terminal is a text-based way to interact with you machine, it can do all the things you do with your mouse and more.

* Search for Terminal in  Spotlight
   ![spotlight mac](https://support.apple.com/library/APPLE/APPLECARE_ALLGEOS/Product_Help/en_US/PUBLIC_USERS/135122/S0071_SpotlightMenu.png)
* The next commands will all be run from the Command Line, the space after the `$` is called the prompt
   ![terminal shell](https://www.howtogeek.com/wp-content/uploads/2016/10/xansiweather-mac-terminal.png.pagespeed.gp+jp+jw+pj+ws+js+rj+rp+rw+ri+cp+md.ic.eKbZVGPsfl.png)

### Before you start your setup

**Make sure you backup all of your data**

One of the first myths we need to dispel is that computers are static, easily breakable interfaces.  We will be redefining this context and during this process your probabilty of making mistakes goes up significantly. As a programmer, you will be installing and configuring a lot of software and working within the command line. Actions taken while in this environment have the potential to cause issues from which it may be difficult to exit cleanly. Getting in the habit of making backups periodically will allow you to mitigate that damage to some extent.

Might be a good idea to keep a hard drive around, or subscribing to a service like Dropbox to store your data.

Here are some backup options:

* [Seagate Backup 1TB](https://www.amazon.com/Seagate-Backup-Portable-External-STDR1000100/dp/B00H4XH5FY)
* [Apple Time Machine](https://support.apple.com/mac-backup/)
* [Apple iCloud](https://support.apple.com/mac-backup/)
* [Dropbox](https://www.dropbox.com/)

All set there?  On to stage two.
*****

## Setting up your machine

As you begin programming, your computer is going to get cluttered *fast*. It's important for you to clean up your machine before class begins to minimize frustration.  If your computer is brand new you may be able to skip this step but good habits can help you down the line:  **So do yourself a favor and give your machine a good cleaning**

A great tool for house cleaning is [CleanMyMac](https://macpaw.com/cleanmymac) by MacPaw.

### The Accounts and Other Noise

Coding is text that eventaully gets turned into binary by a computer.  The bare minimum you will need to code for the web is a browser and a text editor, but we have a few more things that help us along the way.

Set some time aside, this might take a minute.  Put on some good music and lets check some boxes.

1. Upgrade to macOS Mojave if you are running an older version (see Updates in the App Store)

2. xCode (Install from the App Store if it is not installed)

3. Unless you already have a password vault option. Get [LastPass](https://www.lastpass.com/), - password manager, download the app, get the chrome extension.  We are going to make a lot of accounts, they need to have good passwords.

4. Signup for a [Slack account](https://slack.com/) [download the app](https://slack.com/downloads/) and put it somewhere easy to access.  (Your line of communication for the class and potentially at your future employer)

5. Join the [MTCS Workspace](https://join.slack.com/t/mtcodeschool/shared_invite/enQtNTIxMTQ4ODE1NDA4LTQ4YTU3NzlkZjBmMTUyOWViOTcyNjIwODg4MzY1ZGM5MWI5YzcwM2NiZDM3ODYzNWI1Y2VjODBhYjIyZGUyMmM).  Give a shout out to your instructor if this link isn't working.  Now that you have Slack you can join the stream and get faster feedback on questions.

6. [Google Chrome](https://www.google.com/chrome/browser/desktop/index.html). For our browser we will be using Google Chrome for this class. It is fast, has great debugging tools, and establishes a good working standard.  Even though they definitely do evil now.

7. At MTCS we will start out using the Atom text editor. Once you start to feel a bit more comfortable we can talk about other options. [Download Atom](https://atom.io/) and install the command line tools.

8. Signup for a [Wakatime](https://wakatime.com) account and [Integrate Wakatime](https://wakatime.com/atom) into Atom

9. Sign up for a [Github account](https://github.com/) although given that you are reading this document, there is the possiblity of redundancy.

10. [setup ssh](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/) for git.

11. Sign up for a [Heroku account](https://www.heroku.com/)

12. Create a [MeetUp Account](https://www.meetup.com/) and join the [Montana Programmers](https://www.meetup.com/Montana-Programmers/) and [Missoula Tech](https://www.meetup.com/Missoula-Tech/) meetups.

13. Create a [Medium Account](https://medium.com/), Medium is a news outlet that has a fantastic amount of relevant info.

14. Create a [Stack Overflow](https://stackoverflow.com/), Stack Overflow is a giant repository of knowledge, it will be your friend.

15. Schedule some time to record and reflect on your journey each week and aim to have to publish a blog at mininmum once a month on [MTCS Medium](https://medium.com/montanacodeschool)

16. If you don't have a  [LinkedIn Account](http://linkedin.com) make one add your work history, resume and a decent picture.

### Your code folder

Lets take a quick break from the browser and jump into the [terminal](#find_your_terminal).

We will try to limit our programming within one folder, our "code" folder. We will also learn our first terminal commands in the process. Let's set that up.

* click in the window that you found through spotlight
* create a new folder: `mkdir ~/code`
* go to the folder: `cd ~/code`

Organize all of your code in this folder. If you need to get to the folder within Finder, you can navigate to your user home folder, and the code folder will be within it.

Now we are going to install some things in our terminal.

1. run `xcode-select --install` This should update the path for your xcode command line tools.

2. In your browser navigate to the [Brew Homepage](brew.sh) there is a ruby script, grab it and paste it into your open terminal instance.

3. You may need to wait a bit. Check that everything went well with `brew -v`

4. With brew in place you may now install node with the command `brew install node`

5. As well as npm with `brew install npm`

6. At the `$` type `node -v` and `npm -v` these should give you version output if all went well.

7. [Follow the directions Here](https://devcenter.heroku.com/articles/heroku-cli#download-and-install) so that you have the heroku toolbelt.

8. If that all goes well a `heroku -v` at the prompt -> `$` should give you version output.

### Customizing your terminal

The standard terminal is boring. There are a few options to build out a little more usability in the terminal.

You may go the `zsh` route by following the steps in this [Gist](https://gist.github.com/ZenLulz/c812f70fc86ebdbb189d9fb82f98197e)

If everything worked as expected your Terminal should look like the screenshot shown in the Gist.

The other option is to download [Iterm](https://www.iterm2.com/version3.html)

Either way you should look into build a `.bash_profile` in your user directory.

### Summary Checklist

Do you have:

* [ ] Latest OS
* [ ] `xcode`
* [ ] `homebrew`
* [ ] `node`
* [ ] `npm`
* [ ] `code` directory
* [ ] `heroku CLI`
* [ ] LinkedIn Account
* [ ] Github Account
* [ ] Password Manager
* [ ] Heroku Account
* [ ] MeetUp Account
* [ ] WakaTime Account
* [ ] Medium Account
* [ ] Stack OverFlow Account
* [ ] A time scheduled weekly to reflect on the process in Medium
* [ ] Slack App
* [ ] Atom Text Editor
* [ ] Atom Integrated With Wakatime
* [ ] `ssh key` for github
* [ ] FINISH YOUR [PRE-WORK](./PREWORK.md)

### Before class starts

Get all those boxes checked? Good.

Take a minute and fill out this [form](https://goo.gl/forms/giMdWq9nHlW6DqMu2)

Now you are ready for the next and final challenge before class starts:

[This repo](https://github.com/Montana-Code-School/first-assesment)  holds a basic server and some very simple javascript, css, and html files.

Jump over there and fork the repo to your profile.  Follow the directions in the [Readme](https://github.com/Montana-Code-School/first-assesment/blob/master/README.md)

*****

## Finally

### When you get stuck

That probably took a minute and maybe you got stuck along the way.  Make sure to check [those frequently](../FAQ.md) asked things.  If your question isn't in there lets follow a simple formula:

* *Read* -- The documentation is a great place to start. Read through it, don't just scan, start at the top and Read.

* *Search* -- Googling is pretty simple.  You probably do it all the time, but googling **well** and for specific information? This is a skill you will need to develop. Start today.

* *Ask* -- Alright you've exhausted your other options, well that's why you're part of this community of helpful folks. Ask one of your instructors.

This is outlined in more detail [here](https://medium.freecodecamp.org/read-search-dont-be-afraid-to-ask-743a23c411b4)

### Asking a good question in the real

Part of the Code School process involves developing self-directed individauls.  This bootcamp is an abbreviated and intense process, it will get you started, but after that you will be on your own.

Well, kinda.  There are still many coders out there that are into helping you solve problems, but they may not be quite as amenable to being told for the fiftieth time that _"it doesn't work"_ and then walking you back through the entire process.

Understanding how to debug your own process and ask a good question is essential to living in this environment and not getting yelled at too much.  Incidentally it will also help your instructors answer your questions.  There is a basic formula for this as well: [Minimum, complete, verifiable](https://stackoverflow.com/help/mcve)
