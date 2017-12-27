# git for mac
> what we need to do is just install a tool named **Command Line Tools**
```
//open the terminal,and type
xcode-select --install enter
//test 
gcc -v
//if it shows below message, then it's installed.
xcode-select: note: install requested for command line developer tools
apple-1tekiiMac:~ apple-1$ gcc -v
Configured with: --prefix=/Applications/Xcode.app/Contents/Developer/usr --with-gxx-include-dir=/usr/include/c++/4.2.1
Apple LLVM version 6.1.0 (clang-602.0.49) (based on LLVM 3.6.0svn)
Target: x86_64-apple-darwin14.3.0
Thread model: posix
```
首先配置自己的身份，这样在提交代码的时候就能知道是谁提交的
```
输入git config --global user.name "名字"

git config --global user.email "邮箱地址"
输入git init就可以创建啦~
然后使用ls -al查询代码仓库，如果想删除这个仓库，直接从目录下删除这个文件夹就可以了
仓库建立完成之后就可以提交本地代码了，这里只需要用到两个命令，add添加和commit提交
add .是提交所有
add +文件名是提交单个文件
git commit -m "First commit"是提交这里要在-m参数后面加上提交参数，很重要哟，不然会被认为不合法不能提交.
```

