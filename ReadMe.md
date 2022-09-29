# ReadMe

Personal website avhb.github.io

## Set up development environment (Windows)

pre-requisites:

- have git installed ssh keys configured to github
- vscode

1. download hugo-extended binary [here](https://github.com/gohugoio/hugo/releases)
2. add the binary to the PATH env variable in Windows settings
3. clone this repo locally `git clone git@github.com:avhb/avhb.github.io.git`
4. `git submodule init` and `git submodule update`
5. `hugo server` for dev server 

## Github Actions

This website is set to auto deploy if a code push to the master branch is done

see: https://gohugo.io/hosting-and-deployment/hosting-on-github/

## Theme

Site is based on the coder theme

https://github.com/luizdepra/hugo-coder
