
使用介绍:
安装全部依赖
npm i
同时全局安装pm2
npm install -g pm2

开启服务
npm start 

访问案例
http://localhost/rest/schedule
出来如下,代表成功运行
```js
[
{
"station": "北京南",
"arriveTime": null,
"departTime": "07:20",
"stay": null
},
{
"station": "天津南",
"arriveTime": "07:54",
"departTime": "07:56",
"stay": 2
},
{
"station": "南京南",
"arriveTime": "11:51",
"departTime": "11:53",
"stay": 2
},
{
"station": "上海虹桥",
"arriveTime": "13:08",
"departTime": null,
"stay": null
}
]
```



