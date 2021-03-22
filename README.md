# Git and GitHub set-up Guide
## Initial set-up
Skip these steps if you have already installed Git and created a GitHub account.
### 1) Install Git
To install Git, [click here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and follow the steps for your operating system.

### 2) Create a GitHub account
Create a GitHub account by [clicking here](https://github.com/), then click "Sign Up". Follow the steps to register for an account.

## Making a connection with Git and GitHub
### 1) Generating a SSH key
Open Git Bash (Windows)/Terminal (Linux or Mac) and do the following:
* Enter ```ssh-keygen -t rsa -b 4096 -C "the_email_address_you_signed_up_to_github_with"``` then press ENTER
* Press ENTER until the key's randomart image displays
* The key is saved in the ```~/.ssh``` directory

### 2) Finding the key
On Git Bash (Windows)/Terminal (Linux or Mac), do the following:
* Enter ```cd ~/.shh```
* Enter ```cat id_rsa.pub``` to show the key
* Copy the key

### 3) Linking with GitHub
On GitHub, do the following:
* Go on **Settings** by clicking your profile picture (upper right corner)
* Go on **SSH and GPG keys**
* Click **New SSH key**
* Enter the key name of your choice and paste the key
* Click **add SSH key** and you'll be ask to enter your password
* DONE!
