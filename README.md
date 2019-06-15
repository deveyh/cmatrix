#黑客下雨桌面

yum -y install gcc

yum -y install gcc-c++

yum install make

yum install ncurses-devel

tar xf cmatrix-1.2.tar.gz /usr/local/cmatrix

cd /usr/local/camtrix

./configure && make && make install


cmatrix命令运行
cmatrix常用命令如下:
cmatrix-a :异步滚动（默认）
cmatrix-b :随机粗体
cmatrix-B :全部粗体
cmatrix-o :使用旧风格滚动
cmatrix-x :X window 模式
cmatrix-V :显示版本信息
cmatrix-u :刷新频率，0-9
cmatrix-C :显示的颜色 （例如cmatrix -C green ）

经过测试,命令复制无效

