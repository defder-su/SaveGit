<h1 align="center">SaveGit</h1>

<p align="center">The collection of scripts for git.</p>

## Features:

- Save specified repositories.
- Save all repos hosted by GitHub user.
- Save by lists.

---

## Installation (Linux, macOS):

Install `git`, `curl` and [jq](https://stedolan.github.io/jq/download/).

Create a folder where you want your repositories downloaded in a drive where you have enough space available.

Open a terminal in the folder and run `chmod +x save*`.

---

## Installation (Windows):

Install [WSL](https://docs.microsoft.com/en-us/windows/wsl/install-win10) (requires about 2GB disk space), [Cygwin](https://www.cygwin.com/), [Git Bash](http://git-scm.com), or some other tool that enables Bash functionality in Windows.

Follow the above section.

---

## Usage:

Open a terminal in the folder and run `./save` or other script with arguments.

### Save a new repo:
`./save https://github.com/defder-su/SaveSites.git`

### Save GitHub user's repos:
`./save https://github.com/ipfs`

### Save list:
`./save_by_list example.txt`

### Save default list:
`./save_by_list collection.txt`

`./save_collection`

---

## TODO:

Updating resaved repositories (using `git fetch` and `git pull`), updating all saved with a command like `./save_updates`.

How to save related data like issues, pull requests etc.? See [thread](https://stackoverflow.com/questions/41369365/how-can-i-export-github-issues-to-excel).

Clone repositories into subfolders.

---

## Related Projects:

- [SaveSites](https://github.com/defder-su/SaveSites)

- [SaveMedia](https://github.com/defder-su/SaveMedia)

- [RatBrowser](https://ratbrowser.com)

- [IPFS](https://ipfs.io)

- [ZeroNet](https://zeronet.io)

---

## Contact:

You are welcome in [Defder.SU](https://defder.su).
