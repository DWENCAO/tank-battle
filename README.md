# 坦克大战 🎮 Tank Battle

> 经典 **Battle City** 风格坦克对战游戏 — 纯 HTML5 Canvas 实现，无需任何依赖

[![GitHub stars](https://img.shields.io/badge/HTML5-Canvas-E34F26?logo=html5)](https://github.com/DWENCAO/tank-battle)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

---

## 📸 预览

| 游戏截图 | |
|:---:|:---:|
| 开局阵地 | ![](https://via.placeholder.com/200x200/1a1a2e/ffd700?text=🎯) |

> *截图占位 — 打开 `index.html` 即可体验！*

---

## 🎯 游戏介绍

你是战场上的指挥官。控制金色坦克，在 26×26 的网格战场上，摧毁所有红色敌军坦克，保卫己方基地（鹰旗）。

### 游戏目标

- **消灭全部敌人** — 每关 20+ 辆敌军坦克
- **保护基地** — 基地被毁则游戏结束
- **生存到底** — 你有 3 条命，用完即止

---

## 🎮 操作方式

| 按键 | 作用 |
|:---:|:---:|
| `↑` `↓` `←` `→` | 移动坦克 |
| `W` `A` `S` `D` | 移动坦克（备选）|
| `Space` | 射击 |

---

## 🗺️ 地图元素

| 元素 | 图标 | 说明 |
|:---:|:---:|:---:|
| 砖墙 | 🧱 | 可被子弹摧毁 |
| 钢墙 | ⬜ | 子弹无法穿透 |
| 水域 | 🌊 | 坦克不可通行，子弹可越过 |
| 森林 | 🌲 | 坦克可通行，提供视觉隐蔽 |
| 基地 | 🏠 | 你的老巢，必须守卫 |

---

## 🧠 技术特性

- **纯前端** — 单 HTML 文件，零依赖，浏览器打开即玩
- **Canvas 渲染** — 像素级绘制坦克、地图、特效
- **AI 敌人系统** — 敌人自主巡逻、随机转向、自动射击
- **碰撞检测** — 坦克之间、坦克与地图、子弹碰撞全方位检测
- **粒子特效** — 爆炸碎片效果增强打击感
- **关卡递增** — 通关后敌人数量随关卡增加
- **响应式 HUD** — 实时显示得分、剩余敌人、命数、关卡

---

## 🚀 快速开始

```bash
# 克隆仓库
git clone https://github.com/DWENCAO/tank-battle.git

# 打开游戏
cd tank-battle
start index.html          # Windows
open index.html           # macOS
xdg-open index.html       # Linux
```

或者直接拖拽 `index.html` 到浏览器中。

---

## 🏗️ 项目结构

```
tank-battle/
├── index.html       # 游戏主文件（HTML + CSS + JS）
└── README.md        # 项目说明
```

---

## 🧪 技术栈

| 技术 | 用途 |
|:---|:---:|
| HTML5 Canvas | 游戏画面渲染 |
| CSS3 | 界面样式与布局 |
| Vanilla JavaScript | 全部游戏逻辑 |
| 无第三方库 | 纯粹原生实现 |

---

## 🤝 贡献

欢迎提交 Issue 和 PR！可以改进的内容：

- 增加更多关卡地图
- 添加道具系统（加速、护盾、连发）
- 双人模式
- 音效系统
- 移动端触摸控制

---

## 📄 License

MIT License © 2026 [DWENCAO](https://github.com/DWENCAO)

---

<p align="center">
  <b>坦克大战</b> — 致敬经典，重温童年 🔥
  <br>
  <sub>用 HTML5 Canvas 重制的 Battle City 精神续作</sub>
</p>
