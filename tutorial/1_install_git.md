# Installing Git

The most helpful guide is on the [official git website](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git). However, here is it simplified:

## Linux

### Debian-Based (Ubuntu, etc.)

```bash
sudo apt-get install git-all
sudo apt-get install install-info
```

### RPM-Based (Fedora, RHEL, etc.)

```bash
sudo dnf install git-all
sudo dnf install getopt
```

### Other Linux Distros

Use [this](https://www.google.com) to find the correct download (should be there if your distro is fairly well-supported)

Example for Manjaro (Arch-based):

```bash
sudo pacman -S git
```

## Mac

```bash
git --version
```
It will either be already install in which case this will output a version (ex. `git version 2.26.2`) or it will prompt you to install it

## Windows

Windows is annoying >:(( but there is a project called Git for Windows and they packaged an application called Git Bash to allow you to use git on your desktop.

[Download Link](https://git-scm.com/download/win)