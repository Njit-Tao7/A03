

# Directions on Using Webstorm
## What is Webstorm ?
WebStorm is an integrated development environment for coding in JavaScript and its related technologies, including TypeScript, React, HTML and CSS.

Instead of typing code in regular notepad or text files, Webstorms let you type your code in a more visual apealing environment.

### Benefits of Webstorm

* It has advanced coding features such as code completion,navigation, refactoring, and quick fixes, to mention a few
* Supports a wide range of testing frameworks for debugging
* It comes with built-in development tools that supports popular web development technologies such as HTML,CSS and JavaScript 

## What is Git and GitHub?
**GIT** is an open source version control system that helps you keep track of the changing you make to documents.

**Github** is a cloud-based hosting service that lets you manage Git repositories.


### How To Use Git&WebStorm
Instead of having to log in to the Github platform every time you make changes to your files, Webstorm allows you to make and upload changes without logging in to Github at all.

* Download and install WebStorm
    * <a href ="https://www.jetbrains.com/webstorm/"> Download Webstorm</a>
* Install Git
    * <a href="https://git-scm.com/book/en/v2/Getting-Started-Installing-Git"> Instructions</a>
* Create Github account
    * <a href="https://github.com/">Instructions</a>  
* Sign in to Github on Webstorm
* Create a or **clone** a **Repository** on Github.com or WebStorm
    * **Cloning** means you're making a copy of a repo from Github and bringing it to your local machine
  <img src="Screenshot 2023-02-14 at 10.57.36 PM.png" />
* After your repo is set up, you're ready to start coding
    * Create a **branch** by typing (git checkout -b branch-name) in your terminal
    * Create your HTML and CSS files
    * after making local changes 
    * **Commit** your changes by typing (git commit -m "commit message ")
    * **Push** your changes by typing (git push origin branch-name)
* File is now on Github
* Create a **Pull** request if you want to **merge** your changes into a master branch
* While doing this , you might encounter a **Merge Conflict**, this is when Git is unable to automatically resolve different 
in code between two commits refer to <a href=" https://www.simplilearn.com/tutorials/git-tutorial/merge-conflicts-in-git#:~:text=A%20merge%20conflict%20is%20an,on%20different%20lines%20or%20branches." >this article </a>to learn how to solve a merge conflict 
* To get changes from other branches you can run git **fetch** or pull
    * Use pull when you have complete context about the changes you will be getting from your remote repository and adding to your local copy.
    * Use Fetch if only if you only want to see all the current branches and changes in your remote repository,
## References
* <a href="https://devmountain.com/blog/git-vs-github-whats-the-difference/#:~:text=GitHub%E2%80%A6-,what's%20the%20difference%3F,help%20you%20better%20manage%20them">REFERENCE 1</a>
* <a href="https://git-scm.com/book/en/v2/Getting-Started-Installing-Git">REFERENCE 2</a>
* <a href="https://www.simplilearn.com/tutorials/git-tutorial/merge-conflicts-in-git#:~:text=A%20merge%20conflict%20is%20an,on%20different%20lines%20or%20branches">REFERENCE 3</a>