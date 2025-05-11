**25 Essential Linux Commands for Developers**

**A precise, graduate-level guide to essential Linux commands for project environments, file management, and productivity.
**
Refer to the Technical Notes Guidelines for detailed formatting instructions.

Introduction
Linux commands offer granular control over your development environment, enabling efficient navigation, file manipulation, and environment configuration. This guide presents 25 must-know commands with explanations, examples, and commentary.

📁 Section 1: File & Directory Navigation
1. pwd — Print Working Directory
Displays the current working directory's absolute path.
pwd
📌 Useful to confirm where you are in the file system.
📝 Yeh batata hai ke aap kaunsi location par ho currently.

2. ls — List Directory Contents
Shows files and folders in the current directory.
ls
3. ls -l — Long Format Listing
Provides details like permissions, owner, size, and date modified.
ls -l
4. ls --help — Help Option
Lists all flags and options available with ls.
ls --help
📌 Helpful for self-discovery of command usage.
📝 Commands ke options samajhne ke liye kaam aata hai.

5. cd — Change Directory
Navigates into a folder.
cd project-folder
6. cd .. — Go Back One Level
Moves up to the parent directory.
cd ..
📝 Ek level upar jane ke liye.

7. cd / — Root Directory
Takes you to the root (/) of the file system.
cd /
📌 Root is the top-most directory in Linux.

🛠️ Section 2: File Creation & Editing
8. mkdir — Make Directory
Creates a new folder.
mkdir src
9. touch — Create Empty File
Creates an empty file or updates the timestamp of an existing one.
touch index.py
📝 Khaali file banane ke liye.

10. echo — Output Text to Terminal or File
Writes plain text or redirect it to a file.
echo "Hello, Linux"  # prints text
echo "print('Hi')" > hello.py  # creates file and writes text
📝 File banane ke saath content bhi daal sakte hain.

11. echo >> — Append to File
Appends data to an existing file.
echo "print('Bye')" >> hello.py
12. cat — Display File Content
Prints file content to the terminal.
cat hello.py
📝 File ke andar ka content dekhne ke liye.

📦 Section 3: File Operations & Redirection
13. cp — Copy Files or Directories
cp index.py backup.py
Use -r to copy folders recursively:
cp -r src/ backup/
14. mv — Move or Rename
mv old.py new.py   # rename
mv file.txt ../    # move file to parent
📝 Move bhi karta hai, rename bhi.

15. rm — Remove Files or Directories
rm old.py
rm -r temp/  # remove folder recursively
⚠️ Use cautiously; files are permanently deleted.

16. clear — Clear Terminal Screen
clear
📝 Console ko saaf karta hai.

17. man — Manual Page
Opens the manual (documentation) for any command.
man ls
📌 Linux documentation ka built-in source.

18. history — View Past Commands
history
📝 Pichle commands dekhne ke liye.

19. head — First Few Lines of File
head -n 5 index.py
Shows first 5 lines.
20. tail — Last Few Lines of File
tail -n 10 log.txt
📝 Log files ke liye useful.

⚙️ Section 4: Permissions & Process Handling
21. chmod — Change Permissions
chmod +x script.sh
📝 Executable banata hai shell script ko.

22. ps — Process Status
ps aux
Shows all active processes.
23. kill — Terminate a Process
kill <PID>
Use ps to find the PID (process ID).
📡 Section 5: Networking & Search
24. ping — Test Internet Connection
ping google.com
📝 Network connectivity test karne ke liye.

25. grep — Pattern Matching / Search
grep "def" script.py
Searches for a specific pattern inside files.
📌 Codebase me search karne ke liye bahut powerful hai.

✅ Summary
Navigation: cd, pwd, ls, mkdir
File Handling: touch, echo, cat, cp, mv, rm
Process Tools: ps, kill, chmod
Help & Docs: man, history, --help
Networking/Search: ping, grep
