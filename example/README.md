## mac 下必须按顺序执行依赖安装?

    不按顺序，可能导致 THRIFTNB_LIB 找不到; 似乎都安装了也米有效果
    
    brew install libevent
    brew install thrift

## mac下编译方式
    不通过clion，清空camke cache后，命令行上 cmake..
    然后再到clion中直接 rebuild all in debug

## Example 依赖于已经 install 的brpc
