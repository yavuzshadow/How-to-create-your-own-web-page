# How-to-create-your-own-web-page
这个项目会手把手教你如何通过内网穿透来建设你自己的网站，且不花你一分一毛，全程完全免费（除非你想付钱）  

### 1.编写自己的网页

这一步较为简单，学过一点HTML的人都可以做，完全没有接触的小白也可以通过AI代码生成来完成。  
下面来编写一个很简单的网页文件（你当然可以不这样干），右键电脑某个位置新建一个记事本，打开该文本文档，复制下面的代码进去，保存。  
![屏幕截图 2025-04-05 063221](https://github.com/user-attachments/assets/7ac91d54-110d-41c9-bcf7-e88444498658)
编辑完后，将记事本的扩展名换为.html，双击打开，一个很基础的网站就建成了。  
![屏幕截图 2025-04-05 064430](https://github.com/user-attachments/assets/908d1e7f-dfed-42ec-b9da-3795bab92ea2)

### 2.启动IIS功能

打开电脑的控制面板中的“程序”-“启动或关闭Windows功能”，将图片里的所有功能都打勾。
![屏幕截图 2025-04-05 065026](https://github.com/user-attachments/assets/6dd92c3e-072b-4443-9269-6fb8c463d4ee)
![屏幕截图 2025-04-05 065035](https://github.com/user-attachments/assets/137176d0-0fc2-4bb5-88c6-baf85ec723d6)

### 3.搭建服务器

回到Windows的开始，搜索IIS，点进去后先点左上角的名称，再点击网站。
![屏幕截图 2025-04-05 065313](https://github.com/user-attachments/assets/0cc5ce80-51e4-442a-90a9-03a75e8180b1)
网站名称可以自取，要上传的网站在哪里，就把文件夹路径设置成那个。
![屏幕截图 2025-04-05 065455](https://github.com/user-attachments/assets/cfa6fa6e-d0be-44e0-adb8-08fb6c5e7bb4)
IP地址我填的是127.1.1.1，端口填80，类型为http。  
关闭上面的标签后，双击打开点击网站，双击选中test（设置的网站名），再点击右边菜单栏启动，再双击中间菜单栏的默认文档。
![屏幕截图 2025-04-05 085804](https://github.com/user-attachments/assets/11d98838-2653-4dfe-bb78-c18de1cd7eee)
首先点击右上方的添加，名称需要填要打开的网站的名称，记得要填上后缀“.html”，然后确定。
![屏幕截图 2025-04-05 101238](https://github.com/user-attachments/assets/89b5a860-51c0-45fc-8ad4-415195c42776)
接下来，点击右边菜单栏中的“浏览 127.1.1.1：80（http）”。
![屏幕截图 2025-04-05 101405](https://github.com/user-attachments/assets/9a68ad70-26bd-4e41-8ba2-51a2acb25570)
这是浏览器会打开你写的网页，并且地址栏显示的因该是127.1.1.1（如果你的IP填的是这个的话）。
![屏幕截图 2025-04-05 101539](https://github.com/user-attachments/assets/c804c6fe-f495-4f06-a342-a499fbffa50c)

### 4.内网穿透



### 5.注意事项
