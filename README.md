 # ⚒️ **task-list-cli-tool** :notebook_with_decorative_cover: 
This is a simple and interactive command line tool that manages a list of tasks on the local file system.
I used the core module fs to store the the tasks in a json format.
Additionally I used two other npm modules: 
1. Yargs:  A tool that parses arguments - commands and options.
2. Chalk: Which adds some terminal string styling, so that the output will be easier to read.

If you want to use this tool, just type the following in the terminal: 
run node app.js
then insert a command from the list below:

  **add**     To add a new note
  
  **remove**  To remove a note
  
  **list**    To list your notes
  
  **read**    To read a note
  
Now you need to provide the necessary data (just the title or both title and description), according to the command you chose.

  add --title [your_title] --body [your_description]
  
  remove --title [your_title]
  
  list
  
  read --title [your_title]

You can also check what is the data the command expects by inserting --help.

Example: 🔨
node app.js add --help

