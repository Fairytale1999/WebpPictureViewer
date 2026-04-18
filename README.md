# WebpPictureViewer
安卓手机垂直浏览webp动图的脚本工具
***
### 我的项目结构
> Demo
>> webp
>>> img1.webp
>>> 
>>> img2.webp
>>> 
>> WebpPictureViewer.html
### 由于脚本语言限制无法主动获取或者扫描文件，故此使用前需要在WebpPictureViewer.html中配置相关文件夹信息
![](/img/demo3.jpg)

```javascript
// 文件夹名称 文件路径  图片数量  图片格式
var arry = [
{"name": "测试标题1", "path": "webp/", "fileSum": 21, "fileSuffix": ".webp"},
{"name": "测试标题2", "path": "webp/", "fileSum": 21, "fileSuffix": ".webp"},
{"name": "测试标题3", "path": "webp/", "fileSum": 21, "fileSuffix": ".webp"},
{"name": "测试标题4", "path": "webp/", "fileSum": 21, "fileSuffix": ".webp"},
];
```
### 然后你需要将文件夹内的图片按照顺序从1开始命名
    1.webp
    2.webp
    3.webp
    ...

### 最后配置完成后使用浏览器打开WebpPictureViewer.html文件即可
#### 滚动预览
![](/img/demo1.gif)
#### 侧边栏预览
![](/img/demo2.gif)
***
