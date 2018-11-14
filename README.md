# git-stack &nbsp;&nbsp; ![GitHub tag (latest SemVer)](https://img.shields.io/github/tag/hankchanocd/git-commands.svg) [![Build Status](https://travis-ci.org/hankchanocd/git-commands.svg?branch=master)](https://travis-ci.org/hankchanocd/git-commands) [![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/) [![Github issues](https://img.shields.io/github/issues/hankchanocd/git-commands.svg)](https://github.com/hankchanocd/git-commands/issues) [![CodeFactor](https://www.codefactor.io/repository/github/hankchanocd/git-commands/badge)](https://www.codefactor.io/repository/github/hankchanocd/git-commands)

> Fuzzy search git commands with fzf

<p align="center">
<img alt="demo" width="850" src="https://github.com/hankchanocd/git-commands/blob/master/images/demo.png" />
</p>

## Install

Clone the repo, and run `npm run transfer` to transfer `./git-commands` to `~/bin`, or manually invoke `./script/transfer.sh` if you are not familiar with `npm`.

If you have a more desired `PATH` for storing scripts, configure `./script/transfer.sh` directly or ignore the transfer instructions.

## Before-Use

Make sure [`fzf`](https://github.com/junegunn/fzf) is installed globally. `git commands` won't work if `fzf` is not installed.

## Usage

A simple one-liner.

```bash
$ git commands
```

Alias `git commands` to something shorter - `git cmd`, if typing `commands` annoys you.

```bash
$ git config --global alias.cmd 'commands'
```

## Changelog

**2018-Nov-13:** `v1` published. Automate commit and file transfer process with [`commitizen`](http://commitizen.github.io/cz-cli/) and [`ghooks`](https://github.com/ghooks-org/ghooks).

## Others

See [Dotfiles](https://gitlab.com/hankchanocd/dotfiles) for my other works on `git`.

See [git-overview](https://github.com/hankchanocd/git-overview) - A quick git repository insight at terminal.

See [git-stack](https://github.com/hankchanocd/git-stack) - View differences between git branches with fzf.

## License

[MIT](./LICENSE)
