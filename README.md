# reading-notes
_**My reading journal for 102d45 (CodeFellows)**_

#*Hi my name is Todd Rutherford and I love to program!*#

Growth mindset means to me...

3 Reminders to stay in Growth Mindset:

  1. Be very deligent in the art of learning! 
  2. Be very persistant in adversifying when coming across obstacles throughout the learning process.  
  3. Stay inspired and driven to achieve your learning goals and career goals.  
  
Here's a link to my portfolio: [toddrutherfordworld] (https://toddrutherfordworld.github.io/reading-notes/)



[Class 1](https://github.com/toddrutherfordworld/reading-notes/blob/main/class1.md)



[Class 2](https://github.com/toddrutherfordworld/reading-notes/blob/main/class2)


# Code 102 Reading Note

# Code 201 Reading Notes


## Things I want to know more about. 

#Merging
When you want to merge changes from one branch into your current one, you can use the git merge command.

#Fast-Forward Merging

With a fast-forward merge, your current branch’s pointer moves forward to the most recent commit for the branch being merged in – there is no divergent work to merge together because the latter branch is directly upstream in relation to the former one.

Example:

$ git checkout master (switches you to the master branch)

$ git merge test (merges in changes from test branch)

Updating c58d775 .. 8b9205d

Fast-forward

index.html| 4 ++

1 file changed, 4 insertions(+)

![Git Merging PNG ](https://blog.udemy.com/wp-content/uploads/2015/08/image054.png)


# Three-way Merge
In cases of branches diverging, fast-forward merges are not an option. A three-way merge can be used, however. This type of merge involves the two latest commit snapshots pointed to by both branches, and their common ancestor. Here is an example of creating a three-way merge:

$ git checkout master

$ git merge test

![Three Way Merge](https://blog.udemy.com/wp-content/uploads/2015/08/image075.png)

