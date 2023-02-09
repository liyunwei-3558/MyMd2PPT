# 使用Marp将md笔记一键转为组会模板ppt
b站：视频链接[https://www.bilibili.com/video/BV1we4y1K7PZ/?vd_source=0a4ec734b1e35319996bdf4563e55339#reply142830901520]

## Update
### 2023-02-10 解决Zotero Better Notes以\<span>标签实现块编辑，而marp无法识别的问题
使用正则表达式替换：
```
<span[\s\S]*?>
<a[\s\S]*?>
</[\s\S]*?>
```