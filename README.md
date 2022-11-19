# Dev Environment

It will always be the first thing to prepare the development environment when the programmer gets a new computer. So I organize the environment to be configured as follows.

> Note: The order is important. 
>

## Basic

[HomeBrew](https://brew.sh/)

Nice Package Manager for MacOS/Linux

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

[Git](https://git-scm.com/)

Nice Version Control System

```shell
brew install git
```

[NVM](https://github.com/nvm-sh/nvm)

Nice Version Control for Node/NPM

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.2/install.sh | bash
```

[Node.js/NPM](https://nodejs.org/en/)

Nice Package Manager for Node projects

```bash
nvm install --lts
```

[Rust](https://www.rust-lang.org/)

Nice programming language

*install rustup first*

```shell
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```



## Extension

[Yarn](https://yarnpkg.com/)

The upgraded version of npm which is faster

```bash
npm i -g yarn
```

[TypeScript](https://www.typescriptlang.org/)

The javascript with syntax for types

```bash
yarn add typescript --dev
```

```bash
npm install typescript --save-dev
```

[oh-my-zsh](https://ohmyz.sh/)

> Need install zsh before, if not, use `brew install zsh`

```shell
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```



## Blockchain

> Since I'm a blockchain developer, I need to install some unique environment for blockchain dev

[Hardhat](https://hardhat.org/)

A development environment for Ethereum SmartContract

```bash
yarn add --dev hardhat
```

```bash
npm install --save-dev hardhat
```

