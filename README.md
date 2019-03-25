# Java IV Spring IoC Labs

Spring Inversion of Control (IoC) configuration labs

## Objective

This repository has three labs:
1. Configuring Spring with XML located in the [xml-config](xml-config) directory
1. Configuring Spring with Java located in the [java-config](java-config) directory
1. Configuring Spring with annotations located in the [annotation-config](annotation-config) directory

For each of the three labs:
* Find the JUnit Test provided which is located under ``src/test/java/edu/cscc/java4/spring/ioc/config/``
* One by one, uncomment each test, changing just enough code or configuration to
make the test pass

## Getting Started:

This repo is actually 3 projects in one which confuses IntelliJ after you checkout the starter code. To avoid confusion we will use the command line for our initial Git operations.

Open a terminal and perform the following steps:

1. If you don't have a "labs" directory, create one: ``mkdir ~/labs``
1. Change to the labs directory: ``cd ~/labs``
1. Clone this repository: ``git clone https://github.com/jeff-anderson-cscc/java4-labs-spring-ioc.git``
1. Change to the top directory for the lab: ``cd java4-labs-spring-ioc``
1. Unlink it from the starter repository: ``git remote rm origin``
1. Create a new, private repository in GitHub using [these procedures](https://help.github.com/en/articles/creating-a-new-repository)
1. Once your repository is created, copy the commands shown in the **or push an existing repository from the command line** section shown in the "Code" tab of your new repository
1. Paste the commands from the step above into the terminal supplying your GitHub user name and password when prompted
1. Verify the push works by looking for output similar to the following:
```
Counting objects: 88, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (56/56), done.
Writing objects: 100% (88/88), 11.59 KiB | 2.90 MiB/s, done.
Total 88 (delta 22), reused 0 (delta 0)
remote: Resolving deltas: 100% (22/22), done.
To https://github.com/jeffrey-anderson/ioc-labs.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
[CORP\andersja@a-2aj985axc5pyu java4-labs-spring-ioc]$
```
1. Create a new branch changes you will make in this lab: ``git checkout -b code-changes-for-lab`` which should produce the following message:
```
Switched to a new branch 'code-changes-for-lab'
```

**NOTE:** For simplicity, do a commit after each lab below but keep all your work on this one branch.

## Completing the Assignment

__Important__ You will want to create a separate IntelliJ project for each of the three subdirectories.
Also, you may not change the code in any test cases. _The only permissible difference between the base version of each JUnit test class and yours is yours will have no tests commented out and the file is otherwise identical._

### XML-based Configuration Lab
1. Start IntelliJ and, if necessary, close the last project you had open
1. Choose "Open" from the IntelliJ IDEA welcome screen
1. From the file navigator, choose ``xml-config`` under ``labs/java4-labs-spring-ioc``
1. Press OK so the project will open and IntelliJ will import it
1. __NOTE:__ The Community edition doesn't automatically configure all Spring artifacts so, if necessary, create a "resources" directory under ``src/main``
1. Open ``XmlConfigTests`` in the editor
1. Move the /* -- top block comment line to below the first Test
1. Right click in the editor window and choose "Run XmlConfigTests"
1. Change just enough code / configuration to make that test pass
1. Repeat the last 3 steps until every test method runs without error

Once you are done, commit your changes using "VCS" -> "Commit":
* Make sure the commit includes any new files you created
* Enter a proper comment
* Uncheck "Perform code analysis"

Finally, Choose "File" -> "Close Project" before starting on the next lab

### Java-based Configuration Lab
1. Choose "Open" from the IntelliJ IDEA welcome screen
1. From the file navigator, choose ``java-config`` under ``labs/java4-labs-spring-ioc``
1. Press OK so the project will open and IntelliJ will import it
1. Repeat the process you followed in the previous lab using tests defined in
``JavaConfigTests``
1. Commit your changes
1. Close the Project

### Annotation-based Configuration Lab
1. Choose "Open" from the IntelliJ IDEA welcome screen
1. From the file navigator, choose ``annotation-config`` under ``labs/java4-labs-spring-ioc``
1. Press OK so the project will open and IntelliJ will import it
1. Repeat the process you followed in the previous lab using tests defined in
``AnnotationConfigTests``
1. Commit your changes
1. Close the Project

## Submitting Your Work

1. Create a pull request for your branch using [these instructions](https://github.com/jeff-anderson-cscc/submitting-assignments-lab#once-you-are-ready-to-submit-your-work-for-grading)
1. Submit the assignment in Blackboard as described in [these instructions](https://github.com/jeff-anderson-cscc/submitting-assignments-lab#once-your-pull-request-is-created-and-i-am-added-as-a-reviewer)

__NOTE: I will provide feedback via. comments in your pull request.__
If you need to amend your work after you issue your initial pull request:

1. Commit your updates
1. Push your changes to gitHub
1. Verify the new commits were automatically added to your open pull request
