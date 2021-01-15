Hi! Welcome to the GitHub tutorial.

By following these instructions, I'm going to run you through the basic processes for GitHub to function
with Visual Studio as I've been able to understand them after a few sleepless nights!

Links used throughout the tutorial: 
- https://visualstudio.github.com/ (GitHub extension for Visual Studio)
- https://github.com/DisguisedPirate/TutorialRepo (Tutorial Repository)

**The Team Explorer**

Navigate to View > Team Explorer. This will open up a menu to the right of your screen, where the solution explorer primarily is.
This is the Team Explorer. It is our connection to the main repository for all of our projects, and your way of switching between 
those projects while using Visual Studio. With the GitHub extension installed, you should see two options on this screen: GitHub and Azure.

Underneath GitHub, there should be a blue link called "Connect". If you click on this link, you'll be prompted to sign in with your GitHub account.
After signing in, four options should appear under GitHub: Clone, Creat, Signout, and a highlighted option below called "TutorialRepo" with a file
extension. This is the repository that you cloned to get to the tutorial when you opened Visual Studio. Additionally, you can clone another repository
to open a different one by clicking the Clone button and inputting the URL of the repository.

**Slight Changes to Solution Explorer**

If you tab back over to the Solution Explorer, you might notice a small graphical change to the files. Next to (most) of the files you should see either
a blue lock or a red checkmark. If you mouse over them, you'll see what they represent. Blue Locks mean that this file has not been changed since you
cloned the repository. As far as I am aware, it does not account for if anyone ELSE makes a change but instead if YOU have made a change since updating
the GitHub repository.

Go ahead, give it a try. [This is test text] <-- Edit this text and save. You should see the symbol next to README change to a red checkmark.