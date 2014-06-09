######Before you read this
You should probably know that this is a experimental project, that means this is not going to be safe and was unofficial.

#Introduction
##What is this?
This is a community-made OpenShift Cartridge repository that utilized [GitBucket](https://github.com/takezoe/gitbucket), a very early but potenial GitHub clone written in Scala. By deploying this, you could have granted yourself a instant, powerful and free Git hosting on the giant OpenShift cloud.

##How to deploy this?
There are multiple methods to achive this, however in this section I'd only tell you the simplest method to do so:

1. 
   Create a free OpenShift Account by clickin [here](https://www.openshift.com/app/account/new)
2.
   After signing up, you should go to the application console, and select "Add Application..."
3. 
   In the application creation wizard, drag your browser to the bottom, and click on "Do-It-Yourself 0.1"
4.
   You should only change the field "Source Code" to "https://github.com/katetem/openshift-community-cartridge-gitbucket" and        branch name should be "master", everything else should be customized by you.
5. 
   After all, click on "Create Application", and you will have a free Git hosting, in only or less than 60 seconds.

#####PS. The defaulting administraive user is root, while the password is also set as "root", you should change your password as soon as    possible after successfully deployed your GitBucket repository.

#Credits
* [OpenShift](https://www.openshift.com/) for his amazing online PaaS hosting.
* [GitBucket](https://github.com/takezoe/gitbucket) for a great interface and the ease of setting up.
* You for reading this all over.
