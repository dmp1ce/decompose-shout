Shout environment for decompose intended to help quickly start a Shout server and a Let's Encrypt certificate. Because this project uses Docker instead of a virtual machine, the website is suitable for production as well as development and testing!

# Requirements

- [Decompose](https://github.com/dmp1ce/decompose)
- [Docker](http://www.docker.com/)
- [Docker Compose](http://docs.docker.com/compose/)

# Quick Start

``` bash
# Initialize
decompose --init https://github.com/dmp1ce/decompose-murmur.git

# build and start
decompose build && decompose up

# TODO: add instructions on configuring shout
```
