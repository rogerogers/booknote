docker
######

docker 

安装
====

* windows

  docker 一般运行在类unix环境下

  * 系统要求

    Windows 10 Pro/ Enterprise / Edication 64位，且需要启用Hyperf-v功能和容器特性





* linux

::

  wget -qO- https://get.docker.com/ | sh

非root用户运行docker命令需要添加用户到docker组，以example用户为例

::

  sudo usermod -aG docker example

重新登陆即可用非root用户操作docker命令

::

  docker --version
