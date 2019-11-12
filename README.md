登入cloudflare	登入cloudflare


API_KEY：右上角点头像，点我的个人资料，最下面的全局 API密钥	API_KEY：右上角点头像，点我的个人资料，在API令牌菜单下找到Global API Key


区域ID：进入域名设置，概述页面下，右下角区域 ID	区域ID：进入域名设置页，概述页面下，找到区域 ID


----------	帐户ID：进入域名设置页，概述页面下，找到帐户ID


获取CFid命令	

找个linux系统某种debian	
```	
易于安装-y curl python	
```	
```	
curl -X GET“ https://api.cloudflare.com/client/v4/zones/修改为zone_id / dns_records” -H“ X-Auth-Email：修改为登录cloudflare的电子邮件” -H“ X-Auth-关键字：修改为API_KEY“ -H”内容类型：application / json“ | python -mjson.tool	
```	
显示结果中	

“ content”：“顶级域名”	

紧接着下面第二行	

“ id”：“ xxxxxxxxxxxxxxxxxxxxxxxxxxxx”	

这个xxxxxxxxxxxxxxxxxxxxxxxxxxxx就是CFid	
