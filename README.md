Laptop
======

Laptop is a script to set up an OS X laptop for web development.

It can be run multiple times on the same machine safely.
It installs, upgrades, or skips packages
based on what is already installed on the machine.

Modified based on the original script by [thoughtbot](https://github.com/thoughtbot/laptop), with significant additions based on [holman's dotfiles](https://github.com/holman/dotfiles) and [mathiasbynens's dotfiles](https://github.com/mathiasbynens/dotfiles).

Requirements
------------

We support:

* [OS X Mavericks (10.9)](https://itunes.apple.com/us/app/os-x-mavericks/id675248567)
* [OS X Yosemite (10.10)](https://www.apple.com/osx/)

Older versions may work but aren't regularly tested. Bug reports for older
versions are welcome.

Install
-------

Clone the repo, and then run `mac`

```sh
git clone git@github.com:jjwon0/laptop.git
cd laptop
sh bootstrap 2>&1 | tee ~/laptop.log
```

Debugging
---------

Your last Laptop run will be saved to `~/laptop.log`. Read through it to see if
you can debug the issue yourself. If not, copy the lines where the script
failed into a [new GitHub
Issue](https://github.com/thoughtbot/laptop/issues/new) for us. Or, attach the
whole log file as an attachment.

Remaining stuff to do after installation
----------------------------------------

- Install iTerm2 themes
- Set up [dotfiles](https://github.com/jjwon/dotfiles)
- Install Flash Player
- Install MATLAB
