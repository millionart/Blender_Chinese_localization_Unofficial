# 根据你的能力参与翻译

首先你需要[注册](https://github.com/join?source=header-home)或[登录](https://github.com/login) GitHub 帐号，然后根据你的实际情况选择以下：

## 情况1 我发现一两条翻译需要修改

1. 进入 [Issues](https://github.com/millionart/Blender_Chinese_localization_Unofficial/issues) 页面
2. 点击 [New issus](https://github.com/millionart/Blender_Chinese_localization_Unofficial/issues/new) 按钮
3. 写清你遇到的翻译错误
4. 写清你建议的翻译或给出参考资料
5. Ctrl + V 粘贴相关图片（建议）
6. 提交等待讨论

## 情况2 我发现大量翻译可以添加 / 修改

### 步骤1 翻译

* 使用 [poedit](https://poedit.net/) 修改 zh_CN.po
* 有大量的词条被标记为黄色，代表由 Google 翻译，这些内容不会生效，请将确认无误的翻译取消 需要处理 开关
* 修改你认为错误的词条，注意保持占位符格式（比如 {} %s 这种类似乱码的内容）
* 为确保界面词汇一致性，请参考[词汇对照表](./dict.md)

### 步骤2 提交

* 如果你熟悉 GitHub，可以直接发起 pull request
* 如果你不熟悉 GitHub，可以将修改过的 zh_CN.**po** （注意不是 mo）压缩成 zip 文件粘贴到 [New issus](https://github.com/millionart/Blender_Chinese_localization_Unofficial/issues/new) 里