# 百度地图切图工具 - 支持IE与Chromium内核

**[最新更新于2022-08-20]**

本项目提供了一款强大的百度地图切图工具，针对先前版本中可能遇到的兼容性问题进行了重大升级。原先依赖于WinForm的WebBrowser控件已被先进的WebView2所取代，确保了在不同浏览器内核下均能稳定显示地图，从而解决了地图无法正常加载的问题。

### 主要特性

1. **适配广泛**：同时兼容旧版IE内核及现代Chromium内核，增强系统兼容性。
2. **自定义AK配置**：使用前需替换`html\在线地图.html`中的第7行AK值为您自己的百度地图API密钥（请注意，需申请浏览器端API密钥）。
3. **项目管理**：支持创建多个项目，便于分门别类管理您的切图需求。
4. **智能选取与下载**：允许用户在地图上多选区域，程序自动下载并合并成单张图片，详细记录缩放级别与中心坐标。
5. **精细图片处理**：基于程序自动处理的基础，进一步优化个人图片处理流程。
6. **瓦片图层生成**：实现高精度瓦片切割至百度地图最大支持的缩放级别20级，并提供DEMO展示效果。

### 使用说明

- 下载“百度地图切图工具ie内核、chromium内核.zip”文件。
- 解压缩后，根据说明文档，前往`html`目录下的`在线地图.html`。
- 替换示例代码中的AK值，确保您已拥有有效的百度地图API密钥。
- 运行程序，享受高效便捷的地图切图体验。

**注意事项**：由于百度地图API政策变化，确保所用AK适用于浏览器端应用，以免影响功能使用。

---

本工具旨在简化地图数据处理流程，提升工作效率，无论是地理信息系统开发还是个性化地图设计，都是不可多得的辅助工具。欢迎开发者和地图爱好者下载使用，并反馈任何改进建议。

## 下载链接
[百度地图切图工具-支持IE与Chromium内核](https://pan.quark.cn/s/214f87f7d85b) 

(备用: [备用下载](https://pan.baidu.com/s/18T2wnAr3uHEG4v6I3kwUtg?pwd=1234))

## 说明

该仓库仅用于学习交流，请勿用于商业用途。
