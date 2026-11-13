# 3D 网页三步工作流

视频教程配套资料，包含 `web3d-model-workflow` 建模 Skill、六屏网页设计提示词，以及读取已有模型制作 3D 视差滚动网站的提示词。

[下载完整资料包](https://github.com/CCCIRCCCLE715/web3d-model-workflow/releases/download/v1.0.0/web3d-model-workflow-v1.0.0.zip) · [查看完整教程](https://hcnbsg6ttb3t.feishu.cn/docx/RaGpdBFpTo5jtUxr6SAc1cPEnlr)

仓库和资料包公开，无需登录即可下载。

## 包内文件

- `web3d-model-workflow/`：按部件选择 Blender 或 Aholo Lux3D，完成组装、GLB 导出和资产记录。
- `Image2_六屏网页设计通用提示词.txt`：生成同一网站的六屏设计稿。
- `3D网页_自动识别模型与视差滚动提示词.txt`：读取设计稿、模型和资产清单，制作滚动网站。

## 安装 Skill

下载并解压资料包，把 `web3d-model-workflow` 文件夹放入 Codex 项目目录，然后向 Codex 发送：

```text
把这个 skill 安装到我的技能目录，检查 Blender 与 Aholo Lux3D 是否可用，按缺项引导配置。
```

如果需要在多个项目中使用，安装到 `~/.codex/skills/web3d-model-workflow`。安装后，已有对话可能需要重新打开才能发现技能。

## 使用

在项目中准备主体参考图、已确认的设计稿和现有工程，发送：

```text
使用 $web3d-model-workflow，读取当前项目的设计图和参考，选择合适的建模方式，制作可拆分模型并记录网页可自动读取的资产清单。
```

制作网站时，将包内的 `3D网页_自动识别模型与视差滚动提示词.txt` 完整发送到同一个项目。

Skill 提供工具选择和配置指引；Blender、MCP 服务及 Aholo Lux3D 插件需按环境配置。资料包不包含软件安装包、账号密钥或云端生成额度，生成费用以服务实际报价为准。

## 版本

本次发布保留教程原始附件中的 5 个文件，未改写 Skill 和提示词。Release ZIP 与原始附件内容及字节一致，SHA-256 见 `source.json`。
