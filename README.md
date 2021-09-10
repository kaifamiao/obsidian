"# obsidian" 
# obsidian

# 安装NODE.JS

## 下载安装Node.js

http://nodejs.cn/download/

![image-20210817202254189](C:\Users\linrui\AppData\Roaming\Typora\typora-user-images\image-20210817202254189.png)

![image-20210817202317909](C:\Users\linrui\AppData\Roaming\Typora\typora-user-images\image-20210817202317909.png)

![image-20210817202327492](C:\Users\linrui\AppData\Roaming\Typora\typora-user-images\image-20210817202327492.png)

![image-20210817202344828](C:\Users\linrui\AppData\Roaming\Typora\typora-user-images\image-20210817202344828.png)

### 命令测试是否安装成功

![image-20210817202457481](C:\Users\linrui\AppData\Roaming\Typora\typora-user-images\image-20210817202457481.png)

## 设置环境变量

### 首先在node.js的安装目录新建两个文件夹node_global和node_cache

![image-20210817202712431](C:\Users\linrui\AppData\Roaming\Typora\typora-user-images\image-20210817202712431.png)

### 创建完两个文件夹后，在cmd窗口中输入以下命令（两个路径即是两个文件夹的路径）：

```bash
npm config set prefix "c:\nodejs\node_global"
npm config set cache "c:\nodejs\node_cache"
```

![image-20210817202802611](C:\Users\linrui\AppData\Roaming\Typora\typora-user-images\image-20210817202802611.png)

![image-20210817202835569](C:\Users\linrui\AppData\Roaming\Typora\typora-user-images\image-20210817202835569.png)



## 在【系统变量】新建环境变量 NODE_PATH，值为

>  C:\nodejs\node_global\node_modules，其中C:\nodejs\node_global是上述创建的全局模块安装路径文件夹



![image-20210817203021797](C:\Users\linrui\AppData\Roaming\Typora\typora-user-images\image-20210817203021797.png)

### 5.修改【用户变量】中的path变量



> 将C:\Users\linrui\AppData\Roaming\npm修改为C:\nodejs\node_global





![image-20210817203232871](C:\Users\linrui\AppData\Roaming\Typora\typora-user-images\image-20210817203232871.png)



![image-20210817203328317](C:\Users\linrui\AppData\Roaming\Typora\typora-user-images\image-20210817203328317.png)

![image-20210817203420447](C:\Users\linrui\AppData\Roaming\Typora\typora-user-images\image-20210817203420447.png)



## 国内镜像

npm install -g cnpm --registry=https://registry.npm.taobao.org



![image-20210817203506766](C:\Users\linrui\AppData\Roaming\Typora\typora-user-images\image-20210817203506766.png)

![image-20210817203534151](C:\Users\linrui\AppData\Roaming\Typora\typora-user-images\image-20210817203534151.png)


