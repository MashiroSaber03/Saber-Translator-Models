# Saber-Translator model files

此仓库托管 [Saber-Translator](https://github.com/MashiroSaber03/Saber-Translator) 使用的模型文件，与主程序独立发布。

用户请启动应用，进入 **设置 → 模型管理**，按需下载或一键安装全部。源码版和打包版使用相同入口；已有模型可继续复用。

## model-files-v1

11 组模型、29 个文件，总计 4,083,355,990 字节（约 3.80 GiB）。文件名以 SHA-256 开头；应用下载后会校验文件大小及哈希。完整路径及校验值见 model_manifest.json。模型权重位于 Releases 附件中，不存入 Git 历史。

| 模型 | 文件数 | 体积 |
| --- | ---: | ---: |
| Default 文本检测 | 1 | 294.1 MiB |
| CTD 文本检测 | 2 | 166.5 MiB |
| YSGYolo 文本检测 | 1 | 15.8 MiB |
| SaberYOLO 文本检测 | 1 | 53.8 MiB |
| MangaOCR | 5 | 423.7 MiB |
| PP-OCRv6 Medium | 3 | 132.2 MiB |
| 48px OCR | 2 | 195.0 MiB |
| PaddleOCR-VL-1.6 | 11 | 1840.9 MiB |
| LaMA MPE | 1 | 103.6 MiB |
| LiteLaMA | 1 | 473.8 MiB |
| LaMA Manga | 1 | 194.9 MiB |

## 使用与许可

这是项目当前模型文件的分发镜像，并非新的统一模型。各模型权重沿用各自上游的许可和使用条件；此仓库不对第三方权重重新授权。Saber-Translator 应用自身的许可证与各模型权重许可证分别适用。