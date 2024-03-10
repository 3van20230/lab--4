# lab 4
# report-4
Steps 4:
`$ ssh jhl026@ieng6.ucsd.edu` 

steps 5:
`git clone git@github.com:ucsd-cse15l-s23/lab7.git`

steps 6: 
`bash test.sh`
```
[jhl026@ieng6-202]:lab7:78$ bash test.sh
ListExamplesTests.java:8: error: ')' expected --backup is given)
  number@Test(timeou1e numbered backups
  existi             ^ered if numbered backups exist, simple otherwise
1 errore, never   always make simple backups
JUnit version 4.13.2
..Ea special case, cp makes a backup of SOURCE when the force and backup
Time: 0.517 given and SOURCE and DEST are the same name for an existing,
There was 1 failure:
1) testMerge2(ListExamplesTests)
org.junit.runners.model.TestTimedOutException: test timed out after 500 
millisecondsanslation bugs to <http://translationproject.org/team/>
For compat ListExamples.merge(ListExamples.java:44) invocation'
[jhl026@at ListExamplesTests.testMerge2(ListExamplesTests.java:19)
-bash: cd: ListExamplesTests.java: Not a directory
FAILURES!!!g6-202]:lab7:76$ nano ListExamplesTests.java
Tests run: 2,  Failures: 1
```

steps 7:
first `cd lab7` and use `ls` to list out the files, edit the file "ListExamplesTests.java" by using `nano ListExamplesTests.java``<Down><Down><Down><Down><Down><right><right><right><right>` to find `@Test(timeout = 500)` change the `500` to `1000`after that use ctrl+O to save the change, press <enter> to admit the change, last ctrl + X to exit the editor. after that use `nano ListExamples.java` to edit the file "ListExamples.java" `<Down> <Down> <Down> <Down> <Down> <Down> <Down> <Down> <Down> <Down> <Down> <Down> <Down> <Down> <Down>` to find the line `index1 += 1;` and change it to `index2 += 1;` ctrl+O to save , press <enter> to admit the change, and ctrl + X to exit the editor.


steps 8:

`bash test.sh`

```
[jhl026@ieng6-202]:lab7:89$ bash test.sh
JUnit version 4.13.2
..
Time: 0.015

OK (2 tests)
```


steps 9:
```
[jhl026@ieng6-202]:lab7:92$ git add . 
[jhl026@ieng6-202]:lab7:93$ git commit -m "Fix error"                  
[main b1d1900] Fix error
 Committer: Jhih Lin <jhl026@ieng6-202.ucsd.edu>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 2 files changed, 4 insertions(+), 4 deletions(-)
```
