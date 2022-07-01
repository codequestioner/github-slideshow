Your GitHub Learning Lab Repository for Introducing GitHub

＃ termux配置
采用原生termux系统，不打算装其他linux发行版
‘’‘
pkg update
pkg install clang python git neovim #基础软件安装
nvim inform.c
clang inform.c
./a.out #运行c程序
