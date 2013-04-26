# Hey Rails developers!

Julian Giuca (@juliangiuca) and Andrew Bloomgarden (@aughr) spoke about how New Relic upgraded to Rails 3 on master at RailsConf 2013. These files were extracted from that work to help you make that same move.

## Bundler patch

* [lib/bundler/lockfile_dsl.rb](lib/bundler/lockfile_dsl.rb)

## Boot sequence

* [config/boot.rb](config/boot.rb)
* [config/application.rb](config/application.rb)
* [config/environment.rb](config/environment.rb)

## An example environment-specific config file

* [config/environments/development.rb](config/environments/development.rb)

## Running a server

* [server3](script/server3)
* [config\_rails3.ru](config_rails3.ru)
