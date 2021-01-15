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
the GitHub repository. Red Checkmarks mean the opposite, that there is a file that has been changed but has not been pushed to the Repository.

Go ahead, give it a try. [This is test text] <-- Edit this text and save. You should see the symbol next to README change to a red checkmark.

**Branches & The Master Branch**

Branches are GitHub's way of handling "unofficial edits". A good way to imagine GitHub is like a river. You can have multiple different streams coming off
of the same river, but none of them EFFECT the main river until you link them back to it. For example, if I were to create a branch in GitHub and begin coding
in it, I would have the exact same code as the version of the Master branch I branched off of, however I could code, break everything, and make it into a whole
other program and even if I pushed that to the repository, the Master Branch would stay the same. The only way to link BACK to the Master Branch would be to make
a Pull Request, which is essentially you putting up your code for discussion with the group on whether or not it should be added, and then I press a big red button
and it gets linked into the Master Branch.

Down in the bottom blue line of Visual Studio, you should see some new options to the right hand side of the screen. To the farthest right you should see
an option that looks like a forked arrow with "master" directly next to it. This is your currently selected branch. If you click on it, you should see a dropdown
(or drop UP I suppose?) menu with a few options.

Click on "New Branch". This brings up a wizard to enter a name for a branch and select whichever branch you are splitting off from. Under most cases, that's going
to be the Master Branch, however it gives us the option to choose a different branch should we please. After creating this new branch, you should see that it auto
selected that branch, and now you are working within it. If you log into GitHub on your browser and navigate to the repository 
(https://github.com/DisguisedPirate/TutorialRepo) you should see
