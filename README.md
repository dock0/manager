**Inactive Project:** I've stopped using this project in favor of building packages on CircleCI

dock0/manager
=======

[![Automated Build](https://img.shields.io/docker/build/dock0/manager.svg)](https://hub.docker.com/r/dock0/manager/)
[![Build Status](https://img.shields.io/travis/com/dock0/manager.svg)](https://travis-ci.com/dock0/manager)
[![MIT Licensed](http://img.shields.io/badge/license-MIT-green.svg)](https://tldrlegal.com/license/mit-license)

Build manager for running builds via [my build container](https://github.com/dock0/manager)

## To launch

```
docker run -d -P -v /var/lib/dock0-manager:/var/lib/dock0-manager -v /var/run/docker.sock:/var/run/docker.sock dock0/manager
```

## License

This repo is released under the MIT License. See the bundled LICENSE file for details.

