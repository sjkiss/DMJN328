---
title: Getting Set Up For DMJN328
author: 
- Simon J. Kiss
date: December 8, 2020
bilbiography:
reference-section-title: References
---
# Getting Set Up For The Course

There are three bits of software necessary to install.

1. R
2. RStudio
3. GitHub Desktop

I have also included a screencast of how to go through and install these here. 

## Installing R
There are Mac and PC versions of the statistical software R. Please visit this website [https://cran.r-project.org/](https://cran.r-project.org/) and select either Mac OS or PC. Download the software to anywhere on your PC, double-click and walk-through the steps necessary. 

## Installing RStudio
You can consider R to be the engine of a car; it actually does the work of the data analysis. But you can consider RStudio to be the dashboard; a bunch of user friendly panels to tell you what is happening and tools to make the engine do the work. You'll actually never open up R on its own; you'll only ever work with RStudio. But RStudio won't work without R.

To install RStudio visit: [https://rstudio.com/products/rstudio/](https://rstudio.com/products/rstudio/) and download the free version of RStudio Desktop. Follow the steps below:

![Step 1](images/rstudio1.png){ width=50% }

![Step 2](images/rstudio2.png){ width=50% }

When you reach this screen, select the version of RStudio that matches your operating system. 

![Step 3](images/rstudio3.png){ width=50% }


## Installing GitHub Desktop
In this course we will be using GitHub for three reasons because it will enable collaboration even in a remote context. Basically, GitHub is a developer's version of Dropbox. We'll spend a whole class on it early in the class. For now, this is how we'll get it set upt.  

### Sign up for a GitHub Account. 
1. Visit [https://desktop.github.com/](https://desktop.github.com/) and download the software for your operating system. 

![Installing Github Desktop](images/install_github_desktop.png){ width=50% }

2. Download the software, double-click it to unpack it to install it. For macs, after installation, you may have to drag it to the `Applications` Folder. 

![Double-click to unpack and install. You may want to drag it to the Applications folder on macs.](images/github_desktop.png){ width=50% }


3. Visit [https://github.com/](https://github.com/) and sign up.

![Sign up for a Github account](images/create_github_account.png){ width=50% } 

If I may provide a bit of advice, at this point: pick a user name that is professional and linked to your overall, online professional identity. This is an outward-facing site and, in an ideal world, would be used by you to share all kinds of projects.

2. Enter this URL your browser bar: [](http://github.com/sjkiss/DMJN328) or enter `DMJN328` in the search bar in the top left. 

![Search GitHub for the DMJN328 course repository.](images/search_for_dmjn328.png){ width=50% }

This should bring you to the central course repository `sjkiss/DMJN328'. 

3. Click on 'Fork'

![This is how you fork or clone a repository to your own](images/fork_course_repository.png){ width=50% }

You should now have a copy of the course in your own repository. See the next image. Notice how there is a repostiory that has the file name of `dmjn328-mac-student/DMJN328` that has been forked from `sjkiss/dmjn328`. 

This is now *your* *remote* copy of the course! Congratulations! We just need to get you a *local* copy of the course, on your computer. See the next step. 

![](images/forked_copy.png){ width=50% }


### Clone the course repository to your computer.
4. Open Github Desktop. You should see a screen like this. Select `Clone a repository from the internet`

![You should see this screen.](images/github_desktop_screen1.png){ width=50% }

5. This will bring up a window like this: Sign in with your Github user name and password. It may take you to your browser to sign in online. Please do so. 

![Sign in here with your user name and possword.](images/github_sign_in.png){ width=50% }


6.This will bring up a list of your repositories that you can download to your computer. Select your DMJN328 repository. After highlighting DMJN328, select `Clone`

![This screen shows the repositories that you have on your remote account.](images/github_desktop_repositories.png){ width=50% }

7. This will bring up a screen that should have your repository's URL and a field for you to pick a local folder to store your local copy of the repository. Select `Choose`. 
 
![This screen shows the URL of your repository.](images/github_select_choose.png){ width=50% } 

8. This will bring up a dialogue box where you can pick the folder that will store a folder that contains a local copy of your course repository. Note, the folder you select must be empty. here, I'm picking a folder called Year 3. Note, this folder already exists on my computer. This part is sort of up to you. 

![This screen gives you the chance to select the folder that will contain the local copy of your repository](images/github_select_local_folder.png){ width=50% } 


# Testing
You should all be set up to start the course, but to test it. I'd like to ask you to follow these steps. 
First, go to RStudio and select `File > Open Project'

![Open a project](images/file_open_project.png){ width=50% }. 

Then, navigate to your folder that you have cloned on your hard drive, in that `DMJN328` folder.  You should see a file in there called `DMJN328.Rproj`. Click (or double-click) on that file and open it. 

![This is the DMJN328 Project file.](images/open_dmjn328.png){ width=50% } 

You'll know that you have that open when you see DMJN328 in the top-right of the Rstudio screen, like this:

![This shows you that you have opened your DMJN328 project. ](images/dmjn328_project.png){ width=50% } 

Now, if you look inside the course folder that we cloned to your computer from your repository, you should see a file install_script_with_plots.R`. Here is a screenshot of my DMJN328 folder; yours should look very similar to this.  You can open it, just by clicking on it. 

![Locate the file `install_script_with_plots.R' under the `File` tab in RStudio](images/install_script_with_plots.png){ width=50% } 

This is a `script`. A litle computer program written in R. You'll be writing your own scripts this term. But right now, I just want you to run this script by clicking the button `Source`. Please be sure you are connected to the internet. The first few commands in the script install some packages of commands that we will use in the course. 

![This should be about in the top-center of your screen.](images/source.png){ width=50% } 

Also, you *may* get some messages asking you to install different versions of the software. Honestly, it won't make a huge difference, but if you do, just select "Y" for Yes or, if the option presents itself choose to install the CRAN version of the package. This might require you entering in a number (e.g. 1 or 2) in the R console and pressing enter. But it's pretty easy. 

![](https://raw.githubusercontent.com/sjkiss/DMJN328/master/images/image7.png){ width=50% }


At the end of the script, you should be able to select the `Plots' tab in the bottom right of your screen and move between two graphs that have been produced. One looks like this:

![Plot 1](images/plot1.png){ width=50% } 

And one looks like this.

![Plot2](images/plot2.png){ width=50% } 

If you've got both of those plots, you're ready to go for this course, I'll see you on Monday January 11th!! And I'm really looking forward to working with you! You're going to produce some amazing work this term!

