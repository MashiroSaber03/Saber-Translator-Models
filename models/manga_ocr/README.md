# MangaOCR

日文漫画 OCR 模型

- 模型包：[`manga_ocr.zip`](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/download/model-files-v2/manga_ocr.zip)
- 解压到应用的 `models/` 目录，保留包内 `manga_ocr/` 路径；也可在应用“设置 → 模型管理”中自动安装。
- ZIP 大小：444238473 字节
- ZIP SHA-256：`b768f0475e084ef4a203a4905f4d7479d98518524c5679badcd8820b5d616ece`

## 包内文件

- `manga_ocr/config.json`
- `manga_ocr/preprocessor_config.json`
- `manga_ocr/pytorch_model.bin`
- `manga_ocr/tokenizer_config.json`
- `manga_ocr/vocab.txt`

运行所需 Python 库由主程序环境提供，模型包只包含该模型的权重、词典和配置。第三方权重沿用各自上游许可，参见仓库 [LICENSE](../../LICENSE)。
