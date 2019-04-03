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

* [WINE] is a compatibility layer capable of running Windows applications
* [Docker] for containers
* [Snapd] canonical package manager
* [Git] for version control
* [OpenSSL] for Transport Layer Security (TLS)
* [Guake] to replace a standart terminal
* [Tmux] for saving project state and switching between projects
* [Zsh] as your shell and [Oh-my-Zsh] as brilliant addons

[WINE]: https://www.winehq.org/
[Docker]: https://www.docker.com/
[Snapd]: https://snapcraft.io/
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

Media tools:

* [Simple Screen Recorder] for screen recording
* [ImageMagick] for cropping and resizing images
* [VLC] media player
* [Joxi] for screen capture

[Joxi]: https://joxi.net/
[VLC]: https://www.videolan.org/vlc/index.html
[Simple Screen Recorder]: https://www.maartenbaert.be/simplescreenrecorder/

Testing tools:

* [Qt] for headless JavaScript testing via Capybara Webkit
* [Ngrok] to expose a web server running on your local machine to the internet

[Qt]: http://qt-project.org/
[Ngrok]: https://ngrok.com/

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
* [Redis] for caching

[Postgres]: http://www.postgresql.org/
[Redis]: https://redis.io/

Editors:

* [Sublime Text 3] for developing
* [VS Code] source code editor

[Sublime Text 3]: https://www.sublimetext.com/
[VS Code]: https://code.visualstudio.com/
It should take less than 15 minutes to install (depends on your machine).

## License
ubuntu-laptop-script is Copyright © 2015-2019 Codica. It is released under the [MIT License](https://opensource.org/licenses/MIT).

## About Codica

[![Codica logo](https://www.codica.com/assets/images/logo/logo.svg)](https://www.codica.com)

We love open source software! See [our other projects](https://github.com/codica2) or [hire us](https://www.codica.com/) to design, develop, and grow your product.
