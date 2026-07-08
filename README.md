# Learning Git
Project to learn how to use Git for Windows

By Rafael Xolio

## Installation
The first step to start using Git is the installation, you can download the installer from the Official Site
[Download](https://gitforwindows.org/) 

<img width="1041" height="677" alt="image" src="https://github.com/user-attachments/assets/ea951c75-1c5f-4272-9744-fbf4fb564d70" />

<img width="802" height="617" alt="image" src="https://github.com/user-attachments/assets/812969b0-d954-4c8d-96bd-efb417849550" />

<img width="792" height="617" alt="image" src="https://github.com/user-attachments/assets/279160ce-5236-4d17-926e-ff785d50291d" />

<img width="792" height="616" alt="image" src="https://github.com/user-attachments/assets/d04398b6-d404-4590-af63-51f7f55764be" />

<img width="922" height="502" alt="image" src="https://github.com/user-attachments/assets/097598d1-2035-4dbd-97c0-173fe5a45cd7" />


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

### Ho to Clone remote repositories
```
To clone a remote repo you only need to run the clone command following next sintaxys:
$ git clone [repo URL]
```
<img width="820" height="141" alt="image" src="https://github.com/user-attachments/assets/4545d227-10f2-4613-a18e-cf23d842b3c6" />


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
