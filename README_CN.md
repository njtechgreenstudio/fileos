# 文件系统

 简单的文件系统是基于ext和c++的. 他在Linux平台上的亲和性更好一些.

`fielesystem-1.0.tar.gz` 是我相对于常规文件系统制作的优化版本. 我写了一个 `makefile` 脚本, 使得这个文件系统可以被轻松地编译出来.

## Fn directory 文件系统

这个文件系统的架构如下图. 和以往文件系统不同的是, 它缺少了组描述符(group descriptors)和保留的组描述符表占用块(Reserved GDT block).

 ![](/picture/architecture.png)

 本文件系统的树状结构: 

 ![](/picture/tree.png)

如果你想要编译运行这个项目, 你只需要在本项目根目录下, 终端输入 `make`

 ![](/picture/make.png)

 如果你只是想要运行这个文件系统, 你只需要在本项目根目录下, 终端输入 `make run`

 ![](/picture/run.png)

 如果你想要删除一个文件的话, 输入 `make clean`

 ![](/picture/clean.png)**

如果你想要找回你在这个文件系统内的用户名和密码, 输入 `make accountback`

 ![](/picture/accountback.png)

## 文件系统功能一览

```
help                                         ---  展示帮助菜单 

clear                                        ---  清除屏幕信息 

ls                                           ---  列出目录子目录的摘要

ls -l                                        ---  列出目录子目录的详细信息

cd                                           ---  更换目录

mkdir                                        ---  创建目录 

touch                                        ---  创建新文件

cat                                          ---  读取文件

write                                        ---  在文件内写入内容

rm                                           ---  删除一个目录或文件

mv                                           ---  重命名文件或者目录

chmod                                        ---  修改一个文件或文件夹的权限

exit                                         --- 退出
```

