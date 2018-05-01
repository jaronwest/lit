# lit
Lite Issue Tracking (LIT)

LIT is an ultra-lightweight issue tracking system similar to git.
Simply copy the lit file into your /usr/local/bin/ folder, set permissions to 755 and you're ready to go!


Navigate to the path you would like to initialize issue tracking on or have an existing .lit folder and use the following commands:

•`lit init`
Initiate the issue tracking repository at current path
This creates folder '.lit' with files 'open' and 'closed'

•`lit` with no arguments or flags
List all open issues

•`lit closed`
List all closed issues

•`lit -a ["Description of Issue"]`
Add a new issue (or leave description blank and it will prompt you) appended to file open with date/time

•`lit -d`
List all open issues and prompts which to delete

•`lit -d-all`
Prompt for permission to delete all open issues

•`lit -c [Issue #]`
Close open issue # (or leave issue # blank and it lists all open isues and prompts which to close)
Removes from file open, appends to file closed with date/time

•`lit -dc`
List all closed issues and prompts which to delete

•`lit -dc-all`
Prompt for permission to delete all closed issues
