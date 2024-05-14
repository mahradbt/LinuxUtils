# Linux Scripts

**Tired of wasting time configuring your Linux development environment?**

This repository provides a comprehensive collection of cheatsheets and detailed documentation to streamline your setup process for:

* Linux: Essential Linux configuration guides for a smooth development experience.

* Docker: Learn how to leverage Docker containers for efficient application deployment.

* Containers: Understand containerization concepts and best practices for managing containers.

* Docker Compose: Master Docker Compose for effortless multi-container application orchestration.

* DevOps Tools: Discover and integrate essential DevOps tools to automate your development workflow.


**Get up and running quickly with clear instructions, helpful tips, and readily available resources!**


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

