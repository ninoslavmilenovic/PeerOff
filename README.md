# PeerOff #

[![Build Status](https://travis-ci.org/pythogorian/PeerOff.svg?branch=develop)](https://travis-ci.org/pythogorian/PeerOff)

Secure P2P RTC Communication Tool

## Development ##
```bash
~$ git clone git@github.com:pythogorian/PeerOff.git
```

```bash
~$ cd PeerOff
```

```bash
# make sure you are using ruby 2.1.2
PeerOff$ bundle install --path vendor/bundle
PeerOff$ cp config/database.yml.example config/database.yml
# configure database connection in config/database.yml
PeerOff$ cp config/secrets.yml.example config/secrets.yml
# configure secret keys in config/secrets.yml
PeerOff$ bundle exec rake db:create
PeerOff$ bundle exec rake db:migrate
PeerOff$ bundle exec rake db:seed
PeerOff$ bundle exec rspec
# all tests should pass
PeerOff$ bundle exec foreman start
# point your web browser to http://localhost:3000/
```

### Copyright ###
Copyright (c) 2014 Ninoslav Milenović

See LICENSE.txt for details.