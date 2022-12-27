# IaC-Repo
Using AWS Code Pipeline deploy CloudFormation Template 

What is Git ? 
  1. Git is a software and it is a command line tool .
  2. Git is a free and open source version contorl system used to handle small to large projects efficiently . 
  3. Git is an open-source licensed .
  4. Git is maintained by Linux .
  5. Git is used to track changes in the source code, enable multiple developers to work together .
  6. Git is a tool that facilitates the source code management in software developement .
  7. Git provides functionalities like Version Control System and Source Code Management .
  8. A version control system helps you document and store 
 
    
Git Commands : 

1. git init : This git command is used to create a new local repository (creates a .git repository ->It will initialize the project folder into a git repo) 

2. git status : This git command will show you exactly which file and folder have been modified ( list new (untracked) and unmodified (tracked) files )

3. git add <file> or git add . : 
       1. Use the git add command to move files from the working directory to the staging index .
       2. Use the git add command stores your modification to the staging area in a file . 
       3. This git add command is used to add your new or updated files from the working directory to the staging area before committing it .( Stage all 
          changed files and stage a file )
          
4. git commit : 
       1. This git command records a log message as well as commit id of the git repository's modifications .
       2. with git commit, you can save your changes to your local repository .
       3. Every time you commit code changes, you must include a concise summary of the changes. This commit message assist others in understanding the 
          changes that have been made .

5. git pull : This git command is used to pull all your updated code from the remote repository and merge it with the local branch . 

6. git push : 
        1. This git command is used to upload local repository content to a remote repository .
        2. It will push all your updates or local changes that you have made in your local repository to the remote repository . 

7. git branch 


What is AWS CloudFormation ? 

  1. AWS CloudFormation is a service that helps you model and set up AWS resources so that you can spend less time 
     managing those AWS resources and more time focusing on your applications that run in AWS Cloud .
  
  2. You create a template that describes all the AWS resources that you want like Amazon EC2 instance, Amazon RDS DB instance and so 
     on . 

  3. CloudFormation takes care of provisioning and configuring those AWS resources for you . You don't need to individually 
     create and configure AWS resources and figure out what's dependent on what, CloudFormation handels that . 
  
  4. When you use AWS CloudFormation, you work with two things 'templates' and 'stacks' . You create templates to describe your AWS 
     resources and their properties . Whenever you create a stack, CloudFormation provisions the resources that are desrcibed in your template . 

AWS CloudFormation Template : 

  1. A CloudFormation template is a JSON or YAML formatted text file. You can save these files with any extension, such as .json, 
     .yaml, .txt, or .template . 

  2. CloudFormation uses these templates as a blueprint for building AWS resources .
