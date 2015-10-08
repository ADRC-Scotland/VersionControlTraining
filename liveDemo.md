#

1. Clone training repository  
```
https://github.com/ADRC-Scotland/VersionControlTraining.git
```
1. Change into directory and show that there are no changes  
```
cd VersionControlTraining
git status
```
1. Edit helloWorld.do file, add punctuation
1. Show that there is now a changed file
```
git status
```
1. Show the difference in the file
```
git diff helloWorld.do
```
1. Stage file
```
git add helloWorld.do
```
1. Show the change in the status
```
git status
```
1. Commit the changes, note that we are prompted for a message
```
git commit
```
1. Show status, highlight that we are now ahead of the remote
```
git status
```
1. Push the results to remote
```
git push
```
1. Show change in status
```
git status
```
1. Look at repository on [GitHub](https://github.com/ADRC-Scotland/VersionControlTraining)
