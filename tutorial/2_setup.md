# Setup

## Adding Identity

Every single commit you make to a repo will have a name and email attached to it

You need to set this up the first time you install git by using the following commands:

```git
git config --global user.name [Your username]
git config --global user.email [Your email]
```

Replace `[Your username]` with your github username and `[Your email]` with your own email.

## Using a specific text editor (optional)

### Using Vim

```bash
git config --global core.editor vim
```

### Using Notepad++ (For Windows users)

```bash
git config --global core.editor "'C:/Program Files/Notepad++/notepad++.exe' -multiInst -notabbar -nosession -noPlugin"
```

## Checking Settings

You can see all of the settings you have by running this command:

```bash
git config --list --show-origin
```

For example, mine outputs:

```
file:/home/mikey/.gitconfig     user.name=MichaelZhao21
file:/home/mikey/.gitconfig     user.email=michaelzhao314@gmail.com
file:/home/mikey/.gitconfig     core.autocrlf=input
file:/home/mikey/.gitconfig     core.editor=vim
file:/home/mikey/.gitconfig     credential.helper=cache --timeout=3600
```