# Creating the repo locally, first commit
 - `git init`
 - `git add README.md`
 - `git commit`

# Creating the repo on GitHub
 - Create GitHub repo
 - Push to GitHub repo
   - `git remote add origin`
   - `git push -u origin master`

# Writing a test
 - We need some code
   - Write simple function to test
 - Write test for function that passes
 - Run with nosetests

# Running tests on Travis
 - Create project on Travis
 - Create `.travis.yml` (see Travis docs)
 - Commit, push
 - See how the test passes
 - Make a breaking change
 - Commit, push 
 - It will break
 - Fix it
 - Important point: When to test and when not to test.

# Using codecov.io
 - Create repo on codecov.io
 - Run tests with `nosetests --coverage`
 - Add magic line to `.travis.yml`
 - Commit, push
 - Important point: Don't make 100% code coverage a goal, it won't solve all your problems.
