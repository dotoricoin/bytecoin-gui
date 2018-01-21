## Build: Ubuntu 16.04 LTS
- `sudo apt-get update && sudo apt-get upgrade --yes`
- `git clone https://github.com/dotoricoin/dotoriwallet`
- `git clone https://github.com/dotoricoin/dotoricoin`
- `cd dotoriwallet`
- `ln -s ../dotoricoin/ cryptonote`
- `mkdir build && cd build`
- `cmake ..`
- `make`
