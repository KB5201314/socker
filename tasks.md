# 大作业:开发一个容器引擎

- 实验目的:

    - 利用Linux操作系统的Namespace和Cgroup机制,实现一个简单的容器引擎,开发语言不限(shell脚本、C、Python等都可以)

- 实验要求:

    - 容器引擎应具有以下功能:
        
        - 实现进程、用户、文件系统、网络等方面的隔离
        - 能够在Ubuntu系统上运行CentOS环境
        - 能够实现同一操作系统下两个容器之间的网络通信
        - 能够为容器分配定量的CPU和内存资源

- 实验报告要求
    1. 容器引擎的源代码

    2. 容器引擎的实现说明

    3. 容器引擎支持容器隔离性、两个容器之间通信连通性、容器资源定量分配等三个核心功能的证明材料,如实验截图和说明文字