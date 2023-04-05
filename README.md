# learn-more-python3-hard-way 

Learn more python 3 the hard way. Commiting to 1 hour a day to get my vocational muscles going. 

- [ ] cat 
- [ ] find 
- [ ] grep 
- [ ] cut 
- [ ] sed 
- [ ] sort 
- [ ] uniq 


## Cheat Sheet
Sometimes I do some pair programming with others, so here is quick reminder of each command so we can all be in the same page. 

## cat 
- command used to display the contents of a file 
- Syntax: `cat [options] [file]`
- Example: `cat myfile.txt`

## find
- command used to search for files and directories in a given location 
- Syntax: `find [path] [expression]`
- Example: `find /home/user/ -name myfile.txt`

## grep
- command used to search for a specified text pattern in a file 
- Syntax: `grep [options] pattern [file]`
- Example: `grep "hello" myfile.txt`

## cut
- command used to extract a specific section (or "column") of text from a file 
- Syntax: `cut [options] [file]`
- Example: `cut -d "," -f 2 myfile.csv`

## sed
- command used to perform text transformations on a file 
- Syntax: `sed [options] [script] [file]`
- Example: `sed 's/foo/bar/g' myfile.txt`

## sort
- command used to sort the lines in a file alphabetically or numerically 
- Syntax: `sort [options] [file]`
- Example: `sort myfile.txt`

## uniq
- command used to remove duplicates from a file 
- Syntax: `uniq [options] [file]`
- Example: `uniq myfile.txt`
