## 界面操作演示

<p align="center">
  <a href="assets/demo/startup.mp4"><img src="assets/demo/startup.gif" width="960" alt="Human Writing 启动与操作演示"></a>
</p>

[观看 / 下载完整视频](assets/demo/startup.mp4) · [演示说明](assets/demo/startup.json)

执行 check_prose.py 的初检与复检，将真实 stdout 重排为终端动画；中间改稿为人工示例，检查器不会自动改文。 画面按操作顺序录制，输入与阅读停留经过剪辑，不代表实际模型耗时。

# 活人感写作（human-writing）

用于创作和修改中文现实文章、故事、评论、公众号文章及其他作品。按任务读取 `SKILL.md` 与 `references/` 中对应规则。`scripts/check_prose.py` 可用于检查散文稿中的格式与禁用表达。

## 安装

将本仓库克隆或下载到：

```text
~/.codex/skills/human-writing
```

本仓库保留技能规则、检查脚本和经整理的写作偏好，不包含旧文章与对话归档。
