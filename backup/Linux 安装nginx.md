### 安装
`sudo apt-get install nginx`

### 重启nginx
`systemctl restart nginx `

### 编写配置
[ispweb.zip](https://github.com/BalsamPearTaste/BalsamPearTaste.github.io/files/13667355/ispweb.zip)
ispweb.conf复制 过去/etc/nginx/conf.d/ispweb.conf
调整对应ip、端口和路径
#vim /etc/nginx/conf.d/ispweb.conf
vim /etc/nginx/nginx.conf
#       include /etc/nginx/sites-enabled/*;   #注释该行

### 验证配置
`nginx -t `

### nginx文件路径：

- /usr/sbin/nginx：主程序
- /etc/nginx：存放配置文件
- /usr/share/nginx：存放静态文件
- /var/log/nginx：存放日志