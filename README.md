# Creating Your Own Website 

## Section A: Setting up your work environment  
1. Download VS Code from the following link https://code.visualstudio.com/download 
2. Download Git Bash from the following link https://git-scm.com/downloads 
3. Create a Github account https://github.com/ 
4. Create a CodePen account https://codepen.io/ 
5. Create a Netlify account https://www.netlify.com/ 

## Section B: Creating your own Github Repository 
1. Click on the *+* button on the top right corner of the navigation bar and then on *New Repository* in the drop down menu
2. Name your repository *ECE5_TEAM-NAME* 
3. Make sure it is set as a public repository
4. Click on *New Repository*
5. Now that your repository is created, click on *import code from another repository**
6. In this repository click on the green *Code* button and copy the link 
8. In the input bar paste the link then hit enter

## Section C: Downloading code from github using VS Code and Git Bash
1. Open VS Code > *Terminal* > *New Terminal* 
2. Drop down menu to make sure the terminal is using Git Bash 
3. Commands to know (navigating directories): ** 
 > - **cd ..** takes you back one directory
 > - **ls** lists the files in the current directory 
 > - **cd (file name)** > tab takes you to the listed file
4. Using the above commands navigate to the directory you wish to store the files in
5. Commands to know (downloading files from Github):
 > - **git clone (paste YOUR github repository link here)**
7. Using the above line of code copy your repository’s link from the green *Code* button and clone it in the VS Code terminal 
8. Check to see that the files have been downloaded in your chosen directory

## Section D: Editing the code using VS Code and CodePen
1. Navigate to where you cloned the Github repository and open the file (it should be named ECE5_INITIALS_SKETCHBOOK)
2. Open your CodePen account and create a new pen by clicking on *pen* in the sidebar
3. Right click the *index.html* file > *Open with Code* 
4. Select all > Copy code and then paste it under the *html* section in CodePen
5. Right click the *style.css* file > *Open with Code* 
6. Select all > Copy code and then paste it under the css section in CodePen
7. Now you are all set to edit your code. Doing so in CodePen helps you see the changes you are making and how they would translate to your website.
8. Once you are done editing your code and like how it looks, copy the code in the *html* section in CodePen and paste it in your *index.html* file in VS Code and save changes
9. Copy the code in the *css* section in CodePen and paste it in your *style.css* file in VS Code and save changes

> **Note: Steps to upload your own images (not images you get online)**
> - Upload your image to google photos https://photos.google.com/ 
> - Use https://www.labnol.org/embed/google/photos/ to generate image link/ html embed code

## Section E: Uploading your code to your Github Repository 
1. Navigate to your *ECE5_TEAM-NAME* directory using the terminal commands
2. One you are in the directory you should see (master) next to the directory name
3. Commands to know (uploading files):
 > - **git status** shows you the status of your files compared to your Github repository
 > - **git add .** adds the changes you have made to the files
 > - **git commit -m"commit name"** saves the changes to a certain commit
 > - **git push** pushes the changes to your Github repository
4. Using the above commands push the changes you have made to your Github repository

## Section F: Hosting your website on Netlify
1. Create a Netlify account and log in
2. Click on *New site from Git* > *Github*
3. Select your *ECE5_TEAM-NAME* repository 
4. Make sure the branch to deploy is master
5. Click on *Deploy site* 

## Congratulations! Now Your Website Is Hosted!

