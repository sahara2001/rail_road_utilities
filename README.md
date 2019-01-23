### Installation Guide

#### System
- Ubuntu 16.04
- Ruby 2.5.0

#### Environment Setup
1. Install dependencies of c++ component:
~~~bash
sudo apt-get update
sudo apt-get install libopenal1 libopenal-dev libsndfile-dev libmpg123-dev libfontconfig-dev libsdl2-dev libsdl2-ttf-dev
~~~
2 Install gosu using `gem install gosu`

#### Test Your Gosu Build
1. You should see a black window after executing the following command.
~~~shell
ruby trial.rb
~~~
