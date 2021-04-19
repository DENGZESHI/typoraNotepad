# Git使用

### Git基础

#### 基本信息设置

1. 设置用户名：

   ```
    git config --global user.name 'sangengliangzhan'
   ```

   

2.  设置用户名邮箱：

   ```
   git config --global user.eamil '779261084@qq.com'
   ```

   

3. 查看设置：

   ```
   git config --list
   ```

   **注意**：git config --global参数，有了这个参数，表示你这台机器上所有的Git仓库都会使用这个配置，当然你也可以对某个仓库指定的不同的用户名和邮箱。

   **脚下留心**：该设置在GitHub仓库主页显示谁提交了该文件。

-------

#### 创建文件夹

1. mkdir 文件名。

2. 在文件内初始化git（建立git仓库）。

   ```
   cd test
   git init
   ```

   *会在test生成一个.git的隐藏文件（用来存储仓库所有信息的）。*

### 向仓库中添加文件

1. 创建文件：

### ![image-20210418183917103](C:\Users\77926\AppData\Roaming\Typora\typora-user-images\image-20210418183917103.png)

2.添加到暂存区：

![image-20210418184202208](C:\Users\77926\AppData\Roaming\Typora\typora-user-images\image-20210418184202208.png)

 3.提交到仓库(从暂存区传到仓库)：

![image-20210418204750003](C:\Users\77926\AppData\Roaming\Typora\typora-user-images\image-20210418204750003.png)

### 修改仓库

1. 修改文件：![image-20210418210135813](C:\Users\77926\AppData\Roaming\Typora\typora-user-images\image-20210418210135813.png)
2. 添加到暂存区：![image-20210418210430224](C:\Users\77926\AppData\Roaming\Typora\typora-user-images\image-20210418210430224.png)
3. 上传到仓库：![image-20210418210756396](C:\Users\77926\AppData\Roaming\Typora\typora-user-images\image-20210418210756396.png)

-------------

### 删除文件

1. 删除文件:

   ```
   rm a1.php 
   ```

​    2.从Git中删除文件：

```
git rm a1.php
```

   3.提交操作：

```
git commit "提交描述"
```

总删除过程：![image-20210418211427748](C:\Users\77926\AppData\Roaming\Typora\typora-user-images\image-20210418211427748.png)



### Git克隆操作

#### 目的

将远程仓库（github对应的项目）复制到本地

代码：

```
git clone 仓库地址
```

仓库地址由来：从github中复制。

![image-20210418212952756](C:\Users\77926\AppData\Roaming\Typora\typora-user-images\image-20210418212952756.png)

---------



### 将本地仓库同步到git远程仓库中

#### 命令

```
git push
```

![image-20210418215855401](C:\Users\77926\AppData\Roaming\Typora\typora-user-images\image-20210418215855401.png)

步骤：

1. 创建文件。
2. 添加到暂存区。
3. 添加到本地仓库。
4. 添加到远程仓库。





### 解决GitHub的push错误

![image-20210418215809672](C:\Users\77926\AppData\Roaming\Typora\typora-user-images\image-20210418215809672.png)

## GitHub Pages 搭建网站

##### 个人站点

##### 访问

https://用户名.github.io

#### 搭建步骤

1. 创建个人站点 -> 新建仓库（注：仓库名必须是【用户名.github.io】）。
2. 在仓库下新建index.html的文件即可。

## 浏览器缓存问题看不到页面

ctrl + shift+delete清除缓存。