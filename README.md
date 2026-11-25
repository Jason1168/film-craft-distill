# film-craft-distill

Cursor 技能：每天收集高质量公开影片和视频制作开源项目，并按参考片的节奏做一条原创成片。完成线是 95 分。

用 Cursor 打开这个仓库，技能在 `.cursor/skills/film-craft-distill/`。新开一个 Agent 对话即可试。

## 试这三句

1. `跑今天的蒸馏`
2. `用 film-craft-distill 复刻这个参考片：/你的路径/参考.mp4。素材在 /你的路径/素材/`
3. 只有打分脚本退出码是 0，才算 95 分。

本机需要 `ffmpeg`。参考片只用来测量，成片使用你自己的素材。

冒烟检查：

```bash
python3 .cursor/skills/film-craft-distill/scripts/score_replica.py --self-test
python3 .cursor/skills/film-craft-distill/scripts/check_plan.py --self-test
```
