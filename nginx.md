### 安装
    yum install nginx
### nginx配置
    vim /etc/nginx/nginx.conf
netstat -ntlp //查看启动tcp端口
netstat -ntulp | grep 80  查看80端口

### 文件目录
    创建：mkdir xxx
    查看：df -h

## 查看Node进程
    ps aux | grep node