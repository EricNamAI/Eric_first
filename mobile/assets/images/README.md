# 蓝书应用图片资源

此目录包含应用所需的图片资源。你需要在此目录下添加以下图片：

1. `default-avatar.png` - 默认用户头像
2. `logo.png` - 应用LOGO
3. `default-travel.jpg` - 默认游记封面图

## 快速测试方法

在没有实际图片的情况下，你可以：

1. 打开 `generate_images.html` 文件（在浏览器中）
2. 生成并下载所需图片
3. 将下载的图片放置在此目录下

## 更新API配置

如果你想使用实际API而不是模拟数据，请编辑 `mobile/api/config.js` 文件：

```javascript
// 设置为false使用实际API
export const USE_MOCK = false;

// 配置正确的API地址
export const API_URL = 'http://your-api-server.com/api';
```

## 图片基本要求

- 所有图片需要遵循版权要求，推荐使用免费的图片资源
- 图片大小应适中，以便应用包体积不会过大
- PNG图片应使用透明背景，以便适应不同的背景色
