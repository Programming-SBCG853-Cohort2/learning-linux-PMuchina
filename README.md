# learning-linux-PMuchina
learning-linux-PMuchina created by GitHub Classroom


When using the terminal, we are working in a single directory.For us to explore the file and the directory, 
we use **ls** as our command. **ls** lists all the contents of the directory that we are in.
## ls

Due to the many directories that may be present in the unix command,using the **pwd** command helps you to know your location
prints the whole working directory.
## pwd 

To make a new directory, we use the make directory command.
## mkdir 

when we want to switch directories we use the change directory command.
## cd 

when navigating one level upwards a directory, we use two dots .. when navigating two levels upwards, we use two sets
of dots separated by a forward slash
## cd ..
## cd ../..

to quickly navigate from the root directory to the learning unix, use the
## ~ @ cd /

to make the ls more useful, you can use dots to list directories above you. Adding a letter l after ls gives you a longer 
output compared to default
## ls .. 
## ls ../..
## ls -1/

For every unix command, we have a manual that helps us understand how all the options function. To access this, 
we use the man command. To navigate through the man, use space to scroll down, b to go back and q to quit.
## man ls
## man cd
## man man *(even the man command has a manual)*

When we have an empty directory that we might want to remove, we use the remove directory command 
## rmdir

when navigating through the terminal, the tab assists you to autocomplete and saves you from alot of typing
when we want to move files to a new directory, we use the **mv** command from the source to the destination.
The mv command can also be used to rename files from the old to new name.
## mv

When removing directories, we use the **rmdir** command but for files we use the **rm** command. However this may be a dangerous 
move a you may delete files you may never recover. You can however add -i after the command line to make it safer for use. This
will give you an option of weather you truly want to discard the file.
## rm

Copying files is much similar to moving files in that you must have a source and a destination. For this we use the command **cp**. This command can also be used to copy entire directories with the addition of command options.
## cp

When viewing files, we can use the **less** and **echo** commands.The less command only allows you to view files but you cannot edit them while echo allows you to put some text on file and veiw it. Echo command also displays contents known as the variable environment. Environment variables contain user specific or system wide values that reflect simple information such as the username or list of useful lcations. **cat** can also be used to view files but unlike less, you hhave no control of what you veiw. Cat can be used to combine multiple files or copy an exsiting file.

When counting characters, words and lines in a file, we use the word count command **wc**. By default it gives you all the characters, words and lines in a file but you can be more specific by give line command options for instance wc -1.
## wc

Editors can be incoporated in the unix system. Nano is an example of a lightweigh editor that can be used to edit text. The command is placed before the opening lines.

To find lines that match a certain pattern in a file, we use the **grep** command. Grep comman can be used together with other command options to make it more useful. For instance use *-i* to ignore case when matching. *-w* to only match whole words and *-v* to show lines that do not match. 

