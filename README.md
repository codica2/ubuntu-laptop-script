Laptop
======

Laptop is a script to set up an Ubuntu laptop for web development.

It can be run multiple times on the same machine safely.
It installs, upgrades, or skips packages
based on what is already installed on the machine.

For MacOS please use [https://github.com/thoughtbot/laptop](https://github.com/thoughtbot/laptop)

Requirements
------------

We support:

* Ubuntu 16.04 LTS

Older versions may work but aren't regularly tested. Bug reports for older
versions are welcome.

Install
-------

Download, review, then execute the script:

```sh
curl --remote-name https://raw.githubusercontent.com/codica2/ubuntu-laptop-script/master/linux
sh linux
```

What it sets up
---------------

Unix tools:

* [Git] for version control
* [OpenSSL] for Transport Layer Security (TLS)
* [Guake] to replace a standart terminal
* [Tmux] for saving project state and switching between projects
* [Zsh] as your shell and [Oh-my-Zsh] as brilliant addons

[Git]: https://git-scm.com/
[OpenSSL]: https://www.openssl.org/
[Guake]: http://guake-project.org/
[Tmux]: http://tmux.github.io/
[Zsh]: http://www.zsh.org/
[Oh-my-Zsh]: http://ohmyz.sh/

Heroku tools:

* [Heroku Toolbelt] and [Parity] for interacting with the Heroku API

[Heroku Toolbelt]: https://toolbelt.heroku.com/

GitHub tools:

* [Hub] for interacting with the GitHub API

[Hub]: http://hub.github.com/

Image tools:

* [ImageMagick] for cropping and resizing images

Testing tools:

* [Qt] for headless JavaScript testing via Capybara Webkit

[Qt]: http://qt-project.org/

Programming languages and configuration:

* [Bundler] for managing Ruby libraries
* [Node.js] and [NPM], for running apps and installing JavaScript packages
* [RVM] for managing versions of Ruby
* [Ruby] stable for writing general-purpose code

[Bundler]: http://bundler.io/
[ImageMagick]: http://www.imagemagick.org/
[Node.js]: http://nodejs.org/
[NPM]: https://www.npmjs.org/
[RVM]: https://github.com/sstephenson/rbenv
[Ruby]: https://www.ruby-lang.org/en/

Databases:

* [Postgres] for storing relational data

[Postgres]: http://www.postgresql.org/

It should take less than 15 minutes to install (depends on your machine).
