## **😈 Terminal Commands Cheat Sheet 😈** ##
### *Navigating the file system:* ###
#### Terminal is an example of a shell where we can run UNIX commands and is a replacement to a GUI *(Graphical User Interface)* Any command we run on the terminal will be executed similar to that of a file window! ####
### *Locating our position:* ###
### **Where am I?** ###
`pwd`
#### This command is short for *(print working directory)* and is used to find which folder we are currently in.
### **Whose with me?** ###
`ls`
#### This command is short for *(list files)* and is used to see all the files and folders within our current directory.
### **Tell me more?** ###
`ls -l`
#### This command results in a list of files and folders along with extra infromation (*permissions, owner and modification date*) ####
### **Whose REALLY with me?** ###
`ls -al`
#### This command results in a list of files and folders along with any hidden files we originally cannot see. ####
### *Finding our way around:* ###
### **How do i get there?** ###
`cd`
#### This command is short for *(change directory)* and is used to change our location to a different directory stated after the command (*use tab to see options*) or if inputed alone - will take us to our home directory.
### **How do I go back?** ###
`cd -`
#### This command is used to go back to where we originally were within the directory. (*if you get lost use pwd*)
### *Creating Files:* ###
### **How do I make a directory?** ###
`mkdir <name>`
#### This command is short for *(make directory)* and is used to create a directory within the location (*name is the name of the new directory*) ####
### **How do I make a file?** ###
`touch <name.format>`
#### This command is used to create a file within the directory (*do not forget to format a file extension*) ####
### **How do I open it?** ###
`open <name of file>`
#### This command is used to open the specificed file. ####
### *Moving files around:* ###
### **How do I move it** ###
`mv <name of file> <.. or destination name>`
#### This command is used to move a specified file either above *(..)* or to a specific destination *(directory name)* ####
#### *important to note that . is the current directory and .. is the directory above* ####
### **How do I copy it?** ###
`cp <name of file> <directory to copy to>`
#### This command is used to copy a specified file to a specified directory. ####

### **How do I delete it?** ###
`rm <file name>`
#### This command is used to delete a specified document or file (*put -r in front to delete a directory*). ####