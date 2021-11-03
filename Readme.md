# Github Branch Lab

Some Notes:
* Steps 1 should only be done once by the project lead.
* Steps 2-4 done by contributors/teammates.
* Steps 5-10 should be done by both project lead and contributors/teammates.
* Steps 11 should only be done once by the project lead.
* Steps 12 should be done by both project lead and contributors/teammates.

## The leader of the group should do the following: 
1.  Create a new repository.

</br>

5. Create and checkout to a new feature branch
    - `git checkout -b Feature_Name`
6. Add html file that has `<h1>Hello from YOUR_NAME</h1>`
7. Add your work to the staging area `git add .`
8. Save the staged changes via commit `git commit -m “”`
9. Push the new branch to origin g`it push -u origin Feature_Name`
10. Submit pull request
11. merge the changes
12. Update the local master by pulling changes from Upstream master `pull origin master`

## The other memebrs should do the following:
2. Fork
3. Clone `git clone FORKED_REPO_URL`
4. Add upstream as a remote repository
   - `git remote -v `
   - `git remote add upstream Original_URL` (Original_URL = The leader repo link)
   - `git remote -v` you should see 2 origin and 2 upstream remotes 
5. Create and checkout to a new feature branch
    - `git checkout -b Feature_Name`
6. Add html file that has `<h1>Hello from YOUR_NAME</h1>`
7. Add your work to the staging area `git add .`
8. Save the staged changes via commit `git commit -m “”`
9. Push the new branch to origin g`it push -u origin Feature_Name`
10. Submit pull request

</br>

12. Update the local master by pulling changes from Upstream master `pull upstream master`