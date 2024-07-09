# Learning Git
Project to learn how to use Git

## Installation
The first step to start using Git is the installation, you can download the installer from the Official Site
[Download](https://gitforwindows.org/) 


### How to setup User and Password

This is how you set git username and password in git bash.

```
Set username
$ git config --global user.name "rafaelxoliolab"
```
![image](https://github.com/rafaelxoliolab/git.learning/assets/63336526/92127cad-c7f8-4049-a959-922cf4cea0b3)

```
Set email account
$ git config --global user.email "rafa@gmail.com"
```
![image](https://github.com/rafaelxoliolab/git.learning/assets/63336526/4726fedc-f90f-4412-a2ea-4696379c4eba)


```
Set Password
$ git config --global user.password "1234321"
```
![image](https://github.com/rafaelxoliolab/git.learning/assets/63336526/0d63467d-873f-4b12-9604-bfdb8fe3a686)

```
To save the credentials forever
$ git config --global credential.helper store
```
![image](https://github.com/rafaelxoliolab/git.learning/assets/63336526/9b6d2649-7c0e-4b02-a6f1-a8efbe26221b)

```
To check the inputs
$ git config --list --show-origin
```
![image](https://github.com/rafaelxoliolab/git.learning/assets/63336526/2ea537ec-ece6-4855-baef-08fe8b36b125)


### How to Push changes to remote repositories
```
Verify Status
$ git status

Add changes
$ git add .

Commit changes
$ git commit -m 'Message'

Push changes
$ git push
```
