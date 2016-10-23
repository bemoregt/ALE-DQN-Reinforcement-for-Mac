# ALE-DQN-Reinforcement-for-Mac
Atari game ReinforceLearning for Mac(El Capitan/Sierra)

# Install torch for mac
see my neural-style install github posting.

# Install dependency

$ luarocks nn
$ luarocks install cwrap
$ luarocks install paths
$ luarocks install torch
$ luarocks install nn

$ luarocks install luafilesystem
$ luarocks install penlight
$ luarocks install sys
$ luarocks install xlua
$ luarocks install image
$ luarocks install env
$ luarocks install qtlua
$ luarocks install qttorch

if you have CUDA/eGPU in Mac(if only cpu, Skip this.)
$ luarocks install cutorch
$ luarocks install cunn

# Install xitary

$ cd /tmp
$ git clone https://github.com/deepmind/xitari.git
$ cd xitary
$ luarocks make

# Install alewarp

$ cd /tmp
$ git clone https://github.com/deepmind/alewrap.git
$ cd alewrap
$ luarocks make

# Changing qlua path to your qlua path

$ which qlua

$ mcedit run_cpu
...
/usr/local/bin/qlua
...
save

# Install DeepMind_DQN
$ git clone https://github.com/kuz/DeepMind-Atari-Deep-Q-Learner

# run

$ cd DeepMInd-Atari-

$ ./run_cpu breakout
