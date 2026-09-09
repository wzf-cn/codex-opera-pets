# Codex Opera Pets · 戏曲萌宠

黄梅戏主题的开源 Codex 动画宠物合集，持续收录经典剧目角色，以卡通动画呈现戏服、身段与角色个性。

目前收录 **1 只原创主题宠物**。长期目标是逐步覆盖黄梅戏剧目角色；尚未制作的角色不计入已收录目录。

## 角色目录

| 预览 | 角色 | 所属剧目 | 特色 | 下载 |
| --- | --- | --- | --- | --- |
| ![梅小水](pets/original/mei-xiao-shui/preview.gif) | [梅小水](pets/original/mei-xiao-shui/README.md) | 原创黄梅戏主题引导角色 | 淡黄与水绿戏服、凤冠、水袖、小锣 | [宠物 ZIP](downloads/mei-xiao-shui.zip) |

## 三种主要动作

| 工作：挥水袖 | 等待操作：敲小锣 | 完成：谢幕 |
| --- | --- | --- |
| ![挥水袖](pets/original/mei-xiao-shui/previews/running.gif) | ![敲锣](pets/original/mei-xiao-shui/previews/waiting.gif) | ![谢幕](pets/original/mei-xiao-shui/previews/jumping.gif) |

另含待机、左右移动、招手、出错、检查结果，以及 16 个视线方向。敲锣是视觉动画，不包含音频。

## 安装

下载上方 ZIP 并解压，将其中 `mei-xiao-shui` 文件夹放入 Codex 自定义宠物目录：

- Windows：`%USERPROFILE%\.codex\pets\`
- macOS / Linux：`~/.codex/pets/`
- 如果设置了 `CODEX_HOME`，使用该目录下的 `pets/`。

最终应存在 `pets/mei-xiao-shui/pet.json` 与 `pets/mei-xiao-shui/spritesheet.webp`。仓库的剧目分组不用复制到安装目录。然后在 Codex 的宠物设置中刷新并选择「梅小水」；必要时重新启动应用。

## 格式与验证

发布包采用 sprite v2：8×11 图集、1536×2288 像素、192×208 单格，含 9 种标准状态与 16 个视线姿态。

每个角色提供图集、动图预览、SHA-256 和脱敏验证摘要。梅小水已通过结构、透明边缘及方向盲测检查，逐帧视觉复核通过并保留轻微差异说明；尚未验证应用内实际播放。详见 [验证摘要](pets/original/mei-xiao-shui/qa/validation-summary.json)。

## 后续收录

目录采用 `pets/<剧目标识>/<角色标识>/`，原创角色使用 `pets/original/`。同名角色的不同剧目版本分别建档，安装 ID 保持全库唯一。每个角色记录剧目、行当、造型参考、动作设计及素材许可，未核实内容保留空值。

欢迎按 [贡献说明](CONTRIBUTING.md) 提交新角色。当前宠物由内置 imagegen 生成并经拆帧、对齐与检查，是戏曲主题卡通演绎，不作为历史戏服或特定演员表演的复原。

## 许可与署名

除单独标明的第三方内容外，本仓库发布的原创素材和文档采用 **[CC BY 4.0](LICENSE)**。推荐署名：

> 梅小水 / Codex Opera Pets，wzf-cn，CC BY 4.0。来源：https://github.com/wzf-cn/codex-opera-pets

使用或改编时请保留作者、来源和许可信息，并说明修改。项目为独立社区作品，与 OpenAI 无隶属或背书关系。
