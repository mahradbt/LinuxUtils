# Linux Scripts


##### Table of Contents  
[Setup bash environment](#bashextra)

[Docker setup](#docker)

[Markdown Cheatsheet](#markdown)



<a name="bashextra" />

## Setup bash environment

1. run `./ubuntu-setup.sh`

2. place `bash_extra`

```bash
cp bash_extra ~/.bash_extra
```

3. import `bash_extra`

add below code at the end of `.bashrc`

```bash
if [ -f ~/.bash_extra ]; then
    . ~/.bash_extra
fi

```


<a name="docker" />

## Docker setup


<a name="markdown" />

## Markdown Cheatsheet

you can access Markdown cheatsheet [here](https://github.com/mahradbt/linux/blob/master/markdown-cheatsheet.md "Markdown Cheatsheet Document")

