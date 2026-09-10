# GitHub 上传清单

## 一、放入仓库首页的文件

将下列内容提交到仓库默认分支：

- `README.md`
- `docs/images/interface-overview.png`
- `docs/images/layouts-comparison.png`
- `docs/images/appearance-settings.png`
- `docs/demos/jiefa-ds-blind-test.html`

Demo 是独立的静态 HTML 展示文件，不包含应用源码、模型文件或 API Key。不要上传应用源码、开发文档、词库原始文件、模型源文件或本机配置。

## 二、创建 Release

- Tag：`v4.3.1`
- Release 标题：`NAI 中文作者助手 v4.3.1`
- Release 正文：复制 `GITHUB_PROJECT_INFO.md` 中“推荐 Release 简介”的内容。

## 三、上传到 Release 附件区

必传：

- `NAI-Author-Assistant-4.3.1-mac-arm64.dmg`
- `NAI-Author-Assistant-4.3.1-mac-x64.dmg`
- `NAI-Author-Assistant-4.3.1-win-x64-setup.exe`
- `SHA256SUMS.txt`
- `发布说明-4.3.1.md`

建议同时上传：

- `测试报告-4.3.1.md`

通常无需手动下载时上传：

- `*.blockmap`：仅在以后接入兼容的自动增量更新机制时需要；当前手动安装发布可不上传。

## 四、发布前最后检查

- 确认三个安装包文件名和版本均为 4.3.1。
- 确认 ARM64 文件名包含 `mac-arm64`，Intel 文件名包含 `mac-x64`。
- 确认 `SHA256SUMS.txt` 与最终上传的三个安装包一致。
- 确认 Release 中注明未签名、未公证和实机测试边界。
- 确认仓库内没有 API Key、个人路径、用户资料或私人提示词。
