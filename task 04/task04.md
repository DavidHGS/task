# 第四周任务
## 安装虚拟机
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/08.jpg)
###### 打开安装界面
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/02.jpg)
###### 选择下载的安装光盘镜像
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/03.jpg)
###### 选择windows servers2003安装的位置
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/04.jpg)
###### 虚拟机安装完成
***


## 安装并配置iis
###### 选择虚拟机->设置
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/05.jpg)
###### 重复该步骤，勾选后确定
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/06.jpg)
###### 出现这个界面
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/07.jpg)
###### 右击 我的电脑 选择管理->用户
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/28.jpg)
###### 选择新用户，完成下面的操作 点创建 
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/29.jpg)
###### 选择刚刚创建的新用户
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/30.jpg)
###### 再隶属于里面 删除里面的uers 再点添加
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/31.jpg)
###### 点击立即查找 完成操作后 确定
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/32.jpg)
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/33.jpg)
###### 新用户设置成功

---
###### 开始->管理工具->internet---管理器->发送到->桌面快捷方式
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/14.jpg)
###### 打开iss管理器
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/15.jpg)
###### 开始创建一个新网站
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/16.jpg)
###### 输入网站描述
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/17.jpg)
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/18.jpg)
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/19.jpg)
###### 点下一步 最后完成网页创建
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/20.jpg)
###### 右击新创建的网站 开始网站配置
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/21.jpg)
###### 
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/22.jpg)
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/23.jpg)
###### 选择目录安全性
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/24.jpg)
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/25.jpg)
###### 点浏览->高级->立即查找
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/26.jpg)
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/27.jpg)
###### iss配置完成

---


##搭建基本新闻站点 并上传网页
打开虚拟机c盘中的风讯5.0中的Templets
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/34.jpg)
###### 打开iss管理器里面的yzadmin，找到login.asp 右击浏览
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/35.jpg)
###### 出现该界面 复制地址栏中的网址
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/36.jpg)
###### 在主机中的ie浏览器中打开改网址 并摁F12打开开发者工具将ie浏览器降级为ie7
###### 输入用户名admin 密码123456 登录
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/37.jpg)
###### 点开参数设置
###### ![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/38.jpg)在模板中文本编辑html文件，打开后会出现乱码，用网页原代码覆盖掉乱码，并且将（charset）utf-8改为gb2312
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/39.jpg)
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/40.jpg)
###### 点开栏目管理 创建根栏目
###### 输入栏目中文名称  在这里列表网页list为模板
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/41.jpg)
###### 在这里选择contant为模板
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/42.jpg)
###### 返回网页编辑 在link里 加 /Templist/
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/43.jpg)
###### 点开发布管理->发布所有栏目
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/44.jpg)
###### 在打开标签库开始创建标签
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/45.jpg)
###### 点开新闻列表
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/46.jpg)
###### 打开发布管理
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/47.jpg)
###### 打开网页地址
可能由于版本原因
在ie 9 10 11显示的是正常的
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/48.jpg)
在ie7上显示为这样
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/49.jpg)
###### 点开标签库 开始创建标签
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/50.jpg)
###### 创建通知公告标签
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/51.jpg)
###### 创建列表页通用标签
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/53.jpg)
###### 按图示进行设置
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/54.jpg)
###### 创建内容页标签
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/52.jpg)
###### 点开样式管理中的新闻显示
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/55.jpg)
###### 点开样式管理中的有日期列表
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/58.jpg)
###### 开始在模板中插入标签
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/56.jpg)
###### 在index页中插入标签
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/57.jpg)
###### 在list页中插入标签
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/59.jpg)
###### 打开发布管理 开始添加新闻
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/60.jpg)
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/63.jpg)
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/64.jpg)
###### 打开新建的新闻网站
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/61.jpg)
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/62.jpg)
###### 开始添加more标签
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/65.jpg)
###### 在list页中添加more标签
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/66.jpg)
###### 再次打开该网页
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/67.jpg)
###### 点击more标签  出现网页 表明more标签创建成功
![image](https://raw.githubusercontent.com/DavidHGS/task/master/task%2004/imgage/68.jpg)

