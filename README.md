# Bath_SWE_CW2
Dungeon game for the second coursework for Bath Master's class of '21 Software Engineering course. 

## Installation

- If you do not currently have the project on your machine, download & use the version control software [git](https://git-scm.com/downloads/) to download the dungeon game.

- If you haven't already, you need to make a github account.

- In order to edit the file, fork this github repo to your own account
 * Find where it says "Fork", to the right side of the name of this repo, and fork to your account
 
 - Clone your own repo onto your machine
   * To find the web address for cloning your repo, go to the repo's main page, press the green button "Code" and copy the address there
```bash
git clone YOUR_REPOS_WEB_ADDRESS
```

## Usage

1. To install the Unity Hub for Windows, MacOS, and Linux visit [Download Unity](https://unity3d.com/get-unity/download?_ga=2.209152402.1644705729.1604169206-1437629805.1604169206) on the Unity website.

2. Download Unity 2020.1.10 from [here](https://unity3d.com/get-unity/download/archive?_ga=2.257575048.240383081.1604267562-1981148611.1604164943) (NOTE: You must download Version 2020.1.10, please do not download through Unity Hub or click the wrong version as the project will not work with another version of Unity and others will not be able to open your project on a different version either)

3. Open the Unity Hub, click the "Projects" tab on the left, click "Add" on the top right, then navigate to where the project folder is located and click "OK

4. Once the project is added to your list of projects in Unity Hub, click the project to open it

## Syncing Your Repo with the Main Repo

- If this is your first time using git
```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```
- In order to edit, fork the project to your own github account (See installation)

- Add a local connection syncing the upstream repo to the one forked to your account
```bash
git remote add upstream https://github.com/LiamFosterLFF/Bath_SWE_CW2.git
```

- Pull to local folder (fetch the latest version and merge with your project folder)
In your project folder
```bash
git pull upstream main
```

## Contributing

- If you make any changes to your project, you will need to make a Pull Request in order to add those changes to the main repo
 * NOTE: When you make changes, do not make changes to the scene directly or they will not integrate with the main project. Instead, store your changes in the form of "prefabs". To make a prefab, simply open the "Prefabs" folder under assets in the project window, and drag your game object into that folder. [Good video explaining prefabs](https://www.youtube.com/watch?v=plHcffZ0eLo)
 
- Add, commit, and push to your repo
```bash
git add .
git commit -m "Put a message here that describes the changes you made. Do this often, smaller changes are better"
git push origin main
```

- Then, go to your github repo's webpage, and close to the top, select where it says "Pull requests"
  * On the ensuing page, click the green button "New pull request"
  * You will have a list of comparisons you can choose from. Click the one that includes "LiamfosterLFF/main"
  * Give your pull request a title and some info about the changes you've made
  * Click "Create pull request" and you're good to go, I'll review it and add it into the main project shortly

## FAQ
- What is git?
  * [Good video tutorials](https://www.youtube.com/watch?v=BCQHnlnPusY&list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV)
  * Git docs
  * [Dangitgit](https://dangitgit.com/en) for common tasks using git
  
- What is the command line/bash/ where are you entering all these commands?
  * If you have windows, click the search bar and type CMD to open the command prompt (Or try [these](https://www.digitalcitizen.life/open-cmd))
  * On MacOS, click the launchpad icon and type terminal, then click terminal
  * [Overview of common CLI commands](https://www.w3schools.com/whatis/whatis_cli.asp)
  
- How do I contribute
  * If you want to become a developer on the project, contact me. However, the easier way is by branching or forking the project and then starting a pull request. [Learn more about contributing to a github project](https://akrabat.com/the-beginners-guide-to-contributing-to-a-github-project/)
  
- I read online that I need to do something with the master branch but git gives the error "error: src refspec master does not match any". What's the deal?
  * Starting from October 1, 2020, the master branch has been by default renamed to "main". You can read more about it [here](https://www.zdnet.com/article/github-to-replace-master-with-main-starting-next-month/). Just swap out "main" for "master" and you're good to go.
