# 点兔友链

## 起源 [tedezarize.com](http://tedezarize.com)

只是因为很有趣  
* 天天座理世 `tedezarize.com` 起源  
* 保登心爱 `hotococoa.com` 已加入  
* 间桐纱路 `kirimasharo.com` 已加入
* 间桐纱路 `kirimasyaro.com` 联系不上
* 香风智乃 `kafuuchino.com` 联系不上  
* 宇治松千夜 `ujimatsuchiya.com` 域名在售中  

谁知道如何联系  
如果你喜欢千夜 可以加入我们  

## 使用 

修改`index.html` 最后的`<script>` 大概在80多行  
my_site、text 颜色什么的 自己改  
rabbit 记录了各个网站的信息  
* imgsrc    人物图片url  默认url  
* imghref   点击头像跳转页面  
* imgsrc_cn 人物图片url 中国图床 如果浏览器语言为`zh-CN`会从这个链接获取  
* access 连接状态 网站可以访问填200 不能访问的随便写

如果`my_site`不在`rabbit`不会做任何事情

需要Google-analytics可以取消注释 我们都没用过...

添加不蒜子访问量计数器 不需要的话可以删除 `div[@class="count"]`  
* pv 每访问一次+1
* uv 每一个用户只+1