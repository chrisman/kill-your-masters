This project contains a git template directory that changes the default HEAD from "master" to "main" because that shit is racist.

## About

The git template includes everything in the system default git template with one modification: it changes the contents of HEAD from `ref: refs/heads/master` to `ref: refs/heads/main`

Using this template makes it so that every time you `git init` from now on, the project will initiallize with a "main" branch and not a "master" branch.

Read more about git templates here: https://git-scm.com/docs/git-init#_template_directory

## Getting Started

1. Clone this repository somewhere.

2. Add this to your git config:

	```
	[init]
  		templatedir = path/to/this/directory/black-lives-matter.git
	```	

3. Go test it out. Initialize a blank git repo somewhere and see that is intialized with a "main" branch.

## Customizing

Change the contents of HEAD to `ref: refs/heads/<whatever>`.

Here are some suggestions that are also better than master:

- primary
- prod
- parent
