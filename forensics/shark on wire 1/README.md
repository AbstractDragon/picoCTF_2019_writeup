# extensions
Points: 150

## Category
Forensics

## Question
>This is a really weird text file TXT? Can you find the flag?

### Hint
>How do operating systems know what kind of file it is? (It's not just the ending!)
>Make sure to submit the flag as picoCTF{XXXXX}

## Solution 
Open terminal and run to determine what file it is.
```
$ file flag.txt
```

Run the following to change the extension of the file
```
$ mv flag.txt flag.png
```

![flag image](files/flag.png)

We can now submit the flag and complete the challenge.

### Flag
`picoCTF{now_you_know_about_extensions}`
