## Building Seastar on Ubuntu

### Building seastar on Ubuntu 14.04/15.10/16.04

Installing required packages:
```
sudo ./install-dependencies.sh
```

Now, only g++-7 supported, to compile Seastar explicitly using gcc 7, use:
```
./configure.py --compiler=g++-7
ninja
```
