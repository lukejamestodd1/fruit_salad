# Learn Git by Making a Fruit Salad
### Practice makes perfect
#### Save, add, commit, checkout, merge, push, pull, and repeat


## 1. Cloning the repository

Clone this repository to your projects folder:
```
git clone https://github.com/lukejamestodd1/fruit_salad.git
```


## 2. Adding changes

Add the names of three citrus fruits here:

1. 
2. 
3. 


Save the file, do a git add, and commit your changes. Push your changes to the remote.

```
git add fruit_salad.md
git commit -m "adding citrus fruits"
git push origin master
```


## 3. Creating a new branch

Create a new branch called stone_fruits.

```
git checkout -b stone_fruits
```
Add the names of three stone fruits here:

1. 
2. 
3. 


Save, add and commit your changes, then push the stone_fruits branch to the remote. 


Great! Now we have two branches locally, and two on the remote. 
Your code is up to date with the remote. 
Master should have 3 citrus fruits listed and stone_fruits should have 3 stone fruits.

## 4. Merging branches
Go back to your master branch, and merge stone_fruits into master, and push master back to the remote again.

```
git checkout master
git merge stone_fruits
git push origin master
``` 

Now master should have citrus and stone fruits, on both loacal and remote.


## 5. Adding more branches

Create a new branch called melons, and add three types of melons here:

1. 
2. 
3. 


Push the melons branch to the remote.


Go back to master, create a new branch called berries, and add three types of berries here:

1. 
2. 
3. 


Push berries to the remote

## 6. Pull requests

Go to the remote repository. Create a pull request to merge melons into Master. Approve it and merge.
Do the same for berries.

On your local, swap back to the Master branch.

Pull the latest changes from the remote

```
git pull origin master
```
Your master branch should now have citrus, stone fruits, melons and berries.

## 7. Resolving conflicts

From master, create a new branch called tropical_fruits, and add three types of tropical fruit here:

1. 
2. 
3. 


Push tropical_fruits branch to the remote.

Go back to master and pull the latest changes. 

The last task is to make sure master has all the fruits listed above, and no vegetables!









