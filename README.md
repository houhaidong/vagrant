# vagrant
 * 官网 https://www.vagrantup.com/
## 基础环境
* VirtualBox 5.1.8
  下载地址 https://www.virtualbox.org/wiki/Download_Old_Builds_5_1
* Vagrant 1.8.6
  下载地址：https://releases.hashicorp.com/vagrant/1.8.6/
## 启动虚拟机
* 方便的`导入导出`功能
    *  直接把一个markdown的文本文件拖放到当前这个页面就可以了
    *  导出为一个html格式的文件，样式一点也不会丢失
* box下载
    *  官网地址：https://www.vagrantup.com
    *  百度云盘地址：http://pan.baidu.com/s/1i5BfL45 密码：himr 或者  https://pan.baidu.com/s/1kU8fUlD
* 添加box 
    *  vagrant box add 目录名 box名称
* 初始化box
    *  vagrant init 名称
    *  vagrant ssh : 以ssh登录box
