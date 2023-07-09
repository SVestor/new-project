### Setting Up New Git Repository and Creating Development Branch for 'new-project'

### Instruction

Follow these steps to set up the new Git repository and create the development branch for 'new-project':

1.  Open GitHub in your web browser and sign in to your account.
    
2.  Click on the "+" icon in the top right corner of the screen and select "New repository" from the dropdown menu.
    
3.  In the "Repository name" field, enter "new-project" (without quotes) as the name for your repository.
    
4.  Optionally, provide a description for the repository in the "Description" field.
    
5.  Choose the visibility of the repository. You can select either "Public" or "Private" depending on your needs.
    
6.  Initialize the repository with a README file by selecting the checkbox next to "Initialize this repository with a README".
    
7.  Click on the "Create repository" button to create the new repository.
    
8.  Once the repository is created, you will be redirected to its main page. Click on the "Code" tab, and copy the repository URL.
    
9.  Open your preferred command-line interface (CLI) or terminal on your local machine.
    
10.  Navigate to the directory where you want to clone the repository using the `cd` command. For example, `cd Documents/Projects/`.
    
11.  Clone the repository to your local machine by running the following command:

    `git clone <repository-url>` 
    
Replace `<repository-url>` with the URL you copied in step 8. This will create a local copy of the repository.

12.  Change to the repository directory using the `cd` command. For example, `cd new-project/`.
    
13.  Create a new branch named "development" using the following command:

    `git branch development` 
    
This will create a new branch based on the current branch (usually "main").

14.  Switch to the "development" branch by running the command:
 
    `git checkout development` 

As one of the additional options, you can also use the  `git checkout -b development`  command
This option will create a new branch "development" and switch to it automatically

You are now on the "development" branch and ready to work on new features.

15.  Create a new file called "README.md" using your preferred text editor and add the step-by-step instructions to it. Save the file.
    
16.  Add the changes to the "development" branch by running the following command:
    
    `git add README.md` 
    
17.  Commit the changes with a descriptive commit message using the command
    
    `git commit -m "Add step-by-step instructions to README.md"` 
    
18.  Push the changes to the remote repository using the command:
    
    `git push origin development` 
    
19.  Once you have completed working on the new features in the "development" branch and are ready to merge them into the "main" branch, follow these steps:
    
    -   Checkout the "main" branch by running the command:
        
        `git checkout main` 
        
    -   Merge the changes from the "development" branch into the "main" branch using the command
        
        `git merge development` 
        
    -   Resolve any merge conflicts that may occur. If conflicts arise, carefully review the conflicting files, make the necessary changes, and commit the resolved changes.
        
    -   Push the merged changes to the remote repository
        
        `git push origin main` 
      
*Congratulations! You have successfully set up a new Git repository for 'your-project'*