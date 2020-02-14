# rheinmainrocks.de Website

## Getting started

The "getting started" sections assumes that your git base directory
is `$HOME/src/github.com`.

```shell
# optional create a git namespace dir and cd into it
mkdir -p $HOME/src/github.com/rheinmainrocks
cd $HOME/src/github.com/rheinmainrocks

# clone the repo
git clone git@github.com:rheinmainrocks/rheinmainrocks.de.git
cd rheinmainrocks.de
```

After cloning the repo you should execute the bootstrap script in
the repo root directory. The script will

* copy a templated .env file for customization
* enable a commit message template

```shell
# execute the bootstrap script
/bin/sh ./bootstrap.sh
```

## Standards / Conventions

The repository uses/follows the following standards/conventions:

* [(Git) Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
* [Git Pre-Commit Checks](https://pre-commit.com/)
* [Editor Configuration](https://editorconfig.org)
* [direnv - Directory based settings management](https://direnv.net/)
* [ShellCheck](https://github.com/koalaman/shellcheck)

## Build / Extend / Customize

tbd

## Resources

* [Hugo](https://gohugo.io/)
* [Hugo Theme Academic](https://sourcethemes.com/academic/)
* [Netlify](https://www.netlify.com/)
