# mythree

## Project setup
```
npm install
```

### 项目启动
```
npm run dev
```

### Compiles and minifies for production项目构建
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
6、主要项目页面

1. 登录  
2. 主页
3. 案例
   * 表格1 
   * 表格2   

7、换行

 1.前端在本地写好路由表，以及每个路由对应的角色，也就是哪些角色可以看到这个菜单/路由

2.登录的时候，向后端请求得到登录用户的角色(管理者、普通用户)；

3.利用路由拦截，根据取到的用户角色,跟本地的路由表进行对比，过滤出用户对应的路由，并利用路由进行左侧菜单渲染  

8、引用

> 菜单栏用的控件
>
> https://element.eleme.cn/#/zh-CN/component/menu
>
> 路由拦截
>
> https://router.vuejs.org/zh/api/#router-addroute


### 项目流程图
![avatar](/process.png)