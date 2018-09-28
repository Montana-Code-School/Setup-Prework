# Set Up Guide for Montana Code School

## Bozeman Campus Edition

At Montana Code School, we all need to be running similar systems and software to make it easier for us all to share and communicate.

Please follow the following guide prior to the first day of class, so we can all hit the ground running on day one.

## Hardware

### You Have to Bring to Class

- Apple Macbook (ideally Macbook Pro, things can get intense coding, so the more RAM, storage, etc. the better).
- Any sort of dongle you need to plug in into a HDMI input on a big screen TV.

#### Optional Items

- Wireless Apple Keyboard
- Wireless Mouse
- Anything else that helps your workflow

### Back Up Your Current Data

**Make sure you backup all of your data prior to your course and periodically thereafter**

There many ways to backup your Macbook, here are the most common ones:

- [Apple Time Machine](https://support.apple.com/mac-backup/)
- [Apple iCloud](https://support.apple.com/mac-backup/)
- [Dropbox](https://www.dropbox.com/)
- External Hard Drive

### Give Your Mac a Good Cleaning

If your Mac already runs pretty slow, it won't get any faster with the stuff we are doing.

**So do yourself a favor and give it a good cleaning ;)**

Uninstall unnecessary software, clear up space and reduce clutter.

A great tool for house cleaning is [CleanMyMac](https://macpaw.com/cleanmymac) by MacPaw.

## Software

Again, since we will do a lot of mob/pair programming it is easiest that we all install and work on the same software.

Sharing machines and having to switch from one text editor to a different one has proven to be a huge time sink. Finding the right keyboard shortcut gets very cumbersome and just gets in the way especially when your brain is working hard on solving a coding problem.

**To avoid these problems we will "make" you use a specific bundle of software** (This is also not uncommon in the working world for the same reasons)

### Things You Have To Install (and Use)

- macOS (Well this should be installed if you have a Mac ;) )
- Upgrade to macOS High Sierra if you are running an older version (see Updates in the App Store)
- xCode (Install from the App Store if it is not installed)
- [Slack Desktop & Mobile App](https://slack.com/downloads/) (Your communication timeline for the class and potentially at your future employer)
- [Google Chrome](https://www.google.com/chrome/) (Only latest NON-Canary version please)
- [Visual Studio Code](https://code.visualstudio.com/download) (IDE/ Source Code Editor)
- [Sourcetree](https://www.sourcetreeapp.com/) (Git Client)

### Windows?

Sorry, we don't have time for this \*\*\*\* :P

### Linux?

We can work with that, let's chat more prior to the course starting.

### Sign-Up for following accounts

- [LinkedIn](http://linkedin.com)
  - Create and/or polish your profile, it is at least as important as your resume if not more if you are looking for tech job.
  - Connect to your instructors [Georgie](https://www.linkedin.com/in/georgiekirschner/) and [Mark](https://www.linkedin.com/in/mark-buckner/).
- [GitHub](http://github.com)
  - Create an account. Pretty much all of the code you will write, will end up here. Again a lot of companies look at the activity on your profile.
  - Slack your GitHub user name into our channel so we can add you as a team member to our Montana Code School GitHub account.
- [MeetUp](https://www.meetup.com/)
  - Create an account and join following the [Montana Programmers](https://www.meetup.com/Montana-Programmers/) and [Bozeman JavaScript Meetup](https://www.meetup.com/Bozeman-JavaScript-Meetup/) groups.
  - These meetups are a perfect way to meet developers in Bozeman. Especially if you are looking to get a developer job, having a personal connection with some can be an easy way into a company!

### Loose Your Terminal Fear

The standard Terminal is boring. Let's make it pretty!

1. Open Spotlight Search (<kbd>Command</kbd> + <kbd>Spacebar</kbd>)
2. Type Terminal and hit <kbd>Enter</kbd>
3. Terminal App should open in its black and white glory
4. You should be able to type next to the `$` sign.
5. Paste following code<br>`xcode-select --install`<br>into your Terminal and pressing <kbd>Enter</kbd>
6. Install [Homebrew](https://brew.sh/) by pasting the following code<br>`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`<br>into your Terminal and pressing <kbd>Enter</kbd>
7. The magic should begin and a bunch of output gets printed to your terminal.
8. Once the installation is done type `brew -v` and hit <kbd>Enter</kbd>
9. You should see `Homebrew 1.7.3` output (maybe with higher version number) in your terminal which means it has been installed successfully (if not try to repeat above steps).
10. Now follow the steps in this [Gist](https://gist.github.com/ZenLulz/c812f70fc86ebdbb189d9fb82f98197e)

If everything worked as expected your Terminal should look like the screenshot shown in the Gist.

### Optimize Visual Studio Code

1. Make sure you have Visual Studio Code installed and you lost your terminal fear described in the steps above
2. Open Visual Studio Code
3. Click "Code->Preferences->User Settings" in the top menu bar
4. Search for "editor: font family" in the search bar
5. Change the font family to "Source Code Pro for Powerline"
6. Search for "shell" in the settings
7. Make sure that "Terminal > Integrated > Shell: Linux" and "Terminal > Integrated > Shell: OSX" show "/bin/zsh" as their path

### Create a Code Folder

Let's mak a folder for all your coding projects

1. Open Terminal
2. Type `cd ~` and hit <kbd>Enter</kbd> to access your home directory
3. Type `mkdir code` and hit <kbd>Enter</kbd> to make a new code folde rin your home directory
4. Type `ls` and hit <kbd>Enter</kbd>
5. code should show up as a folder in your home

### Streamline GitHub

[Add a SSH key](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/) to your GitHub account

# TO BE CONTINUED...

## Finally

At any point during your configuration, or your pre-work in general, please don't hesitate to get ahold of your instructor over Slack.
