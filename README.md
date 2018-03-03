## Overview

A deep reinforcement learning project based on [Gym-TORCS](https://github.com/ugo-nama-kun/gym_torcs) and
[DDPG-Keras-Torcs](https://github.com/yanpanlau/DDPG-Keras-Torcs).

## Requirements
We are assuming you are using Ubuntu 14.04 LTS/16.04 LTS machine and installed
* Python 3
* xautomation (http://linux.die.net/man/7/xautomation)
* OpenAI-Gym (https://github.com/openai/gym)
* numpy
* vtorcs-RL-color (installation of vtorcs-RL-color is explained in vtorcs-RL-color directory)

## Dependencies

- Ubuntu 16.04
- Python3
- xautomation (http://linux.die.net/man/7/xautomation)
- OpenAI-Gym (https://github.com/openai/gym)
- numpy
- OpenCV3.x

## Build

```bash
$ mkdir -p ~/gym_torcs
$ cd ~/gym_torcs/
$ git clone --recursive https://github.com/htsai51/gym_torcs.git
$ cd ~/gym_torcs/vtorcs-RL-color
$ ./configure
$ make -j4
$ sudo make install
$ sudo make datainstall
```

## Run

```bash
```