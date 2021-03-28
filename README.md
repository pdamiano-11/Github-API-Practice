## SSW-345 HW4 Submission

In this homework, I took the REST folder and from the REST lab and uploaded the files to this repository. I then
proceeded to change the index.js file to be able to list the branches of a repo, create and also delete a repo,
if that repo already exists, add an issue to a repo, and add a wiki to a repo. I then tested the index.js file
using "node test" and all tests ran perfectly. I also started a server and recorded a screen cast, the file of 
which is in this repo.


# Note: For the create repo test, if the repo already exists, it will return an error 422. I have included a
# method within the create repo function that reads this error and deletes the repo. Simply run 'npm test' again
# to rectify the issue and get 5 passes.