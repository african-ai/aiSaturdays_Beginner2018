# AI-Saturdays Nairobi - Beginner
This exerise is designed to assess your programming capabilities.
Submissions received before **Thursday August 2nd 2018** will be considered for the AI-Saturdays 2018 Beginner Track.

### Task 1
Everytime you run the snippet of code below, a new random list, **ourList** of 10 integers between 1 and 10 is generated. Extend the snippet to create a valriable **belowFive** with only the elemets of **ourList** that are below 5.


```sh
import random 

ourList = list()
count = 0 
while (count < 11):
    ourList.append(random.randint(1,10))
    count += 1
    
ourList
```

### Task 2
Everytime you run the snippet of code below, a new random 4-word string, **randomPhrase** is generated. 

```sh
import random

words = [word.rstrip('\n') for word in open('words.txt')]
randomPhrase = " ".join([words[random.randrange(0, len(words))] for i in range(4)])

randomPhrase
```

Extend the snippet to reverse both the order of the 4 words and the order of the letters in each word. Save this in a variable called **reversePhrase**.
eg. 
```sh
band prize boss complex
```
would become:
```sh 
xelpmoc ssob ezirp dnab
```

## Working on the Exercise

1.Fork the code challenge repository provided.

2.Make a topic branch. In your github form, keep the master branch clean. When you create a branch, it essentially will be a copy of the master.

>Pull all changes, make sure your repository is up to date

```sh
$ cd aiSaturdays_Beginner2018
$ git pull origin master
```

>Create a new branch as follows-> git checkout -b [your_email], e.g.

```sh
$ git checkout -b youremail@gmail.com master
```

>See all branches created

```sh
$ git branch
* youremail@gmail.com
  master
```

>Push the new branch to github

```sh
$ git push origin -u youremail@gmail.com
```

3.**Remember to only make changes to the fork!**
    
Edit the **task1** and **task2** .py files in the repository folder and solve the set out exercises. Each file should be concluded with a **print()** statement that prints out the desired result.

eg. 
```sh
print(belowFive)
```
```sh
print(reversePhrase)
```

4.Commit the changes to your fork.

5.Make a pull request to the **aiSaturdays_Beginner2018** Repo.


