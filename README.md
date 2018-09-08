# Set Up Guide for Montana Code School
### (Bozeman Campus Edition)

At Montana Code School, we all need to be running similar systems and software to make it easier for us all to share and communicate.

Please follow the following guide prior to the first day of class, so we can all hit the ground running on day one.

## Hardware

### You Have to Bring to Class
* Apple Macbook (ideally Macbook Pro, things can get intense coding, so the more RAM, storgae, etc. the better)
* Any sort of dongle you need to plug in into a HDMI input on a big screen TV 

### Optional Things Which make Things easier at home
Here is a list of what we support here at the code school:

* macOS 
* Google Chrome
* Atom text editor

This walkthrough is meant to help you set up your machine for the code school, and get you more comfortable with making changes.

## Back Up Your Current Data

**Make sure you backup all of your data prior to your course and periodically thereafter**

There many ways to backup your Macbook, here are the most common ones:

* [Apple Time Machine](https://support.apple.com/mac-backup/)
* [Apple iCloud](https://support.apple.com/mac-backup/)
* [Dropbox](https://www.dropbox.com/)
* External Hard Drive

## Give Your Mac a Good Cleaning
If your Mac already runs pretty slow, it won't get any faster with the stuff we are doing.

**So do yourself a favor and give it a good cleaning ;)**

Uninstall unnecessary software, clear up space and reduce clutter.

A great tool for house cleaning is [CleanMyMac](https://macpaw.com/cleanmymac) by MacPaw.

## Software
Again, since we will do a lot of mob/pair programming it is easiest that we all install and work on the same software.

Sharing machines and having to switch from one text editor to a different one has proven to be a huge time sink. Finding the right keyboard shortcut gets very cumbersome and just gets in the way especially when your brain is working hard on solving a coding problem.

**To avoid these problems we will "make" you use a specific bundle of software** (This is also not uncommon in the working world for the same reasons)

### Things You Have To Install (and Use)
* macOS (Well this should be installed if you have a Mac ;) )
* xCode (Install from the App Store if it is not installed)
* [Slack Desktop & Mobile App](https://slack.com/downloads/) (Your communication timeline for the class and potentially at your future employer)
* [Google Chrome](https://www.google.com/chrome/) (Only latest NON-Canary version please)
* [Visual Studio Code](https://code.visualstudio.com/download) (IDE/ Source Code Editor)
* [Sourcetree](https://www.sourcetreeapp.com/) (Git Client)


### Windows?
Sorry, we don't have time for this **** :P

### Linux?
We can work with that, let's chat more prior to the course starting.

### Sign-Up for following accounts
* [LinkedIn](http://linkedin.com)
  * Create and/or polish your profile, it is at least as important as your resume if not more if you are looking for developer job. 
  * Connect to your instructors [Mark] and [Georgie].
* [GitHub](http://github.com)
  * Create an account. Pretty much all of the code you will write, will end up here. Again a lot of companies look at the activity on your profile.
  * Slack your GitHub user name into our channel so we can add you as a member to our Montana Code School GitHub account.

### Loose Your Terminal Fear

The standard Terminal is boring. Let's make it pretty!
1. Open Terminal
  1. Open Spotlight Search (<kbd>Command</kbd> + <kbd>Spacebar</kbd>)
  2. Type Terminal and hit <kbd>Enter</kbd>
  3. Terminal App should open in its 
* Generate a SSH key
* Adding a new SSH key to your GitHub account
* Add SSH key to Sourcetree

### Install software

This step is optional for some classes but highly recommended for everyone:

Signup for a [Wakatime](https://wakatime.com) account and [Integrate Wakatime](https://wakatime.com/atom) into Atom

Here are some things you will need to download

Get [LastPass](https://www.lastpass.com/) - password manager, download the app, get the chrome extension.

[Github account](https://github.com/) as a bonus step [setup ssh](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/) for git.

[Heroku account](https://www.heroku.com/) as a bonus - Heroku command line tools

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

### Things learned from history 
****

So many things, below are some steps you need to take that I was not aware of...  You are in tech now, the rate of change is exceedingly high.  Get used to it.

 - [ ] Upgrade to high sierra, latest mac os
 - [ ] Download xcode from the app store
 - [ ] do you know how to find your terminal?
   - **Nope**
     - open spotlight in your finder bar at the top it's a little magnifying glass.
     - take a minute to drag the app to your shortcuts bar, you will be using it a lot.
     - open it
   - **Yes of course I do** countinue on into the woods....
   
- [ ] if terminal is running quit and restart.
- [ ] In your new terminal instance type `xcode-select --install` at your command prompt and press enter. Your command prompt looks like -> `$` <- with some text in front of it.
    - **Error?** You might get a path error here, drop it into google or slack, we'll see what we can do.
    - **No Error** -> countinue on down the rocky path...
- [ ] Google -> **|** homebrew install mac os **|** this page will have a curl command to install homebrew. The url should look like -> `brew.sh`
 [ ] Copy the command and paste it into your terminal, this is in general a bad idea, so lets double check that you want to the right place `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
` is good? Press return.

  *sidenote --* your terminal is a powerful place, you can delete files and folders with a keystroke, take a moment in the beginning to double check, post in slack if you are unsure.
   
 - [ ] Check that you installed brew at your command prompt -> `$` type `brew -v` it should give you version output

 - [ ] install node -> `brew install node`
 - [ ] install npm -> `brew install npm`
 - [ ] -> `$` type `node -v` and `npm -v` these should give you version output

## Finally

At any point during your configuration, or your prework in general, please don't hesitate to get ahold of your instructor, either over email or Slack.
