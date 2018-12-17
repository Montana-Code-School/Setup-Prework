# Frequently Asked Questions

**Ed** - Instructor @Missoula <br>
**Austin** - Instructor @Missoula <br>
**Mark** - Instructor @Bozeman <br>
**Georgie** - Instructor @Bozeman
*****

### _What computer should I purchase?_

  - **Ed** | There are a lot of options here and a lot of factors to consider, most of them revolve around price.  Here are some decent baseline specs for a workhorse type machine:

|  thing  | decent | better  |
| ------- |:------:| ------: |
| RAM     |  8gbs  | 16gbs |
| Drive   |  250GB | 500GB |
| GHz     | 2.3/.5 |  3+ |


A machine older than 5 years slows your process way down.

Wouldn't worry about graphics cards, macs don't place high there anyway.

****

### _I'm having pathing errors running `xcode-select --install`.  WTF!_

- **Ed** | Yup that happens.  Take Douglas Adam's advice and Don't Panic.  Start by looking for the possiblity that someone else might have had the same error with google. [Stack Overflow is your friend](https://stackoverflow.com/) If you have exhauasted that route, which would be impressive because it would be like exhausting the entire internet, hit me up on Slack/text/email.

****

## Things learned from history 
****

Past errors in a glob.

_Path errors installing xcode, brew, npm and node_

 - Upgrade to latest mac os
 - Download xcode from the app store
 - do you know how to find your terminal?
   - **Nope**
     - open spotlight in your finder bar at the top it's a little magnifying glass.
     - take a minute to drag the terminal app to your shortcuts bar, you will be using it a lot.
     - open it
   - **Yes of course I do** countinue on into the woods....
   
- if terminal is running quit and restart.
- In your new terminal instance type `xcode-select --install` at your command prompt and press enter. Your command prompt looks like -> `$` <- with some text in front of it.
    - **Error?** You might get a path error here, drop it into google or slack, we'll see what we can do.
    - **No Error** -> countinue on down the rocky path...
- Google -> **|** homebrew install mac os **|** this page will have a curl command to install homebrew. The url should look like -> `brew.sh`

 - Copy the command and paste it into your terminal, this is in general a bad idea, so lets double check that you want to the right place `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
` is good? Press return.

  *sidenote --* your terminal is a powerful place, you can delete files and folders with a keystroke, take a moment in the beginning to double check, post in slack if you are unsure.
   
 - Check that you installed brew at your command prompt -> `$` type `brew -v` it should give you version output

 - install node -> `brew install node`
 - install npm -> `brew install npm`
 - -> `$` type `node -v` and `npm -v` these should give you version output
