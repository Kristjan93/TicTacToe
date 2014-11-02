# Administrator Manual

### How to set it up and get it to run

Check the Development Manual to get the project to build on your fresh machine

```
1. Create a new branch
        - command: git checkout -b <my-branch>
```
```
2. Make changes
        - make a change in code
```
```
3. Check the changes you have made
        - command: git status
```
```
4. Commit your changes
        - command: git add <changes-you-want-to-be-added>
        - command: git commit -m "my comment"
```
```
5. Push your branch to Github
        - command: git push -u <my-branch>
```
```
6. Merge the branch to your local master
        - command: git checkout master
        - command: git merge <my-branch>
```
```
7. Push the changes to Github
        - command: git push origin master
```

By pushing your changes to Github it will be automaticly deployed to Travis and Heroku if all tests are passed

