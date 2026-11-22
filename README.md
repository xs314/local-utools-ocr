# 本地 OCR for uTools

在 Windows 上离线识别截图和图片中的文字、表格与印刷公式。图片在本机处理，无需 API Key，没有每日识别次数限制。

- **文字**：识别中英文，结果可编辑、复制或导出为 TXT。
- **表格**：识别行列和合并单元格，支持复制到 Excel 或导出为 `.xlsx`。
- **公式**：识别为 LaTeX，可预览、编辑和复制。

## 下载与安装

支持 Windows x64。打开 [v1.1.2 下载页](https://github.com/xs314/local-utools-ocr/releases/tag/v1.1.2)，在 **Assets** 里选择对应版本：

| 版本 | 适合谁 | 1.1.2 下载大小 |
| --- | --- | ---: |
| CPU 通用版 | 普通 Windows x64 用户 | 约 280 MiB |
| Intel NPU 增强版 | 配有兼容 Intel AI Boost 和驱动的用户 | 约 333 MiB |

1. 下载 Assets 中带 `cpu` 或 `npu` 的 `.upxs` 安装包。
2. 选中文件并复制，呼出 uTools，粘贴后选择「安装插件应用」，再按提示确认。无需解压或安装开发者工具。[uTools 离线安装说明](https://www.u-tools.cn/plugins/topic/48/)
3. 呼出 uTools，搜索「本地OCR」。也可用「本地截图识别」「本地表格识别」或「本地公式识别」直接进入对应功能。

增强版默认使用 CPU。在识别界面右上角的性能设置中可切换到 Intel NPU，选择会自动保存。首次遇到新尺寸时需要准备 NPU 模型，表格结构和公式由 CPU 处理。

本仓库用于发布说明和预构建版本。第三方组件归属和许可证随发行文件提供。
