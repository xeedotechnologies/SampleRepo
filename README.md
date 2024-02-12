## Let's get started

1) To verify if  git is been installed successfully with ```git --version``` command
   
![image](https://github.com/xeedotechnologies/SampleRepo/assets/159549820/612acc38-afa9-40ce-8aa0-932528cb7651)

2) **Set Username:** ``` git config --global user.name "Your Name" ``` 
The `--global` flag makes this configuration apply globally to all your Git repositories.

3) **Set Email:** ```git config --global user.email "your.email@example.com"```

![image](https://github.com/xeedotechnologies/SampleRepo/assets/159549820/d1a35d97-83c2-44c2-85d3-a1c854cfa5da)

## Step-by-step guide on how to clone a repository to your local machine, make changes, and push those changes back to the remote repository:

1)  **Clone the Repository:** ```git clone <repository_url>```
    Replace <repository_url> with the URL of the repository you want to clone. This creates a local copy of the repository on your machine.

![image](https://github.com/xeedotechnologies/SampleRepo/assets/159549820/631bc579-3485-440f-8568-48d986e30015)

2) **Navigate to the Cloned Repository:** ```cd <repository_directory>```
   Change into the directory that was created when you cloned the repository.

![image](https://github.com/xeedotechnologies/SampleRepo/assets/159549820/55b8cb0e-52cc-4a2c-9dd5-5d38de01fe5c)

3) **Create a Branch:**
 ```
git branch <branch_name>
git checkout <branch_name>
```
  Create a new branch to work on your changes. The second command switches to the newly created branch.

4) **Make Changes:**
   Modify the files in your local repository according to your requirements.

5) **Check the Status:** ```git status```
   Check the status of your working directory and see which files are modified or untracked

![image](https://github.com/xeedotechnologies/SampleRepo/assets/159549820/284801e7-8210-451f-a635-bd241685b4d7)

6) **Add and Commit Changes:**
```
git add .
git commit -m "Your descriptive commit message"
```
  Stage and commit your changes. The commit message should describe the purpose of your changes.

![image](https://github.com/xeedotechnologies/SampleRepo/assets/159549820/0ea01009-9530-4683-ba97-d90eb8a1f49d)

6) **Push Changes to Remote Repository:** ```git push origin <branch_name>```
  Push your changes to the remote repository on the branch you created.

![image](https://github.com/xeedotechnologies/SampleRepo/assets/159549820/252031b0-4ffd-4990-937f-d12c525fd1f5)

##  The steps to create a local repository, make your initial commit, and push it to GitHub:

1) **Initialize a Local Repository:**
  Open your terminal or command prompt and navigate to the directory where you want to create your project. Then, run the following command:
```git init```

![image](https://github.com/xeedotechnologies/SampleRepo/assets/159549820/54b41bff-5d5e-460b-bd64-710d46c9e2c9)

3) **Create and Add Files:**
  Create some files in your project directory and add them to the staging area.
``` git add . ```

![image](https://github.com/xeedotechnologies/SampleRepo/assets/159549820/2c7f4d84-5aac-41b7-9d52-492e9debe554)

4) **Commit the Changes:** ```git commit -m "Initial commit"```
  This commits the changes you added to the staging area with a descriptive message.

![image](https://github.com/xeedotechnologies/SampleRepo/assets/159549820/67f19f19-b468-4bb9-8244-2563ef7ed5e2)

5) **Create a New Repository on GitHub:**

- Go to GitHub and log in.
- Click on the "+" icon in the top right corner and select "New repository."
- Fill in the repository name, description, and other settings.
- Click on "Create repository."

5) **Link Local Repository to GitHub Repository:**
  Back in your terminal, set the remote origin to your GitHub repository by replacing <username> and <repository> with your GitHub username and repository name:
```git remote add origin https://github.com/<username>/<repository>.git```

![image](https://github.com/xeedotechnologies/SampleRepo/assets/159549820/e77b0e21-c9cf-460c-ba5a-920f8a208ec2)

6) **Push to GitHub:**
   ```git push -u origin master```
  This pushes your local commits to the GitHub repository. The -u flag sets up tracking, so in the future, you can simply use git push without specifying the branch.

![image](https://github.com/xeedotechnologies/SampleRepo/assets/159549820/ae1a9e3a-a5c6-4a6f-91c7-f6470a99fa18)
