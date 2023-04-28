# .github

# MMAG GitHub space

## How can I learn more about GitHub?
### There are many nice free tutorials on getting started with version control and GitHub. See e.g. https://docs.github.com/en/get-started/quickstart/hello-world or just search for another one.

## Are there any dos and don’ts of using this GitHub space?
### Not so much dos and don’ts, but some general advice on how to use it efficiently:
1.	It’s up to you how you organise your space in terms of directory structure, but I would suggest you have a separate folder for each project. To begin with keep them private (which should be the default), but you can make them more widely available in the future if you wish.
2.	Whenever you create a repo (repository), always add some documentation (i.e. a README file) detailing any code/package dependencies for your software, basic instructions for running it etc. This will be useful for others if you share your code at some point, but also for your future self if you need to go back to this code at some point!
3.	Don’t upload large amounts data , otherwise we will run out of space. If you want to upload some data to show how the code can work just upload a small amount of sample data, just enough to show the code working.
4.	To avoid pushing larger files, you can use .gitignore - this is a document where you can add the folder(s) and/or file extension(s) that you don’t want to track. For example, if you add *.nii.gz, it will ignore all files ending in nii.gz. Similarly, you can ignore full folders by adding the folder to the .gitignore file.
5.	If your code reads in data from files, try to use relative file paths, i.e. if your code needs to read in a file called “C:\user\code\my_project\files\text.txt” and your code is in “C:\user\code\my_project\”, just use the relative file path “files\text.txt”. This will make your code more portable. Also try not to use spaces in your file names as some operating systems may not like this.
6.	GitHub will ask you every time to add the user and password by default. If you want, you can store these locally and then it won’t ask every time you commit code: git config --global credential.helper store
7.	Vscode and PyCharm have integrated GitHub - you just need to configure it once and then it will help you to show changes in the code and which files should be committed.
8.	There is also the possibility to make a recurring git push, e.g. once per week.
9.	For more advanced users, you can create branches to work in different projects and then merge them into the main branch. For more documentation see: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches.
