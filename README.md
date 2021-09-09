# ANTLR CPP14 grammar root
In this project, we are trying to parse a simple CPP source in example.txt

## Reference
https://stackoverflow.com/questions/62756429/antlr-cpp14-grammar-root

## Run the Project
The TestRig needs the compiled Java source files to work.

From the terminal (assuming your CPP14.g4 and ANTLR JAR are in the present working directory), do the following:

### Generate parser classes
C:\WORKSPACE\IdeaProjects\AntlrProj1> java -cp antlr-4.8-complete.jar org.antlr.v4.Tool CPP14.g4

### Compile generated parser classes
C:\WORKSPACE\IdeaProjects\AntlrProj1> javac -cp .;antlr-4.8-complete.jar *.java

### Run TestRig
C:\WORKSPACE\IdeaProjects\AntlrProj1> java -cp .;antlr-4.8-complete.jar org.antlr.v4.gui.TestRig CPP14 translationunit -gui < example.txt

## Git Commands

$ git init
$ git remote add origin https://github.com/gudiseva/AntlrProj1.git
$ git remote -v
$ git pull origin main
$ git add .
$ git commit -m "Initial Commit"
$ git push origin master
    Do a Pull Request to Merge Master with Main.  Delete Master branch.
$ git checkout origin/main

### To get the history of commands
C:\WORKSPACE\IdeaProjects\AntlrProj1> doskey /history
