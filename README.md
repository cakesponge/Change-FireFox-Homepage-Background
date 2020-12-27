# Change-FireFox-Homepage-Background
This has the code and instructions on how to change Firefox's Homepage background. It cannot be changed without using CSS or a third-party extension.

You will first need to open about:support in your Firefox search bar. There you will find a directory called the Profile folder. It shows the path in which the profile folder is held. Go to this directory in your file explorer and create a folder called "chrome" inside of it. 

Next, inside the chrome directory, create a file and a folder. Name the folder "img" and then open the file in a text editor and save it as "userContent.css"

Inside, you will paste in the contents of the file attached in this repository by the same name. The explanations for the code is inside that file. Next, you will want to go to about:config in the Firefox search bar.

Accept the risks (no real risks), then paste in "toolkit.legacyUserProfileCustomizations.stylesheet" into the search bar. There you wil find the option to start up the userContent file. Turn this to true. Now, exit Firefox and when you open a new page it should look like the image.
