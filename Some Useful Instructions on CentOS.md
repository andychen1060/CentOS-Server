### Some Useful Instructions on CentOS<br/>
<hr/>
#### Summary<br/>
Noting some useful instructions used to manage CentOS operating system.<br/>

#### System Environment.<br/>
● Operating System: CentOS 6.8 LTS<br/>

####Instructions<br/>
●主機防火牆設定<br/>
查閱目前防火牆的設定狀況
```
sudo /etc/init.d/iptables status
```
修改防火牆設定並重新啟動，使新的設定規則生效
```
sudo vi /etc/sysconfig/iptables  
sudo service iptables restart
```
●安裝Telnet軟體<br/>
```
yum install telnet -y
```
安裝後可以如下使用telent:
```
telnet IP_address Port_number
```
