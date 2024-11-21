# Homework #4   
**Due Friday Nov. 22nd @ 11:59 pm**
**Regrade Requests Due Friday Dec. 6th @ 11:59 pm**

**Objective:** This assignment synthesizes many data analysis and plotting skills you have learned this quarter including reading text files, Numpy, Pandas, SciPy, and plotting.

### Accessing Class Code and Instructions

1. Create a fork of the class repository in GitHub.

2. Clone this repository into the home directory of your own JupyterHub by running this command:
```git clone your_SSH_URL```

**Our JupyterHub server has trouble remembering the file permissions for our SSH keys. If you get a file permission error with your private ssh key, run the following line of code in your Terminal:**

```chmod 400 ~/.ssh/id_ed25519``` 
<br>

This will change your file permission to the proper permissions that SSH requires.

3. There should now be a "homework_4" directory in the home directory of your JupyterHub. In terminal, change directories into "homework_4". Next, click on the the "homework_4" icon on the filepath hierarchy in the left panel of JupyterHub. If you don't see it, make sure you're in the home folder by clicking the folder icon under the search bar. 

4. Double click the "HW4.ipynb" to open it in a new tab and begin working on the assignment. Read the instructions carefully, and make sure to write your answers in the specified cells. 

5. Make sure to use the answer variable names provided in the starter code. There are autograder tests embedded in the notebook that will check your work when you run the Autograder, and you can which tests you passed/failed after you submit.

6. Edit the README file and write your name and UW NetID. Include a paragraph on some advantages and disadvantages of smoothing data by linear regression, interpolation, or rolling means (4-5 sentences. Review the week 8-9 pre-lectures for review on these methods. (5 points)

7. As you continue to answer the homework questions and make edits to your code, make sure to regularly update your GitHub repository as well via git add, commit, and push. A good rule of thumb would be to run these git steps anytime you make an addition or change that you don't want to accidentally lose. Generally, you can push once a day to maintain good version control practices. <br>

Also, make sure that your git commands are running without errors before you refresh your GitHub and check your changes. If you are not seeing the updated changes you created in your local JupyterHub directory, check where your status is by this command: <br>
``` git status```

Then, you can see if you made an error with your git add, commit, or push commands.


### Ari Paulik - agpaulik
Interpolation can be a really powerful tool in establishing clean and complete data, however it still has its downsides. Interpolation can be used to fill in gaps of potential missing data or create a specific desired point that doesn't exist in the data already. For example, if an individual wanted the chlorophyll concentration from a cruise at a specific location on a day that chlorophyll concentration was not recorded, they can use interpolation to estimate this value based on values around it. However, interpolation can make a lot of assumptions about the data around it and it's imperative that the correct interpolation method is chosen in order to avoid anomalous values that don't make sense with the standing data. Understanding that interpolation does not provide a wholly accurate output is very important in understanding the usefullness of interpolation.