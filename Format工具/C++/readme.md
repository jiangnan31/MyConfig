#说明

Format工具：AStyle
依赖环境：LINUX
安装部署： 
(1) 下载http://styleguide.baidu.com/style/cpp/resources/install_astyle.sh 
(2) sh install_astyle.sh 
(3) source ~/.bashrc
使用方法： 
修改单个文件：astyle main.cpp 
修改整个目录之下的cpp代码，包括全部子目录：astyle -R "*.cpp"