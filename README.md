# Bash-Commands
## Basic Commands
- [ ] pwd - Present Working Directory
- [ ] cd - Change directory
  - **./--** > means current directory | **cd ..** --> means one directory behind | |**cd ../..** --> 2 folder behind
- [ ] **ls** - show the content inside the directory
  - **ls -la** - including hidden folder
  - **ls -l new_dir** - show the file details inside new_dir
  - **ls -r new_dir** - show the file details inside new_dir recursively
  - **ls -t new_dir** - show the file details inside new_dir with timestamp
  -  
- [ ] mkdir - make a folder
- [ ] touch - create an empty file e.g touch index.js
- [ ] cat - show content of file e.g cat index.js
- [ ] code . --> open file in v s code
- [ ] mv --> move the file e.g a.mv a1.txt new-folder | b. mv test new-f1/new-f2
- [ ] cp --> copy e.g cp t2.txt new-f3
  - copy recursively - e.g cp -r test1 test2
## Advance Commands
- change Permission----> for example when we use ls -l command we get 
	- -rw-r--r-- --> so 1st rw is for me , r is for staff, r is for others
	- To change mode-chmod (u/g/o) (+/-) (r/w/x/rw...) e.g chmod u+x a.sh
- echo "Hello World" --> to display in terminal
- head a.txt / tail a.txt --> gives last or first 10 lines of a.txt file.
- combining both head and tail--> tail -n +25 newfile.txt  | head 5
- wc --> basic stats about file (wc a.txt)
- grep --> grep "one" a.txt
	- grep -c "one" a.txt-->(give num of occurences)
	- grep -h "one" a.txt --> (give all occurences)
	- grep -hi "one" a.txt




