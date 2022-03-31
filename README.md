# ubuntu-in-termux

### Ubuntu 20.04.4

ubuntu_20.04.4.sh 文件基于 [https://github.com/MFDGaming/ubuntu-in-termux/blob/ubuntu20.04.3/ubuntu.sh](https://github.com/MFDGaming/ubuntu-in-termux/blob/ubuntu20.04.3/ubuntu.sh)  
将原代码中使用 Ubuntu 官方镜像改为清华大学镜像，不再需要科学上网也能在 Termux 上部署 Ubuntu  

使用说明  
```bash
pkg update

# 安装依赖
pkg install -y wget proot git wget openssl curl

# 下载源码
cd ~ && git clone https://github.com/IYATT-yx/ubuntu-in-termux.git --depth=1

# 部署安装
cd ubuntu-in-termux && chmod a+x ubuntu_20.04.4.sh && ./ubuntu_20.04.4.sh

# 启动 Ubuntu 20.04.4
./startubuntu.sh
```

