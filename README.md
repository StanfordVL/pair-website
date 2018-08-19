# Stanford PAC Website

This repo contains the static files needed for the [Stanford Partnership in AI-Assisted Care (PAC) website](https://aicare.stanford.edu). 

### Requirements

1. SSH access to aicare.stanford.edu
2. Sudo permission on aicare
3. Access to this repository

### Instructions

You should perform all edits on your local machine and test the website on your local browser. Once you are 100% sure the website is updated, then pull on aicare.

On your local machine:

#### 1. Clone the repo to your local machine.
Standard command: `git clone git@github.com:ahaque/stanford-pac-website.git`

#### 2. Update the website on your local machine.
Update the relevant files. We use .php files to handle the *Last Updated* timestamp in the footer as well as the [Google reCAPTCHA](https://www.google.com/recaptcha/intro/).

If you don't have a php server running on your local machine, you can rename the .php files to .html while you edit on your local machine. **Note: Please rename it back to .php before committing.**

#### 3. Commit your local changes and push to Github.

Once you are done, commit your local changes and push the changes to Github. `git commit -m <message here>` then `git push` are the commands.

#### 4. Pull the changes onto aicare.

Connect via SSH to aicare.stanford.edu. Once you are logged in, navigate to `/var/www/html`.

Notice the files in this folder mimic your local repository. This folder is also a valid git repo. Now pull your changes with `sudo git pull`.

You may already have sudo permission so go ahead and enter your password when Ubuntu asks for it. If you do not have sudo rights, ask someone (e.g., Albert) to pull for you.

The git repo on aicare was configured with HTTPS so it will ask for your **Github** username and password before the pull can be performed. Once the pull is successful, you can view the new website: [https://aicare.stanford.edu](https://aicare.stanford.edu)
