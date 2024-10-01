# GitHub 镜像加速节点测试工具

这是一个简单而有效的工具，用于测试和比较不同 GitHub 镜像加速节点的性能。

## 功能特点

- 测试多个 GitHub 镜像的响应速度
- 支持一键测试所有镜像或查找最快的镜像
- 结果自动排序

## 使用方法

1. 打开 `index.html` 文件在浏览器中运行
2. 在文本框中输入要测试的镜像地址，每行一个
3. 点击"测试全部"按钮测试所有镜像，或点击"获取最快"查找最快的镜像
4. 查看结果，可以通过点击"复制"按钮复制所需的镜像地址

## 预览

```
GitHub 镜像加速节点测试

[文本框包含多个镜像地址]

[测试全部] [获取最快] [停止]

✅ 成功 https://example-mirror1.com 200ms [复制]
✅ 成功 https://example-mirror2.com 350ms [复制]
❌ 失败 https://example-mirror3.com 1500ms [复制]
...
```

## 技术实现

- 纯 HTML、CSS 和 JavaScript 实现
- 使用 Image 对象测试镜像响应时间
- 采用 Promise 进行异步处理
- 动态更新 UI 提供实时反馈

## 贡献

欢迎提交 Issues 或 Pull Requests 来帮助改进这个工具。

## 许可

MIT License
