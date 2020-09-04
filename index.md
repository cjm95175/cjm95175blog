## Blog 0

# GitHub and Setting Up A Repository. ![](https://img.caixin.com/2019-12-12/1576147635453631.jpg)

### What is Git?

Git is an open source, distributed control system. It was designed to handle a small project, like this blog post, to a fully developed website. It allows any number of developers to collaborate on the same files, documents, and source code simultaneously, without overriding each developer's code. This keeps a steady, controlled flow of changes to any project on the go. 

  ##### Version Control 
  Git provides information regarding any changes to a project's source code. The technical defintion is "a system that records changes to a file, or set of files over time so that you can recall specific versions later." The most minute detail, like a added space or deleted   word, will be highlighted. You'd be able to see who changed it, giving you the ability to place the blame accordingly if something goes wrong!
  
### What is GitHub?
The quintessential open source publishing, version control, and collaboration tool. Nearly everything you'll need for a variety of developmental projects. What's it missing? A money printing machine would be nice!

### Setting Up a Repository
Well there are two ways of executing this. Depending on your comfort levels with a Command Line Interface, it can be done through CLI or GUI, otherwise known as a Graphical User Interface. I will be covering both.

#### With The GUI
- Step 1: Create a GitHub Account ![](https://media.geeksforgeeks.org/wp-content/uploads/20190826232755/1403.png)
- Step 2: Click on "New repository" ![](https://media.geeksforgeeks.org/wp-content/uploads/20190826233513/223-1.png)
- Step 3: Clarify which settings you want ![](https://media.geeksforgeeks.org/wp-content/uploads/20190826235103/4-155.png)
- Step 4: Upload any files you want in there ![](https://media.geeksforgeeks.org/wp-content/uploads/20190827000113/639.png)
- Step 5: Here you can make any edits or changes then commit them ![](https://media.geeksforgeeks.org/wp-content/uploads/20190827000948/726.png)

#### Now Through CLI
Here I'm going to assume that you've already made a GitHub account. Following the proceding steps.
- Step 1: Open up your terminal of choice, create a directory somewhere locally, change into that directory. My terminal of choice is the Git CMD. ![](https://toolsqa.com/wp-content/gallery/git/GitRepoCreation4.jpg)
- Step 2: Create an empty directory with a hidden .git folder. In this example it's named BareGitRepo. ![](https://toolsqa.com/wp-content/gallery/git/BareRepoCreation1.jpg)
- Step 3: Change directories into that new projcet. ![](https://toolsqa.com/wp-content/gallery/git/BareRepoCreation2.jpg)
- Step 4: Use the "git init" command to create the empty repository. ![](https://toolsqa.com/wp-content/gallery/git/BareRepoCreation3.jpg)
- Step 5: To view the contents of the new repository, use the "dir /ah" command. ![](https://toolsqa.com/wp-content/gallery/git/BareRepoCreation4.jpg)

