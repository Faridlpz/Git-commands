# Git-commands and Kubernetes app
In this repository, I'll be practicing git commands and following its strategies in order to have a better knowledge of its use. Besides, I'll be using Kubernetes for creating some resources, which are: Pods, Deployments, Services, Ingress, Secrets, and CofigMap, and including backend, frontend, and database apps.

Lets start by using Git

Some commands used in Git and then Kubernetes:
1. show
2. add
3. status 
4. push
5. pull 


# kubernetes

Commands used more frequently in kubernetes.
1. apply -f + manifest.yaml
2. delete f 
3. get pods
4. get svc
5. get deployments 

This image below depicts my architecture as created via kubernetes.
# Architecture of my app
![alt text](architecture.png)

Finally, I'll change Pod objects to Deployment to have replicas of my pod. What this means is that if one Pod fails, another takes its position. Therefore, the Deployment object is better and helps us modify our image without deleting it, as well as the service was added to the Deployment manifest to follow best practices.

---

Continouing to practice with Git there is a folder called ./git inside of which you'll find folders and files that make up the git reposity.

First of all, lets start by talking about add, status, push and pull common commands of Git.

So, starting off, I'm going to be using add. 


## Git common commands
**git add ./file/folder** is used to upload your changes to the staging area.

**git reset HEAD "file"** is used when your file is in a staging area and you need to get the file back to your working directory.

**git status**

we use git status to verify if we have any new changes to upload.

**git commit**

we use git commit to add a comment to our change.


**git push**

we use git push to upload our new changes to our gitrepository. The file will be send from our local to the repository

**git pull**



**.gitignore**

We use gitignore to avoid uploading any files that you don't need to have.

for example:

* Specific file: myfile.txt
* File pattern: *.txt
* folder: my-folder/