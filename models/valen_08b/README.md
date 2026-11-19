# Valen-0.8B

Saber-Translator 字体匹配使用的 Valen 旧版。包内保留 `Valen-0.8B/`、原版权重、推理代码、配置、分词器和上游许可证。 [固定上游版本](https://huggingface.co/Valen-Team/Valen-0.8B/tree/c2c481fcb319bd9ae834abc7c6373271710cf24e)

完整 ZIP 为 `valen_08b.zip`，3,437,344,256 字节。

SHA-256

`9167f6b93d41db28234369e0a70be038d95625028c33e8fea343d755f8ee0b64`

## GitHub 分卷

下载全部分卷到同一目录，按编号拼接，然后核对完整 ZIP 的 SHA-256。

- [valen_08b.zip.001](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/download/model-files-v2/valen_08b.zip.001) · 1,992,294,400 字节
- [valen_08b.zip.002](https://github.com/MashiroSaber03/Saber-Translator-Models/releases/download/model-files-v2/valen_08b.zip.002) · 1,445,049,856 字节

Windows PowerShell

```powershell
cmd /c copy /b valen_08b.zip.001+valen_08b.zip.002 valen_08b.zip
Get-FileHash -Algorithm SHA256 valen_08b.zip
```

macOS 或 Linux

```sh
cat valen_08b.zip.001 valen_08b.zip.002 > valen_08b.zip
```

## 离线安装

将包内 `Valen-0.8B/` 解压到 Saber 的模型下载目录。首次使用时在 **设置 → 更多 → 模型管理** 准备 Valen 独立环境，再在 **设置 → 字体匹配** 选择。原上游许可随包提供。 [Apache 2.0 许可证](https://huggingface.co/Valen-Team/Valen-0.8B/blob/c2c481fcb319bd9ae834abc7c6373271710cf24e/LICENSE)
