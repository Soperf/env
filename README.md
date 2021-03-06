# env

Repo for storing my environment settings, dotfiles and etc. [`git.io/env`](https://git.io/env)

* [`.bash_profile`](https://github.com/Drapegnik/env/blob/master/.bash_profile) - shortcuts, bash settings
* [`.inputrc`](https://github.com/Drapegnik/env/blob/master/.inputrc) - extended bash configs
* [`.gitconfig`](https://github.com/Drapegnik/env/blob/master/.gitconfig) - git aliases, colors and user configs
* [`Brewfile`](https://github.com/Drapegnik/env/blob/master/Brewfile) - my [`brew`](https://brew.sh/) packages dump made with [`homebrew-bundle`](https://github.com/Homebrew/homebrew-bundle)
* [`atom/`](/atom) - my [`atom`](https://atom.io/) configs & packages dump made with [`sync-settings`](http://atom.io/packages/sync-settings)
* [`jetbrains/`](/jetbrains) - [JetBrains IDE's](https://www.jetbrains.com/products.html) configuration
* [`.stack/`](https://github.com/Drapegnik/env/blob/master/.stack) - [`haskellstack`](https://www.haskellstack.org/) files
* [`.ghci`](https://github.com/Drapegnik/env/blob/master/.ghci) - [Glasgow Haskell Compiler](https://wiki.haskell.org/GHC/GHCi) options

## commands

* `sh bin/install-brew.sh`: install [`brew`](https://brew.sh)
* `sh bin/sync.sh`: update [`Brewfile`](https://github.com/Drapegnik/env/blob/master/Brewfile)
* `sh bin/setup.sh`: create symlinks && install packages
