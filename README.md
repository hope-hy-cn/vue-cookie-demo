# vue-cookie-demo

> vue项目实现表单登录页保存账号和密码到cookie功能

### 实现功能： 
1.记住密码勾选，点登陆时，将账号和密码保存到cookie，下次登陆自动显示到表单内

2.不勾选，点登陆时候则清空之前保存到cookie的值，下次登陆需要手动输入 
>大体思路就是通过存/取/删cookie实现的；每次进入登录页，先去读取cookie，如果浏览器的cookie中有账号信息，就自动填充到登录框中，存cookie是在登录成功之后，判断当前用户是否勾选了记住密码，如果勾选了，则把账号信息存到cookie当中.

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run all tests
npm test
```








