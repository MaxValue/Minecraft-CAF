#MINECRAFT CAF\*

**CAF stands for "citius, altius, fortius", the current olympic motto.*

##Explanation

I noticed that Minecraft (PC) mostly runs outdated libraries. Effects of this are more laggs, more bugs, less fun, less utilisation of computer hardware. In short: Minecraft doesn't do it's job that well.

But you can change that. Since the new launcher was born, settings are made more central and easier to customise. The launcher has the option to create different profiles with variable Minecraft versions. The settings for these profiles are stored in JSON-files. I already did the job for you and updated all profiles for all minecraft versions for you. What does this change, you ask? Minecraft now loads newer versions of the required libraries and runs overall better.

###TL;DR

Make Minecraft better by altering tiny textpieces in your `.JSON`-profiles.

##Important Note

**Use this at your own risk. Not every feature has been tested with these updated settings, but I'm working on it to change this. Beware.**

##Installation

###UNIX-like machines

Use the minecraftCAF.py file to update your profiles. You need to download the `libraries.JSON`-file beforehand.

###WINDOWS

Use the minecraftCAF.vbs file to update your profiles. You need to download the `libraries.JSON`-file beforehand.


##FAQ

Q: B-But dude, what about forge?! I need that stuff!
A: You can also use forge with this, in fact, this project was started because of forge. The installer script runs through the profile and replaces every outdated library it finds. So it also works with other modloaders besides forge.

Well, I couldn't think of anymore questions to ask about this, so contact me if you want to know something.

##Roadmap

1. Write collector script (see developer folder)
2. Collect all the libraries and their info-sources for current releases.
3. Edit the `libraries.JSON` file acordingly.
4. Write the installer scripts.
5. Automate the retrieval of new version numbers.
6. Implement feature to automatically report newly used libraries.
7. Expand above feature to automatically try new version numbers.
8. Write `.jar`-program to provide functionality on any desktop machine with minecraft installed.
9. If project is not finished by then, automate more.
