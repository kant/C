# C

> C language

## C11

> C11（也被称为C1X）指ISO标准ISO/IEC 9899:2011，是当前最新的C语言标准。在它之前的C语言标准为C99。

```sh
$ gcc -v
# Configured with: --prefix=/Applications/Xcode.app/Contents/Developer/usr --with-gxx-include-dir=/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX.sdk/usr/include/c++/4.2.1
# Apple clang version 11.0.3 (clang-1103.0.32.62)
# Target: x86_64-apple-darwin19.5.0
# Thread model: posix
# InstalledDir: /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin

```

```sh
# gcc --help
$ gcc --help | echo > gcc-help.md

```

```sh
# 编译
$ gcc hello-world.c

# 执行
$ ./a.out
# Hello, World!


$ gcc hello-world.c -o hello-world.out
$ ./hello-world.out

```

```sh
# 多个 c 代码的源码文件，编译
$ gcc test1.c test2.c -o main.out

# 执行
$ ./main.out

# bug
# duplicate symbol '_main' in:
# /var/folders/qm/csrtpvpn62x82v4zykvsrnw80000gn/T/test1-4914ae.o
#     /var/folders/qm/csrtpvpn62x82v4zykvsrnw80000gn/T/test2-cbdd6c.o
# ld: 1 duplicate symbol for architecture x86_64
# clang: error: linker command failed with exit code 1 (use -v to see invocation)
```



## refs

https://www.runoob.com/cprogramming/c-program-structure.html

https://www.runoob.com/cprogramming/c-header-files.html
