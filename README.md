# Saber-Translator 模型包

此仓库托管 [Saber-Translator](https://github.com/MashiroSaber03/Saber-Translator) 使用的模型，与主程序独立发布。源码版和打包版均可在 **设置 → 模型管理** 中按需下载或一键安装全部，已有完整模型可继续使用。

## model-files-v2

每个模型独立一个文件夹、一个 ZIP。包内保留原模型目录及其权重、词典和配置，共 11 个模型包、29 个运行文件，合计 4,083,360,200 字节（约 3.80 GiB）。

GitHub 的模型目录提供说明及对应 ZIP 的下载链接，二进制 ZIP 位于 [模型包 Release](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/tag/model-files-v2)。[魔搭镜像](https://modelscope.cn/models/MashiroSaber/Saber-Translator-Models/files) 正在同步此目录结构。完整安装路径、ZIP 和包内各文件的校验值见 [model_manifest.json](model_manifest.json)。

| 模型目录 | ZIP 下载 | 包内文件数 | 下载大小 |
| --- | --- | ---: | ---: |
| [Default 文本检测](models/detector_default/) | [detector_default.zip](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/download/model-files-v2/detector_default.zip) | 1 | 294.1 MiB |
| [CTD 文本检测](models/detector_ctd/) | [detector_ctd.zip](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/download/model-files-v2/detector_ctd.zip) | 2 | 166.5 MiB |
| [YSGYolo 文本检测](models/detector_yolo/) | [detector_yolo.zip](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/download/model-files-v2/detector_yolo.zip) | 1 | 15.8 MiB |
| [SaberYOLO 文本检测](models/saber_yolo/) | [saber_yolo.zip](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/download/model-files-v2/saber_yolo.zip) | 1 | 53.8 MiB |
| [MangaOCR](models/manga_ocr/) | [manga_ocr.zip](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/download/model-files-v2/manga_ocr.zip) | 5 | 423.7 MiB |
| [PP-OCRv6 Medium](models/paddle_ocr/) | [paddle_ocr.zip](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/download/model-files-v2/paddle_ocr.zip) | 3 | 132.2 MiB |
| [48px OCR](models/ocr_48px/) | [ocr_48px.zip](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/download/model-files-v2/ocr_48px.zip) | 2 | 195.0 MiB |
| [PaddleOCR-VL-1.6](models/paddleocr_vl/) | [paddleocr_vl.zip](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/download/model-files-v2/paddleocr_vl.zip) | 11 | 1840.9 MiB |
| [LaMA MPE](models/lama_mpe/) | [lama_mpe.zip](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/download/model-files-v2/lama_mpe.zip) | 1 | 103.6 MiB |
| [LiteLaMA](models/litelama/) | [litelama.zip](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/download/model-files-v2/litelama.zip) | 1 | 473.8 MiB |
| [LaMA Manga](models/lama_manga/) | [lama_manga.zip](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/download/model-files-v2/lama_manga.zip) | 1 | 194.9 MiB |

## 安装方式

应用内下载会自动续传、校验并解压安装。离线安装时，将 ZIP 内的模型目录解压到应用的 `models/`；例如 `manga_ocr/config.json` 应位于 `models/manga_ocr/config.json`。LaMA MPE 与 LiteLaMA 各有一个 ZIP，解压后共享 `models/lama/`，使用不同的权重文件。

模型包包含各模型独立运行所需的权重、词典及配置。Python、PyTorch、Transformers、ONNX Runtime 等环境由主程序和其依赖提供。程序安装成功后即可加载模型，无需再为每个 ZIP 安装独立环境。

旧版 [model-files-v1](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/tag/model-files-v1) 保留供旧客户端使用，已安装模型无需迁移。

## 使用与许可

这是项目当前模型的分发镜像。各模型权重沿用各自上游的许可和使用条件，此仓库不对第三方权重重新授权，详见 [LICENSE](LICENSE)。应用自身的许可证与各模型权重许可证分别适用。
