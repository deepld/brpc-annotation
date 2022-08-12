## mac 下必须按顺序执行依赖安装

不按顺序，可能导致 THRIFTNB_LIB 找不到

brew install libevent
brew install thrift

## Example 依赖于已经 install 的brpc
