# Introduction to Git and Github
A simple website created to teach students the basics of version control in software development using git and Github for a workshop conducted by Nexus, SJCET.

Speaker: [Athul Cyriac Ajay](http://athulcyriac.xyz/)
## Pre-requisites
- Install Git on your computer. Instructions for installing Git on:
  - [GNU/Linux and MacOS](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  - [Windows](https://phoenixnap.com/kb/how-to-install-git-windows)
## Instructions
- Fork this repo and clone it to your local machine (`git clone <fork_url>`).
- Create file with your name seperated by `-` or `_` in the content folder.
- Add the template given below and fill in the respective details.
  ```
  ---
  name: "Your Name"
  avatar: "img.com/img.png"
  desc: "About You"
  college: "College Name"
  web: "website"
  github: "github link"
  gitlab: "gitlab link"
  ---
  ```
  The `name`, `avatar`, `desc`, `college` and `github` fields are mandatory. 
  If you do not have a website or Gitlab account set those fields to `none` like so:
  ```
  web: "none"
  ```
- Commit your changes with a proper commit message and push your changes to fork.
- Open a pull request against the main branch of this repo from your fork.
- Wait for someone to review the changes. After review, the maintainer will either
  merge your changes or suggest changes if required. 
## References
- [Git Cheatsheet](https://training.github.com/downloads/github-git-cheat-sheet/)
- [Git Documentation](https://git-scm.com/docs/)
