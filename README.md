# Introduction web development

## tools
- VSCode - `code editor` 
- terminal/shell/cmd/command prompt/cli - the `command line interface` (not user-interface)
- firefox + devtools
- slack for communication


## markdown syntax examples

# Headline 1
## headline 2
##### Headline 5


Hello today is `monday`  
This is *important*  
This is **just** for formatting

Today i did:
- buy bread
- bought milk


## keyhboard shortcuts

`CTRL + S` => save file (in vscode)
`CTRL + R` => reload (in firefox)


## terminal introduction
`dir`  => show contents of current directory
`cd FOLDERNAME` => "change directory" changes current directory to FOLDERNAME  
`cd ..` => changes directory one folder up  
`cp FOLDERNAME NEWFOLDERNAME` => copies a file from FOLDER to NEWFOLDERNAME  
`move OLDFILENAME NEWFILENAME` => moves/renames a file OLDFILENAME to NEWFILENAME
`move ../FILEFROMUPPERFOLDER .` => move the file from the upper folder to HERE ( . )  
`mkdir NEWFOLDERNAME` => creates NEWFOLDERNAME  
`cd F` and press TAB => it will autocomplete eveything with F at the beginning


## git

### git one time commands per project
`git init` => initiates a new/empty repository(project/folder that you wanna track

### git working flow => creates and pushes one git commit
`git status` => shows current status of git/changes/tracked files  
`git diff` => shows all the changes since the last commit
`git add cat.jpg index.html lili.html` => tell git to start tracking 3 files (put them to the bus station)  
`git commit -m "add all files to git initially"` => commits the currently staged files (let them pick up by the bus) `-m` lets you define a custom message
`git push` => synchronises with gitHUB, uploads all your commits/code to the remote