# Private_Repository_CS4013/5013
Howdy!
<br>

Congratuations for making it all the way to the end of the semester! It was great working with all of you, and congratulations to those graduating! Or have a great summer to those who are close!
<br>

This will serve as a personal guide to creating a private repository for uploading your final project code and documention for CS4013/5013. Please let me know at dvargas88@ou.edu if you have any questions or concerns!

## Step 1: Sign In:
This may go without saying, but you would be surprised how many people forget to sign in before continuing. Make sure you sign in with your OU github account, otherwise you will need to refer to:
<li class="masthead__menu-item">
    <a href="https://canvas.ou.edu/courses/384471/pages/transfer-ownership-of-git-repository">How to Transfer Ownership.</a>
</li>
<br>

## Step 2: Navigate to the Course submission repository:
<li class="masthead__menu-item">
    <a href="https://github.com/AI2025-final-project-submission">Course Submission Repo</a>
</li>

## Step 3: Create a repository:
The next step is to create a repository. In the top right corner, click on the "+" button, then select "New Repository".

<br>

## Step 4: Fill Information for respository:
Below you can find a layout on how to set up your repository. Again, make sure you do this on your OU github. You may notice at the bottom that it notifies you if you are submitting with a personal account, such as mine. You don't want to see this for yours!
<br?> 
Do NOT initialize with README, .gitignore, or license. (This avoids merge conflicts later)

<img src="https://github.com/dannyboy849/Private_Repository_CS5013/blob/main/Guide_Images/Screenshot%20from%202025-04-30%2015-20-08.png">

### NOTE: To ensure its very clear, by Team_# it just means Team_(Your_Teams_Number), i.e. Team_5!

## Step 5: Invite your partners! 
After creating your private repo, invite your teammates as collaborators! Make sure you are all communicating and sharing your progress on the setup to avoid confusion or issues.


# Done! (Technically)
So after this setup, you are essentially done. After those stepse, you can manually submit your documents and call it a day. 
<br>

Or, you can be fancy and access/upload from your terminal!


## Setup to access the repo remotely!
I STRONGLY recommend checking out GitHubs documentation for setting up remote access from your terminal. 

<li class="masthead__menu-item">
    <a href="https://docs.github.com/en/get-started/git-basics/set-up-git">GitHub How-to-Repo</a>
</li>

After this, move onto accessing it! 

```bash
git clone https://github.com/yourusername/Team_#.git
cd Team_#
```

<br>

# Add the Course repo as a remote
Add the OU repo:

``` bash
git remote add AI2025 https://github.com/AI2025-final-project-submission/Team_#.git
```

Now you're in! 

## Push your repo!
Push your branches and tags to the AI2025 remote
```bash
git push AI2025 main # or `master` # depending on your branch name
```

## Ensure your work is uploading
Go to the AI2025 repo and verify its uploading correctly
:
<li class="masthead__menu-item">
    <a href="https://github.com/AI2025-final-project-submission/ "/Team_#" ">Check your hard work!</a>
</li>

# Congrats, that's all there is to it! Good luck in the future! It was a great semester working with all of you, and have a great summer!
