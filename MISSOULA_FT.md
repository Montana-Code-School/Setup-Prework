# Configuring your setup for Montana Code School
## Missoula Campus Edition

At Montana Code School, we all need to be running similar systems and software to make it easier for us all to share and communicate.

This walkthrough is meant to help you set up your machine for the code school, and get you more comfortable with making changes.
*****

## Before you start

**Make sure you backup all of your data**

One of the first myths we need to dispel is that computers are fragile. As a programmer, you will be installing and configuring a lot of software, and some of these can cause issues with other software. Someday you **will** lose data, so you have to get in the habit of making backups periodically.

Might be a good idea to keep a hard drive around, or subscribing to a service like Dropbox to store your data.

Here are some backup options:

* [Seagate Backup 1TB](https://www.amazon.com/Seagate-Backup-Portable-External-STDR1000100/dp/B00H4XH5FY)
* [Apple Time Machine](https://support.apple.com/mac-backup/)
* [Apple iCloud](https://support.apple.com/mac-backup/)
* [Dropbox](https://www.dropbox.com/)

## Your Computer
****
We have recently transitioned to a mac-only campus for the simplicity and speed of the process. Macs are definitely more expensive, but they ship with a lot of solid starting options for developers.  If for some reason you simply cannot run a mac os, we can talk about what your options are, this will depend a great deal on you ability to debug your own machine as the instructors can't take time out to setup a single tricky environment. 

If you have questions about what to purchase check the [FAQ](./FAQ.md) or email/Slack/text an Instructor.

## Setting up your machine

As you begin programming, your computer is going to get cluttered *fast*. It's important for you to clean up your machine before class begins to minimize frustration.

**So do yourself a favor and give it a good cleaning**

A great tool for house cleaning is [CleanMyMac](https://macpaw.com/cleanmymac) by MacPaw.

### Installing software

Coding is text that eventaully gets turned into binary by a computer.  The bare minimum you will need to code for the web is a browser and a text editor, but we have a few more things that help us along the way.

Set some time aside, this might take a minute.  Put on some good music and lets check some boxes.

1. Upgrade to macOS Mojave if you are running an older version (see Updates in the App Store)

2. xCode (Install from the App Store if it is not installed)

4.  Unless you already have a password vault option. Get [LastPass](https://www.lastpass.com/), - password manager, download the app, get the chrome extension.  We are going to make a lot of accounts, they need to have good passwords.

2. Signup for a [Slack account](https://slack.com/) [download the app](https://slack.com/downloads/) and put it somewhere easy to access.  (Your line of communication for the class and potentially at your future employer)

1. [Google Chrome](https://www.google.com/chrome/browser/desktop/index.html). For our browser we will be using Google Chrome for this class. It is fast, has great debugging tools, and establishes a standard for all of us to work with.  Even though they definitely do evil now. 

2. At MTCS we will start out using the Atom text editor. Once you start to feel a bit more comfortable we can talk about other options. [Download Atom](https://atom.io/) and install the command line tools.

3. Signup for a [Wakatime](https://wakatime.com) account and [Integrate Wakatime](https://wakatime.com/atom) into Atom

6. Sign up for a [Github account](https://github.com/) and  [setup ssh](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/) for git.

7. [Heroku account](https://www.heroku.com/) as a bonus 

8. Create a [MeetUp Account](https://www.meetup.com/) and join the [Montana Programmers](https://www.meetup.com/Montana-Programmers/) and [Missoula Tech](https://www.meetup.com/Missoula-Tech/) meetups.

9. If you don't have a  [LinkedIn Account](http://linkedin.com) make one add your work history, resume and a decent picture.

Lets take a quick break from the browser and jump into the terminal.

## Termimal

The terminal is a text-based way to interact with you machine, it can do all the things you do with your mouse and more.

* Search for Terminal in  Spotlight
   ![spotlight mac](https://support.apple.com/library/APPLE/APPLECARE_ALLGEOS/Product_Help/en_US/PUBLIC_USERS/135122/S0071_SpotlightMenu.png)
* The next commands will all be run from the Command Line, the space after the `$` is called the prompt
   ![terminal shell](https://www.howtogeek.com/wp-content/uploads/2016/10/xansiweather-mac-terminal.png.pagespeed.gp+jp+jw+pj+ws+js+rj+rp+rw+ri+cp+md.ic.eKbZVGPsfl.png)

We will try to limit our programming within one folder, our "code" folder. We will also learn our first terminal commands in the process. Let's set that up.

* click in the window that you found through spotlight
* create a new folder: `mkdir ~/code`
* go to the folder: `cd ~/code`

Organize all of your code in this folder. If you need to get to the folder within Finder, you can navigate to your user home folder, and the code folder will be within it.

Now we are going to install some things in our terminal.

1. run `xcode-select --install` This should update the path for your xcode command line tools.

1. In your browser navigate to the [Brew Homepage](brew.sh) there is a ruby script, grab it and paste it into your open terminal instance.

2. You may need to wait a bit. Check that everything went well with `brew -v`

3. With brew in place you may now install node with the command `brew install node`

4. As well as npm with `brew install npm`

5. At the `$` type `node -v` and `npm -v` these should give you version output if all went well.

## Customizing you terminal

The standard Terminal is boring. There are a few options to build out a little more usability in the terminal.

You may go the `zsh` route by following the steps in this [Gist](https://gist.github.com/ZenLulz/c812f70fc86ebdbb189d9fb82f98197e)

If everything worked as expected your Terminal should look like the screenshot shown in the Gist.

The other option is to download [Iterm](https://www.iterm2.com/version3.html)

Either way you should look into build a `.bash_profile` in your user directory.

## Summary Checklist 

Do you have:

- [ ] Latest OS
- [ ] `xcode` 
- [ ] `homebrew`
- [ ] `node`
- [ ] `npm`
- [ ] `code` directory
- [ ] `heroku CLI`
- [ ] LinkedIn Account
- [ ] Github Account
- [ ] Password Manager
- [ ] Heroku Account
- [ ] MeetUp Account
- [ ] WakaTime Account
- [ ] Slack App
- [ ] Atom Text Editor
- [ ] Atom Integrated With Wakatime
- [ ] `ssh key` for github

## Finally

At any point during your configuration, or your prework in general, please don't hesitate to get ahold of your instructor, either over email or Slack.