

# downloader_lite2.py
## 精简版多线程下载

推荐使用这个下载脚本，速度快，能批量下载

## 使用方法
    

在代码中录入m3u8的url、下载文件保存的地址、保存的文件名
- urllist：m3u8的url地址列表
- dirlist：下载视频的目录地址列表，可以把每个url下载到对应的目录里面去
- videoNameList：每个视频的名称列表，可以给每个视频取相应的名称

线程数大小更改

threadListSize = 5

#队列大小更改，队列大小应大于线程数的大小

queueSize = 10



# UI.py
## 桌面客户端

## 使用方法
使用命令启动客户端界面，需要安装python环境和相关依赖
python UI.py

在输入框中录入m3u8的url（多个使用分号分割开）、下载文件保存的地址、保存的文件名
点击启动按钮即可开始下载。
