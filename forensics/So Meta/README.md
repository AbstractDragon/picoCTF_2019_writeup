# So Meta
Points: 150

## Category
Forensics

## Question
>Find the flag in this picture. You can also find the file in /problems/so-meta_0_7c0b2ae7a38b024c6b1c68cf50970a88.
![unzipped file](files/pico_img.png)

### Hint
>What does meta mean in the context of files?
>Ever hear of metadata?

## Solution 
Open terminal and install imagemagick
```
$ sudo apt install imagemagick
```

Open terminal in the directory of the image file and use:
```
$ identify -verbose pico_img.png | grep "picoCTF"
```

![unzipped file](files/flag.png)

We can now submit the flag and complete the challenge.

### Flag
`picoCTF{s0_m3ta_dc38ce45}`
