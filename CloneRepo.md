# Clone a Repo with Visual Studio

Here are some instructions (with screen captures) of how to clone a GitHub repo with Visual Studio (2019).  The screen shots and descriptions will help you navigate the process.  Especially, if you have never created a project from a repo before.  (By the way, cloning a repo just means creating a project from a repo.)

The easiest thing to do is start Visual Studio.  (This is true of many other IDEs as well.)  Visual Studio 2019 starts with a screen that has Clone a repo as its first option.  Click on that button (circled in the image).

![Visual Studio 2019 opening screen](https://github.com/MichaelTMiyoshi/CPPwithMiyoshi/blob/master/images/01CPPVSClone.png)

You will come to a screen where Visual Studio is asking you for the URL or Repository location and local path (to your local repo location).  The local path is most likely already filled in with the location where you save your repos.  Or rather with the location where Visual Studio thinks you should place them.  (You can change this in some setting, but that is beyond the scope of this page.)

![Visual Studio 2019 Clone screen without URL](https://github.com/MichaelTMiyoshi/CPPwithMiyoshi/blob/master/images/02CPPCloneFieldsEmpty.png)

Open a browser to the internet and go to the repo you want to clone.  (If you are reading this, then that is most likely what I call the <a href="https://github.com/MichaelTMiyoshi/CPPwithMiyoshi-01VarsAndConsts" target="_blank">first repo</a> to clone in the Readme file).  I have found that you can either click the clone repo button and then the button that copies the repo name onto your clipboard or you can just copy the URL from your browser and paste that in the Repository location field.  Either method works fine.

![GitHub repo page](https://github.com/MichaelTMiyoshi/CPPwithMiyoshi/blob/master/images/03CPPGitHubClone.png)

Paste the URL or the repo name into the correct field in Visual Studio.  (The picture just has the URL and not what was copied to the clipboard in the last instruction.  You can tell because there is no .git at the end.)  Then, click the CLONE button in the bottom right corner.

![Visual Studio 2019 Clone screen with URL (and local repo location)](https://github.com/MichaelTMiyoshi/CPPwithMiyoshi/blob/master/images/04CPPVSCloneWithURL.png)

Visual Studio will open to what is hopefully a familiar screen.  Look for the Solution Explorer window.  If you see the Team Explorer window instead, look down at the bottom and see if Solution Explorer is there on one of the tabs.  If not, go to the view menu and click on Solution Explorer (should be the top one).

Solution Explorer | Team Explorer
----------------- | -------------
![Visual Studio Solution Explorer](https://github.com/MichaelTMiyoshi/CPPwithMiyoshi/blob/master/images/05CPPVSSolutionExplorer.png) | ![Visual Studio Team Explorer](https://github.com/MichaelTMiyoshi/CPPwithMiyoshi/blob/master/images/06CPPVSTeamExplorer.png)

Look in Solution Explorer and you should recognize the folder and file structure.  If there are just triangles by the names, click on the topmost one that is not expanded to see what is there.  When you get to the file that ends with .sln, you have found your solution file.  Double click that .sln file to open the solution.

![Visual Studio .sln file](https://github.com/MichaelTMiyoshi/CPPwithMiyoshi/blob/master/images/07CPPVSsln.png)

Whether your code shows up or not, you can expand the solution even more to find your .cpp (and .h) file(s).  Double click on the file(s) you want to open and they will appear in the editing area are ready for you to edit.

![Visual Studio .cpp file(s)](https://github.com/MichaelTMiyoshi/CPPwithMiyoshi/blob/master/images/08CPPVScpp.png)

If you are opening one of my repos that I link to in the [ReadMe](https://github.com/MichaelTMiyoshi/CPPwithMiyoshi/blob/master/README.md) file of this repo, you can hit the run button and the program will compile and run.  Then, you can modify to your heart's content.

Have fun coding.  And enjoy the ride.
