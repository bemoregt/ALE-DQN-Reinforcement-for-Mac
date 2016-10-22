# ALE-DQN-Reinforcement-for-Mac
Atari game ReinforceLearning for Mac(El Capitan/Sierra)

# Install dependency
$ luarocks nn
...
etc 

# Install xitary

$ cd /tmp
$ git clone xitary git address
$ cd xitary
$ luarocks make

# Install alewarp

$ cd /tmp
$ git clone alewrap git address
$ cd alewrap
$ luarocks make

# Changing qlua path

$ mcedit run_cpu
...
/usr/local/bin/qlua
...
save

# Install DeepMind_DQN
$ git clone DeepMind_SQD git adress
# run

$ ./run_cpu breakout
