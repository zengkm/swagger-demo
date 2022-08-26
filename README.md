## 安装和运行
```javascript
$ cd swagger-demo
$ npm install
$ node start.js
```
## 服务管理
利用pm2方便服务管理维护。
```javascript
$ npm install pm2 -g  //安装pm2
$ cd swagger-demo
$ pm2 start swagger-demo 
```
## 使用
* 修改api.yaml
  ```javascript
  vim api.yaml
  ```
* 重启服务，swagger json就会变更
  ```javascript
  pm2 start swagger-demo
  ```
