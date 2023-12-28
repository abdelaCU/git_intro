### DSI: Unix Shell, Git and GitHub

## Assignment 2 & Quiz: Git and GitHub

### Part 1

Part 1 of Assignment 2 is a quiz. Please complete to the best of your ability. Notes are permitted. Please email your responses to the TA with Instructor CC'd.

1. Check all that are TRUE about version control:

   - [x] Can revert files to a previous state
   - [x] Can compare changes over time
   - [x] Can see who modified something last
   - [x] Can recover lost files

2. What is the difference between centralized version control systems and distributed version control systems?

```
Centralized systems have a single repository, are network-dependent, and often use a checkout/commit model. Distributed systems have full repositories locally, allow decentralized collaboration, and support flexible workflows. Git is a popular example of a distributed version control system

```

3. What are the three states that files can reside in?

   - [ ] a) committed, changed, waiting
   - [ ] b) saved, changed, staged
   - [x] **c)** committed, modified, staged
   - [ ] d) saved, modified, staged

4. What command initializes a new repository?

   - [ ] a) `git clone`
   - [ ] b) `git branch`
   - [ ] c) `git fork`
   - [x] **d)** `git init`

5. What does `git diff` do?

   - [ ] a) compares the differences between the home directory and staging area
   - [x] **b)** compares the differences between the working directory and staging area
   - [ ] c) compares the differences between the working directory and what’s been committed
   - [ ] d) compares the differences between the staging area and what’s been committed

6. How do you add a message to your commit? (select all that apply)

   - [x] **a)** `git commit -m`
   - [ ] b) `git commit --messages`
   - [x] **c)** `git commit`
   - [ ] d) `git commit -message`

7. How do you add a remote repo? (select all that apply)

   - [x] **a)** `git remote add`
   - [ ] b) `git add remote`
   - [ ] c) `git clone`
   - [ ] d) `git add clone`

8. How do you add a remote repo? (select all that apply)

   - [x] **a)** `git remote`
   - [ ] b) `git add remote`
   - [ ] c) `git clone`
   - [ ] d) `git add clone`

9. What is the difference between `git pull` and `git fetch`?

```
***git pull:***
Fetches and merges changes from a remote repository into the current branch in one step.
Quick and convenient, but may result in automatic merges.

***git fetch:***
Fetches changes from a remote repository but does not automatically merge.
Updates remote-tracking branches, allowing you to review changes before merging.
Provides more control over the process
```

9. How do you switch branches?

   - [x] ***a)*** `git checkout`
   - [ ] b) `git checkout -b`
   - [ ] c) `git branch -c`
   - [ ] d) `git branch`

10. Why are messages important? What would make a good commit message?

```
Commit messages in version control systems like git are crucial show collaborators easily what has been done.

```

11. Please correct the merge shown below (both codes are suitable, neither has errors):


```
<<<<<<< HEAD
df.loc[df['sex'] == 'f', 'age'].mean()
======
df.loc[df['sex'] == 'm', 'age'].mean()
>>>>>>> branch_1
```

```
df.loc[df['sex'] == 'f', 'age'].mean()
df.loc[df['sex'] == 'm', 'age'].mean()

``
