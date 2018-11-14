# centos 64 位上测试安装nginx    

请确认gcc g++开发类库是否装好，如果没有，先进行如下操作：    
安装make：    
yum -y install gcc automake autoconf libtool make     
安装g++:    
yum install gcc gcc-c++    

## 一、选定安装文件目录    
我选择的目录是 /apps/, 在根目录下建立了一个apps目录，放在这个目录下。然后依次执行如下命令：    
cd apps    
wget ftp://ftp.csx.cam.ac.uk/pub/software/programming/pcre/pcre-8.39.tar.gz   
cd pcre-8.39    
./configure    
make    
make install    



   
