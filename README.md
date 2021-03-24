# Change-FireFox-Homepage-Background
This has the code and instructions on how to change Firefox's Homepage background. It cannot be changed without using CSS or a third-party extension.

You will first need to open **about:support** in your Firefox search bar. There you will find a directory called the Profile folder. It shows the path in which the profile folder is held. Go to this directory in your file explorer and create a folder called "chrome" inside of it. 

![image](https://user-images.githubusercontent.com/67387897/112243446-c6ee4e00-8c0a-11eb-9f32-7cfd25f958b6.png)

It will look something like this.

Next, inside the chrome directory, create a file and a folder. Name the folder "img" and then open the file in a text editor and save it as "userContent.css"

![image](https://user-images.githubusercontent.com/67387897/112243775-63185500-8c0b-11eb-939a-af0e7c91efe4.png)

For me, it would look like this. Follow the directory provided in your 'Profile Folder.'

Inside, you will paste in the contents of the file attached in this repository by the same name. The explanations for the code is inside that file. 

![image](https://user-images.githubusercontent.com/67387897/112244763-f2723800-8c0c-11eb-9ddb-1010d62ca583.png)

Next, you will want to go to about:config in the Firefox search bar.

Accept the risks (no real risks), then paste in "toolkit.legacyUserProfileCustomizations.stylesheet" into the search bar. There you wil find the option to start up the userContent file. Turn this to true. Now, exit Firefox and when you open a new page it should look like the image.
