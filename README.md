# COMP3310 
## Week 01 - Fundamentals
An empty repo to start.

You should clone this repository, create an intial gradle project, and push it. 

- enrol in git classroom using email link
- clone classroom repo locally
- install VS studio Code
->  - install extensions
    ->   - Extension Pack for Java
         - SonarLint
         - Gradle Extension Pack
         - GitHub Pull Requests and Issues

- setup gradle by dloading and extracting zip to C:Gradle
- add Gradle bin path to ENV Variable
- create gradle project 

 in win cmdline or Powershell

         #  $c:\  cd C:\Users\jlore\Documents\GitHub\workshop-1-secure-hello-world-name
         #  PS    cd C:\Users\jlore\Documents\GitHub\workshop-1-secure-hello-world-name>

 Useful commands:

         # gradle --help  ( for commands)
         # gradle --tasks ( for list of tasks and commands)


  In VS Code
         -  Go to Project exporer and select option to " Create Java Project " 
         -  Select the " Gradle " drop down option   
         -  Select folder with Git repo
         -  Select " groovy " option & Choose Project Name ( Initial project created)
         -  In cmdline or Git bash make file    " gradlew "      executable

   run      #    git update-index chmod=+x gradlew   ,   or select properties of file and rename with .exe


   Open Cmmdline, or Git_Bash, or Powershell ( your choice )     and CD to new Project location                                
       
         - in Terminal run :
                #   gradle init      // to start interactive terminal,
                #    select 2 ;  'application',
                #    select 3 ;  'Java'  ,
                #    select 1 ;  ' no'  - only one application,
                #    select 1 ;  'Groovy',
                #    type    'yes'    build using APIs,
                #    select 1 ;  'JUnit 4'  ,

  In Git Bash, Git Desktop or VS code  " PUSH " changes to master 

          -  In same terminal above run;
                #    gradle status,
                #    gradle build 
                #    gradle run
                #    gradle test
             

See the workshop manual for details.
