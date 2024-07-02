
# Welcome to Codebar’s 10th Birthday - Poetry Challenge!

### Aim:

You have been tasked with helping to write a poem that portrays what Codebar means to you and highlights all of the amazing work that Codebar chapters have been doing for the past 10 years!

We are going to practice our Github skills while we do this and by following the steps below you will learn the following skills:

- Forking a repo
- Pushing up to a repo and pulling down from a repo
- Opening a pull request

## The Main Challenge


- **Step 1 - Forking the Repo:** Fork the repo from [https://github.com/MagariMike/codebar-birthday-poetry](https://github.com/MagariMike/codebar-birthday-poetry) by clicking the "fork" button in the top right of the page.

This will allow you to save a copy of the repo to your own Github profile.



- **Step 2:** Make sure you have navigated to the "forked" version of the repo that you just saved within your Github profile, then click the green button which says "code". This will provide you with a link that you can copy.
  

- **Step 3:** Open your IDE and use the terminal to navigate to where you would like to save your new git folder and run the following command: 


```bash
git clone YOUR_GITHUB_REPO_LINK_GOES_HERE
```

- **Step 4 - Writing your verse:** Now you should have a folder on your computer which has the project files within it which you have pulled down from your repo. 

Find the index.html file and open it. Within this file you will be able to see various <p> tags with different verse names. Find the verse number that you have been asigned and begin to add your desired text. 

- **Step 5 - Making your first commit:** One you have added some text that you are happy with, its time to do your first git commit action. 

Open the terminal within your IDE once more and enter: 

```bash
git add  . 
```

This command adds all files that have been edited to a staging area, ready to be progressed towards their end destination (our online Github repo). 

Then run the command: 

```bash
git status 
```

This will show you all of the files that have been moved to the staging area and its often very useful to check that the right files have been added. 

Next run the command (alter the text in CAPS with your own commit message - ideally this should be the in the following format teamName/verseNumber): 

```bash
git commit -m ‘YOURTEAMNAME/YOURVERSENUMBER’
```

Now you have moved all of your files into the last “waiting area” before they are ready to be pushed up to our online repo. 

The final command to send these changes on they’re way is: 

```bash
git push
```

Congratulations, if you’re this far then you have updated the Github repo on your profile with your poem verse. 

Remember you can repeat the actions from step 5 to update your code if you need to make any further changes. 

*** You’re not quite finished yet, you need to open a pull request ***

### Opening a Pull Request:

Opening a pull request sends a request to the original repo and asks to merge your local repo with it so that the original copy has all of your changes. The owner of the original repo can that accept or deny your changes or add any comments etc. 

In your local repo that you forked, select the “Pull Requests” tab along the top bar of the page. 

You can add any notes that you’d like in the box that appears and then click “Create Pull Request”. This will send a request and one of the tutors will then approve this later in the session.

### CSS Challenge (optional):

If you successfully add your poem verse and want to tackle something a little more colourful! 

A button has already been added which when clicked, changes the stylesheet on the page. 

Why not try and add create your own stylesheet to give the page your own personal twist! 

- **Step 1:** Find the folder called “styles” and add a new file to it with a name of your choosing. The file extension should be .css for example yourTeamName.css. 

- **Step 2:** Go into the folder called “data” and then within the “css-file-list.js” file, add the name of your new css file to the data array. 

- **Step 3:** Populate your file with CSS as you see fit, using the current class names to style the page.  

- **Step 4:** Once you are happy with your styling, complete the actions in step 5 above to commit and push your changes to your Github repo

