# Installation
  1. Check if Git is already installed by opening the terminal and typing "$git --version" or "$which git".
  1. If there is no answer, then it means you need to install git.
  1. Download and install git from : https://git-scm.com/download. (You could use homebrew instead.)
  1. Sign up and create an account on Github.com. remember your user name and email you used.
  1. add your github email and username to git by typeing on the terminal :<br />
    $git config --global user.email "kimirene01@gmail.com"<br />
    $git config --global user.name "irenekim"<br />
# Using Git
  1. First, clone the repository to a local folder : goto your local folder and type : <br />
    $git clone https://github.com/irenekim/RTG_proteomics
  1. Now, you can either edit an existing file in the cloned folder at your local machine, or add a file to the folder. <br />
    Let's call the two file's name that were either edited or added "file1.txt", "file2.txt".
  1. To sync the repository with your updates, we first add the files that needs attention.<br />
    $git add file1.txt   will add one file,<br />
    $git add .           will add all modifications.<br />
  1. Now commit the changes so Git takes a snapshot of the update and save it the history.<br />
    $git commit -m "first commit"<br />
    multiple commits can be done.<br />
  1. Finally, sync the current snapshot with the git repository.<br />
    $git push 
# Using git with Github Desktop
  1. Install Github Desktop from https://desktop.github.com/
  1. Clone the repository using file > clone repository
  1. Once you edit a file or change the contents of the folder, Github desktop will catch them under Changes on the left bar.
  1. Choose the changes that you want to update by clicking the boxes under Changes. This corresponds to<br /> 
  $git add < file name >
  1. Write a summary and description if needed, then click commit to master at the bottom left. This corresponds to<br /> 
  $git commit -m "messege"
  1. Click the publish on the top right. This corresponds to<br /> 
  $git push 


