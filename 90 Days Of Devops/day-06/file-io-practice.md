# Day 06 – Linux Fundamentals: Read and Write Text Files

## Task

- Creating a file
- Writing text to a file
- Appending new lines
- Reading the file back

## Commands Used

- `touch vishal.txt`
Ouput: To text file 


- `echo "Hi, I vishal sharma" > vishal.txt`
Output: Add line in file 

- `echo "I will be Devops 2026" >> vishal.txt`
Output:  Append line in notes.txt
- `echo "My Dream is to work in Atlassian" >> vishal.txt `
Output:  Append line in vishal.txt

- `cat vishal.txt | head -n 1`
Output: To read notes.txt heading  line 1

- `cat vishal.txt | tail -n 2`
Output: To read vishal.txt last 2 lines 

- `echo "Hands-on is key to become Devops Engineer" | tee -a vishal.txt`
Output: Append and prints the output to terminal

- ` cat vishal.txt`
Output: Read vishal.txt

## Hands on

