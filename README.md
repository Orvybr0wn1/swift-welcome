# Welcome!

We're excited to have you learn Swift and iOS development with us. There's a lot to cover in this course and the first couple of lessons in this track will revolve around getting you set up with the appropriate tools and platforms. Be prepared to spend some time on setup, but we promise it will be worth it because these will be the same tools and workflows that you will be using when you're building apps. So what can you expect in this and the subsequent lesson? 

- **Xcode**
- **GitHub**
- **Workflow for solving coding labs in this course**

Let's get started with Xcode. 

# What is Xcode?

Apple creates a lot of hardware such as the iPhone, Mac, Apple Watch & Apple TV. Powering these various devices is software. There are different pieces of software deployed on each device, names you might already be familiar with.

* iPhone- iOS
* Mac- MacOS
* Apple Watch- watchOS
* Apple TV- tvOS

But where do we create this software? For example, we can use a Word document to create essays, stories or other text based documents. For iOS development, Xcode serves as our Word document. It's a place where we write code.

The programming languages we can utilize within Xcode are Swift & Objective-C. When this code is written, we can then *run* the application. When doing so, Xcode is able to take the code we wrote and read it. It does more than read the code; it's able to compile it and allow any of the above devices to run it!

Xcode is considered an Integrated Development Environment, or IDE. Xcode is provided by Apple which allows us to create applications.

# Installing Xcode (Version 8.0)

Download Xcode [here](https://itunes.apple.com/us/app/xcode/id497799835?mt=12). You're required to download Xcode from the Mac App Store. So, after clicking the "View In Mac App Store" link (see screenshot below) you should be directed to the Mac App Store where you can download the application. You need to be on  Mac in order to download Xcode. If you already have Xcode installed on your machine, make sure you go to the Mac App Store and update to the latest version which is version 8.0.

![Xcode Link](https://s3.amazonaws.com/learn-verified/XcodeWeb.png)

![Mac App Store](https://s3.amazonaws.com/learn-verified/XcodeAppStore.png)


Once Xcode is installed, open it to make sure that everything is working OK. When opening the application, you should be presented with this screen (without all of those files listed in the right pane):

![Xcode Open](https://s3.amazonaws.com/learn-verified/XcodeOpen.png)

Locate your Terminal application on your Mac. Pressing command + spacebar will bring up a search bar where you can begin to type in Terminal which is a fast way to locate the application (or any application for that matter!).

![findingTerminal](https://s3.amazonaws.com/learn-verified/XcodeTerminalSearch.png)

Here is what my version of Terminal looks like when it's open.

![termm](https://s3.amazonaws.com/learn-verified/XcodeTerminal1.png)

In order to setup your terminal to look and act like mine (which is important, it will make your life much easier during this course), copy and paste this command into your terminal:

`curl https://raw.githubusercontent.com/flatiron-school/dotfiles/master/.bash_profile -o ~/.bash_profile`

Like so:

![](https://s3.amazonaws.com/learn-verified/XcodeTerminal2.png)

In order for these changes to take place, copy and paste this command inside terminal

`source ~/.bash_profile`

Like so:

![](https://s3.amazonaws.com/learn-verified/XcodeBash.png)

Type the following command in Terminal. Doing so should install the necessary packages. Many useful tools are included, such as the Apple LLVM compiler, linker, and Make. When you run this command, your system may ask for permission to install the packages; click OK.  

`xcode-select --install`

![xfun](https://s3.amazonaws.com/learn-verified/XcodeInstallCommand.png)

Click Install when this window pops up after typing in the xcode-select --install command.

![](https://s3.amazonaws.com/learn-verified/XcodePrompt.png)

# Setting Up GitHub

Make sure you can login to your GitHub account. If you don't have a GitHub account yet, create one.

![](https://s3.amazonaws.com/learn-verified/XcodeGithub.png)

Now we want to setup an SSH Key.The way our lessons are designed, we need for you set this up. In order to set this up through GitHub, follow these instructions:

1. Check to see if you already have an SSH key by following the instructions [here](https://help.github.com/articles/checking-for-existing-ssh-keys/).
2. Generate an SSH Key by following the instructions [here](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/).
3. Now you need to connect your generated SSH Key to your Github Account. Instructions to do that can be found [here](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/).

After you've gone through the above three steps of setting up your SSH Key, you should head back to terminal to copy/paste the following command:

`curl -s https://raw.githubusercontent.com/flatiron-school/ios-setup/master/install.sh`

Like so:

![](https://s3.amazonaws.com/learn-verified/XcodeCurl.png)

If all is good, you should be met with the following prompt:

![](https://s3.amazonaws.com/learn-verified/XcodeComplete.png)

Keep it up! So far, so good.

![](https://media.giphy.com/media/c5PHIq9sXsV6o/giphy.gif)


<p class='util--hide'>View <a href='https://learn.co/lessons/swift-welcome'>Welcome</a> on Learn.co and start learning to code for free.</p>
