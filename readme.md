# Project XT
Built on TLA rev 535

***

## Goals
The [current FOnline SDK](https://xp-dev.com/sc/history/76003/HEAD/?page=0) exists in a constant state of flux, with no stable release in over two years. The goal of this project is to provide an updated, documented revision of the SDK to build on.

## How to contribute

### Pre-requisite: Git Client

You can find a list of Git client software here: https://git-scm.com/downloads/guis/

We prefer Github Desktop for ease of use. Github Desktop can be downloaded here: https://desktop.github.com/

### Code
1. Create a Fork of this repository

2. To merge changes, [submit a pull request](https://github.com/tinoesroho/Project-XT/compare)

3. Your code changes will be reviewed and merged.

### Documentation

Documentation is stored on [our wiki](https://github.com/tinoesroho/Project-XT/wiki). As time permits, we will update the wiki to outline the scripts, the scripts' functions, and how to add new content.


## Installation Pre-requisites

Requires server and map files from [this version of the SDK](http://www.mediafire.com/file/e7rslca0rwcag90/SDK_TLA.rar) (535).

In the off chance the SDK mirror is down, you can download it via SVN.

### SVN instructions
1. Download and install [TortoiseSVN](http://tortoisesvn.net/) source control software.

2. Create a new folder. You will need around 2 GB of free space.

3. Run CMD

4. Run this command in CMD: svn checkout http://xp-dev.com/svn/fonline_sdk/@535

5. Wait for SDK to download (it will take a while).

## Install Project XT (server admins)

Remove the /scripts/ folder from the SDK and replace it with the Project XT scripts folder.