#### Essential Commands
-------------------------------------------------------------------------

* Search for files and directories : **find** , **locate**

<h6>find:</h6>

- command used to search for files and directories

- Can search by name, file type 

<h5>Syntax:</5>

> sudo find -name "file_name"

> sudo find / -name "file_name"

> sudo find / -iname "file_name"

> sudo find / -type f -name "file_name"

> sudo find / -type f -user user_name

<h6>locate:</h6>

- faster than find

<h5>Syntax:</5>

> locate "file_name"

> locate i "file_name"

* Files manipulation
-------------------------------------------------------------------------

<h6> cat:</h6>

- Display the content of a file

<h5>Syntax:</5>

> cat file_name

<h6> touch:</h6>

- Used to create an empty file

<h5>Syntax:</5>

> touch file_name.txt

<h6> nano:</h6>

- Used to create a new file

- Review and edit the content of an existing file

<h5>Syntax:</5>

> nano file_name


Input-output Redirection
--------------------------------------------------------------------

<h5> | (pipe)</h5>

- Used to move data between the commands (Output of one command becomes the input of the other command)

<h5>Syntax:</5>

> command_1 | command_2

<h5> The **>** operator </h5>

- Used to write an output to a file
- Create a file if it does not exist or overwrite an existing file

<h5>Syntax:</5>

> echo " output message" > example.txt


<h5> The **>>** operator </h5>

- Append the command output to a file
- Create new file if that file name does not exist 

<h5>Syntax:</5>

> echo " output message" >> example.txt






 