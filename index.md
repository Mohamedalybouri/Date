# ***Git presentation***
This presentation is a summary of the most used git commands.


# ***Planning***
- VCS
- GIT
- Git branch
- Fork
- Diferrence between fork and branch
- Advantages and disadvantages of using Git


<!-- When you take a look at the defenition in google of git you will see that -->
<!-- But What is VCS -->
Git is a version Control system (VCS)
    **What is version Control system?**


# ***VCS***
* A system that tracks changes to a file or set of files over time
* Sharing on multiple computers
* Logging where be changed
* If you screw things up or lose files, you can easily recover 


# ***Types of VCS***

There are 3 types of VCS:
1. Local Version Control System 
2. Centralized Version Control System
3. Distributed Version Control System


## **_Local Version Control System_**
<!-- example Skype -->
![w:980](https://cdn.shortpixel.ai/spai/w_738+q_glossy+ret_img+to_webp/https://serengetitech.com/wp-content/uploads/2020/12/local-version-control.png)


* +This approach is very common and simple
* -The chances of accidentally writing to the wrong file is higher


## **_Centralized Version Control System_**

![w:980](https://cdn.shortpixel.ai/spai/w_738+q_glossy+ret_img+to_webp/https://serengetitech.com/wp-content/uploads/2020/12/Centralized-Version-Control-System.png)


example: SVN
![w:800](data:image/png;base64,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)


* +Relatively easy to set up
* +Enable admins control the workflow
<!-- Disadvantages -->
<!-- 1/If the main server goes down -->
* -Developers can’t save versioned changes
* -Remote commits are slow
<!-- 3/If the central database is corrupted -->
* -The entire history could be lost (security issues)


### **Distributed Version Control System**
![w:800](https://cdn.shortpixel.ai/spai/w_738+q_glossy+ret_img+to_webp/https://serengetitech.com/wp-content/uploads/2020/12/distributed-version-control.png)


example: GIT 
![w:800](gitgithub%20-%20Copie.png)


<!-- Ther are 3 version control software are the best which are: -->
## _The best version control software_
![w:1210](VCS.png)


<!-- In this table we can see the devolpere of different of verrsion control software -->
<style scoped>
table {
    height: 100%;
    width: 100%;
    font-size: 50px;
    color: black;
}
th {
    color: red;
}
</style>
|***2015***                   |***2018***                   |
|:---------------------------:|:---------------------------:|
|Git: 69.3%                   |Git: 88.4%                   |
|Subervsion: 36.9%            |Subervsion: 16.6%            |
|Team Foundation: 12.2%       |Team Foundation: 11.3%       |
|Mercurial: 7.9%              |Mercurial: 3.7%              |


![w:1200](Gitpng.png)


# ***Git*** is: 
<!-- 1/With open-source, it means that it is a system for which the source code is freely and easily available. This source code is the original one which can be further modified-->
* Open-Source System
<!-- 2/Firstly, it is present on the server. Secondly, it can be taken from the developer’s computer. This means that the repository is present in a distributed network apart from the central server-->
* Distributed System
<!-- 3/it means that it is linked with a tracking system -->
* Control System
 <!-- 4/Whenever more and more code is added to the folder, the code present in the Git folder gets changed.-->
* Version Controlled


* Using online hosts such as *`GitHub`* or *`Bitbucket`* to store a copy of the files and their revision history
* Merging the changes


![w:1250](image0.png)


![w:1200](image1.png)


<!-- Git has 3 main states that your file can reside in -->
### *The main states:*
* Modified
* Staged
* Committed


<!-- Git has 4 main code which are represented in this cercal-->
### *Most popular command in Git*
![w:1100](image3.png)


<!-- The basic steps on Git to push the project into an online host -->
### **The basic steps on Git:**

    $ git init                    (1)
    $ git add .                   (2)
    $ git commit                  (3)
    $ git remote add <name> <url> (4)
    $ git push -u <name>          (5)(6)
    $ git pull                    (6)(5)
    

### **Git add**
    - git add <path>
    - git add .
    - git add -A
    
Selects file(s) and moves it to the straging area


### **Git push**
Git push command is used to upload content from a local repository to a remote repository


### **Git commit**
![w:1200](image2.png)


# ***Git branch***

![w:1000](image9.png)


### **Commands related to branch**
    $ git branch 
    $ git checkout
    $ git clone
    $ git merge <branch name>


### **Git checkout**
<!--Switch the branch-->
![h:610](Image22.png)


### **Git clone**
![w:1000 h:580](Image18.png)


![w:980 h:260](image19.png)
![w:980 h:460](image20.png)


### **Git merge**
![w:1180 h:560](Image27.png)


![w:1200](Image25.png)


# Fork
<!-- There is another solution to work in group in git which is Fork -->
* Can make changes to a project without affecting the original repository
* Can submit changes to the original repository with pull requests.


# ***Diferrence between fork and branch***
<!-- Every one now may ask me what is the differenc between Fork and branch well: -->
<!-- because there we can make a Close communication -->
<!-- "Make an exemple of working in a small group but we trust each other" -->
#### *Branch :*
* Small group of programers who trust each other 
* Close communication
* Give the development organization write access to a repository.
* Rapid iteration cycle.

<!-- "Change the exemple but in this time the groupe desn't trust each othre" -->
<!-- But, imagine that you are working in groupe and there is some one who would like to modify some files in your main project (master branch) That's why we should find a solution that we can stop this guy Well there is another solution which is Fork. Well Fork can-->
#### *Fork:*
* You don't want to manage user access on your repository
* You want fine-grain control over merging
* You expressly want to support independent branches
* You want to discard experiments and changes easily

# ***Advantages of using Git***
* Fast Processing
* Flexible
* Easy Merging

# ***Disadvantages of using Git***
* Not Suitable for Binary Files
* No Sub-Trees Checkout Possible

# ***Thank You for your attention*** 
