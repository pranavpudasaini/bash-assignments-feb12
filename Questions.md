# 1. Basics

Copy your `/etc/passwd` file to `/tmp` and write a script to display the following:


- Full contents of the file sorted in ascending order (display the whole file)
- Total number of lines in the file
- Total number of characters in the file
- All usernames containing the letter `s`
- All usernames starting from `r`

# 2. Naive Parser

Given the following CSV file, write a Bash script to find if the total number of delimeters in the file is correct.

```csv
id|first_letter|last_full|age
0|S|Dangol|24
1|P|Koirala|17
2|S|Dotel|18
3|N|Shresth|19
4|A|Joshi|22|
```

## 3. Cron

Write a cron job that runs every hour. It should:

- Fetch the HTML response from `https://www.example.com`
- Log the output inside this directory `/var/log/bash_assignment/`
- Compress all previous logs as a ZIP archive
- Keep only 5 most-recent archives and delete all other archives

