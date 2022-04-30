# rossta安装

1.解压rosseta

tar -xzvf rosseta.tar

编译前的准备

安装c++

sudo apt install c++

sudo apt install cmake

```bash
sudo apt install c++

sudo apt install cmake
sudo apt install zlib1g-dev
#进行编译
sudo ./scons.py -j 4 mode=release bin
#设置环境变量
export $rosetta3='加bin路径'
export $rosetta3_db='db路径'
export $rosetta3_tools='tools路径'
```

