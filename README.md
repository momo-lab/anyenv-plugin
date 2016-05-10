# anyenv-plugin

This [anyenv](https://github.com/riywo/anyenv) plugin that provides ```anyenv plugin-install``` command to install anyenv or **env plugins.


## Usage example

To install plugin:

    $ anyenv plugin-install <*env> <github-user/repo>

In the case of plugin that begin with *env-, <*env> is optional.

    $ anyenv plugin-install <github-user/repo>

Install [rbenv-update](https://github.com/rkh/rbenv-update) for rbenv:

    $ anyenv plugin-install rbenv rkh/rbenv-update

Same as this:

    $ anyenv plugin-install rkh/rbenv-update


## Installation

    mkdir -p "$(anyenv root)"/plugins
    git clone https://github.com/momo-lab/anyenv-plugin.git "$(anyenv root)"/plugins/anyenv-plugin

## License

MIT
