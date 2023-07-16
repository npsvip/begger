# Begger
在线乞讨全球要饭项目,支持docker一键部署，支持企业微信通知，支持文案编辑

# 前端
<img width="1678" alt="image" src="https://github.com/npsvip/begger/assets/95081538/8722a675-d8d0-4e97-a8f9-b9540371f0d0">

# 后端
<img width="1678" alt="image" src="https://github.com/npsvip/begger/assets/95081538/8473920c-387f-4c80-9e71-4c9caf92a53d">

<img width="1679" alt="image" src="https://github.com/npsvip/begger/assets/95081538/b00e1b6a-2e51-4231-94c7-03809156dbe0">

<img width="1678" alt="image" src="https://github.com/npsvip/begger/assets/95081538/d3bee593-ad68-43e2-88b7-5558b7e2914f">

<img width="1676" alt="image" src="https://github.com/npsvip/begger/assets/95081538/1baa0106-f6d6-457b-81ed-f2a7250b8742">

# 运行命令
```
docker run -d --name beggar --restart=always -p 8080:8080 -e console=true -v /opt/beggar/log/:/beggar.mv.db  -v /opt/beggar/log/:/opt/logs/beggar/ aeert/beggar:latest
```
日志目录&nbsp;&nbsp;&nbsp;&nbsp;/opt/logs/beggar/<br/>
H2数据库&nbsp;&nbsp;&nbsp;&nbsp;/beggar.mv.db 

# 支付平台
目前对接的是&nbsp;&nbsp;<a href="https://pay.npsvip.cn" target="_black">蓝鲸支付</a>
