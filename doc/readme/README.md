#### 功能使用设计图

- ##### 加载插件

![image](https://github.com/guojingyinan219/pushplus/blob/master/doc/images/1.png)

- #####  配置全局参数

![image](https://github.com/guojingyinan219/pushplus/blob/master/doc/images/2.png)

- ##### 每个项目配置参数，不同的项目推到不同的群组

![image](https://github.com/guojingyinan219/pushplus/blob/master/doc/images/3.png)


- ##### jenkins pipeline 配置
```sh
 post {
        always {
         
            pushplus (
                "你的群组"
            )
            
        }
    

    }
```
  
