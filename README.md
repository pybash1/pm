<br/>
<p align="center">
    <a href="https://github.com/pybash1/rrpm" target="_blank">
        <img width="50%" src="https://raw.githubusercontent.com/pybash1/rrpm/master/extra/banner.png" alt="RRPM logo">
    </a>
</p>
<br/>
<p align="center">
    <a href="LICENSE" target="_blank">
        <img src="https://img.shields.io/github/license/pybash1/rrpm.svg" alt="GitHub license">
    </a>
    <a href="https://github.com/pybash1/rrpm/releases" target="_blank">
        <img src="https://img.shields.io/github/tag/pybash1/rrpm.svg" alt="GitHub tag (latest SemVer)">
    </a>
    <a href="https://github.com/pybash1/rrpm/commits/" target="_blank">
        <img src="https://img.shields.io/github/commit-activity/y/pybash1/rrpm.svg" alt="GitHub commit activity">
    </a>
    <a href="https://github.com/pybash1/rrpm/graphs/contributors" target="_blank">
        <img src="https://img.shields.io/github/contributors-anon/pybash1/rrpm.svg" alt="GitHub contributors">
    </a>
</p>
<br/>

[**RRPM**](https://github.com/pybash1/rrpm) is the **all-in-one project and remote repository management tool**. A 
simple CLI tool that supports project generation for multiple languages, along with support for generating projects
using different package managers and/or environments. This repository contains the **core CLI source code**.

## 🚀 Installation && Documentation

`rrpm` can be installed from PyPI

```bash
pip install rrpm
```

Complete documentation can be found on [GitBook](https://pybash.gitbook.io/rrpm)

## Usage

```bash
Usage: python -m rrpm [OPTIONS] COMMAND [ARGS]...
Options:
  --install-completion [bash|zsh|fish|powershell|pwsh]
                                  Install completion for the specified shell.
  --show-completion [bash|zsh|fish|powershell|pwsh]
                                  Show completion for the specified shell, to
                                  copy it or customize the installation.
  --help                          Show this message and exit.
Commands:
  create  Generate a project from any of the presets and/or its variations
  get     Clone a remote repository to directory specified in config
  list    List all cloned repositories and generated projects
```

## ❤️ Community and Contributions
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## 📫 Have a question? Want to chat? Ran into a problem?
We are happy to welcome you in our official [Discord server](https://discord.gg/FwsGkZAqcZ) or answer your questions via [GitHub Discussions](https://github.com/pybash1/rrpm/discussions)!

## 🤝 Found a bug? Missing a specific feature?
Feel free to **file a new issue** with a respective title and description on the the [pybash1/rrpm](https://github.com/pybash1/rrpm/issues) repository. If you already found a solution to your problem, **we would love to review your pull request**!

## ✅ Requirements
RRPM requires Python >=3.7

## Presets
 - [ ] Python
   - [x] Pip
     - [x] Python Package
     - [x] FastAPI
     - [x] Flask
   - [x] Poetry
     - [x] Python Package
     - [x] FastAPI
     - [x] Flask
   - [ ] Virtual Environments
     - [ ] Python Package
     - [ ] FastAPI
     - [ ] Flask
 - [ ] JavaScript
    - [ ] NPM
      - [ ] NodeJS
      - [x] ReactJS
        - [x] create-react-app
        - [x] Vite
      - [x] NextJS
    - [ ] Yarn
      - [ ] NodeJS
      - [x] ReactJS
        - [x] create-react-app
        - [x] Vite
      - [x] NextJS
    - [ ] Pnpm
      - [ ] NodeJS
      - [ ] ReactJS
        - [ ] create-react-app
        - [x] Vite
      - [x] NextJS
 - [ ] TypeScript
     - [ ] NPM
       - [ ] NodeJS
       - [x] ReactJS
         - [x] create-react-app
         - [x] Vite
       - [x] NextJS
     - [ ] Yarn
       - [ ] NodeJS
       - [x] ReactJS
         - [x] create-react-app
         - [x] Vite
       - [x] NextJS
     - [ ] Pnpm
       - [ ] NodeJS
       - [ ] ReactJS
         - [ ] create-react-app
         - [x] Vite
       - [x] NextJS

## 📘 License

The RRPM tool is released under the under terms of the [MIT License](https://choosealicense.com/licenses/mit/).