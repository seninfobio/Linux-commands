# [Reference](https://bioinformaticsworkbook.org/Appendix/programs#gsc.tab=0)


# Linux-commands

**vi/.sh files edit/delete** -  `:1$d`

# File commands

1. `ls` - Director listing
2. `ls-al`- Formatted listing with hidden files
3. `ls -lt` Sorting the formatted listing by time modification
4. `cd dir` - change the directory to dir
5. `cd` - change to home directory
6. `pwd` - show current working directory
7. `mkdir dir` - creating a directory dir
8. `cat >file eg. cat 1.txt 2.txt 3.txt > 0.txt` - places the standard input into the file
9. `more files` - output the contents of the file
10. `head file` - output the first 10 lines of the file
11. `tail file` - outpu the  last 10 lines
12. `tail -f file` - output the contents of files as it grows, starting with the  last 10 lines
13. `touch file` - create or update file
14. ` rm file` - Deleting the file **(rm -rf files)
15.  `du-sh (filename)` - memory usage
16.  `kill PID` - To kill the processing/running file
17.  


# Compression

1. `tar cf file.tar file` - **create tar named file.tar containing file**
2. `tar xf file.tar` - **Extract the files from file.tar**
3. `tar czf file.tar.gz files` **create a tar with Gzip compression**
4. `tar xzf file.tar.gz` - Extract a tar using Gzip
5. `tar cjf file.tar.bz2` - Create tar with Bzip2 compression
6. `tar xjf file.tar.bz2` - Extract a tar using Bzip2
7. `gzip file` - Compresses file and renames it to file.gz
8. `gzip -d file.gz` -Decompresses file.gz back to file

# Searching
1. `grep pattern file` - Search for pattern in file **(grep "^>" filename.fasta | wc -l )**
2. `grep -r pattern dir` - Search recursively for  pattern in dir
3. `command | grep pattern` - Search pattern in the output of a command
4. `locate file` - Find all instances of file
5. `find .-name filename` - Searches in the current directory (represented by a period) and below it, for files and directories with names starting with filename
6. `pgrep pattern` - searches for all the named processes, that matches with the pattern and, by default, returns their ID
7. `grep ">" FILENAME > HEADERFILE.txt`  
8. `grep ">" FILENAME | less`  
9. `grep ">" AT_cDNA.fa | less` -you can list all the headers (description lines) for the sequences using grep. Simply search for > and grep will list all the description lines.		

