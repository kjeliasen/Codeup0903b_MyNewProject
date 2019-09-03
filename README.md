This is the Readme for my-new-project
https://ds.codeup.com/appendix/git/

Initial Repository Setup
Create a new project and initialize a repository

mkdir my-new-project
cd my-new-project
git init
Create a repository on Github and add the remote to your project

git remote add origin REMOTE_URL
Where REMOTE_URL is the url obtained from Github after creating a repo.

Create a README.md file with a short description of the project, and add and commit it

After creating the readme file:

git add README.md
git commit -m 'Initial Commit'
Push your changes

git push origin master
After pushing, visit Github and verify that you can see the README.md file that you created.
