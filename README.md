![icon](https://github.com/Mran/neno/blob/master/dist/assets/neno.ico)

![](https://visitor-badge.glitch.me/badge?page_id=neno)

NENO
=============

仿照[浮墨](https://flomoapp.com/)的开源版本
- svelte+tailwindcss构建的PWA应用
- 基本功能上与[浮墨](https://flomoapp.com/)保持相同
- 后端地址[Neno-HW-serverless](https://github.com/Mran/Neno-HW-serverless),使用NodeJs构建.
- 后端支持华为云的函数工作流(serverless),可一键部署,每日1000次免费调用,超出需绑定备案过的域名才能享受免费额度
- 图库使用七牛云,免费的10Gb空间,需绑定域名
- 数据库MongoDB,可以使用[https://cloud.mongodb.com/](https://cloud.mongodb.com/)的免费500 Mb的存储空间
- 理论上买一个域名即可免费私有化部署.

[马上体验](http://neno.topmini.top/)
- **支持完全离线使用**
- **支持完整版数据导入导出**



### 前端部署方式

#### 马上部署

    dist目录下面为打包好的文件
    直接部署即可

#### 自己打包
```
npm install
node run build
dist 目录下面为构建好的前端页面
```

### Todo

- [x] 分享出图片  
- [X] 完全基于浏览器的离线版本
- [ ] 每日回顾
- [ ] 随机漫步
- [ ] go版本的后端


![](https://github.com/Mran/neno/blob/master/readmepic/%E9%A6%96%E9%A1%B5.png)
![](https://github.com/Mran/neno/blob/master/readmepic/%E9%A6%96%E9%A1%B5%E7%A7%BB%E5%8A%A8%E7%AB%AF.png)
![](https://github.com/Mran/neno/blob/master/readmepic/%E7%88%B6%E7%BA%A7.png)
![](https://github.com/Mran/neno/blob/master/readmepic/setting.png)



=============

## License

GPL

