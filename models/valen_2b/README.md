# Valen-2B

Saber-Translator 字体匹配使用的 Valen 旧版。包内保留 `Valen-2B/`、原版权重、推理代码、配置、分词器和上游许可证。 [固定上游版本](https://huggingface.co/Valen-Team/Valen-2B/tree/fb9205c2541abc97ce276670e66f79b78d9068fc)

完整 ZIP 为 `valen_2b.zip`，8,879,500,614 字节。

SHA-256

`928852449fe9e317de6bd15d5e3a96eaf699dc45e3e08c4dbc6f4ac4873f9be9`

## GitHub 分卷

下载全部分卷到同一目录，按编号拼接，然后核对完整 ZIP 的 SHA-256。

- [valen_2b.zip.001](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/download/model-files-v2/valen_2b.zip.001) · 1,992,294,400 字节
- [valen_2b.zip.002](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/download/model-files-v2/valen_2b.zip.002) · 1,992,294,400 字节
- [valen_2b.zip.003](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/download/model-files-v2/valen_2b.zip.003) · 1,992,294,400 字节
- [valen_2b.zip.004](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/download/model-files-v2/valen_2b.zip.004) · 1,992,294,400 字节
- [valen_2b.zip.005](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/download/model-files-v2/valen_2b.zip.005) · 910,323,014 字节

Windows PowerShell

```powershell
cmd /c copy /b valen_2b.zip.001+valen_2b.zip.002+valen_2b.zip.003+valen_2b.zip.004+valen_2b.zip.005 valen_2b.zip
Get-FileHash -Algorithm SHA256 valen_2b.zip
```

macOS 或 Linux

```sh
cat valen_2b.zip.001 valen_2b.zip.002 valen_2b.zip.003 valen_2b.zip.004 valen_2b.zip.005 > valen_2b.zip
```

## 离线安装

将包内 `Valen-2B/` 解压到 Saber 的模型下载目录。首次使用时在 **设置 → 更多 → 模型管理** 准备 Valen 独立环境，再在 **设置 → 字体匹配** 选择。原上游许可随包提供。 [Apache 2.0 许可证](https://huggingface.co/Valen-Team/Valen-2B/blob/fb9205c2541abc97ce276670e66f79b78d9068fc/LICENSE)
