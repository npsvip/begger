# Begger
在线乞讨全球要饭项目,支持docker一键部署，支持企业微信通知，支持文案编辑

# 前端
<img width="1678" alt="image" src="https://github.com/npsvip/begger/assets/95081538/8722a675-d8d0-4e97-a8f9-b9540371f0d0">

# 后端
<img width="1678" alt="image" src="https://github.com/npsvip/begger/assets/95081538/8473920c-387f-4c80-9e71-4c9caf92a53d">

<img width="1679" alt="image" src="https://github.com/npsvip/begger/assets/95081538/b00e1b6a-2e51-4231-94c7-03809156dbe0">

<img width="1678" alt="image" src="https://github.com/npsvip/begger/assets/95081538/d3bee593-ad68-43e2-88b7-5558b7e2914f">

<img width="1678" alt="image" src="https://github.com/npsvip/begger/assets/95081538/68cf6e68-85d9-4d71-b695-3e86efd23b86">

<img width="1677" alt="image" src="https://github.com/npsvip/begger/assets/95081538/6011a1ed-035f-4749-ba32-c4ef227702cf">

<img width="1677" alt="image" src="https://github.com/npsvip/begger/assets/95081538/171f9005-2678-4ca5-b90b-fdbf0b36efb1">

# H2 console
<img width="458" alt="image" src="https://github.com/npsvip/begger/assets/95081538/f03147ff-241b-415e-bf5b-2c561a6f902f">

<img width="1678" alt="image" src="https://github.com/npsvip/begger/assets/95081538/2ede27d6-1789-4cd4-a1bf-f5d2b5ddf623">


# 运行命令
```
docker run -d --name beggar --restart=always -p 8080:8080 -e console=true -v /opt/beggar/log/:/opt/logs/beggar/ aeert/beggar:latest
```
日志目录&nbsp;&nbsp;&nbsp;&nbsp;/opt/logs/beggar/<br/>
H2 console&nbsp;&nbsp;&nbsp;true 打开<br/>
H2数据库&nbsp;&nbsp;&nbsp;&nbsp;/beggar.mv.db 

# 访问信息
前端地址&nbsp;&nbsp;&nbsp;&nbsp;http://localhost:8080<br/>
后端地址&nbsp;&nbsp;&nbsp;&nbsp;http://localhost:8080/admin/<br/>
后端账户密码&nbsp;&nbsp;随意输入，之后会保存H2数据库
H2 console&nbsp;&nbsp;JDBC URL: jdbc:h2:./beggar

# 支付平台
目前对接的是&nbsp;&nbsp;<a href="https://pay.npsvip.cn" target="_blank">蓝鲸支付</a>
