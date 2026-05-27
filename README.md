# ⚽ 2026 FIFA 世界杯主题网站

一个功能丰富的世界杯主题 Web 项目，包含数据展示、互动游戏和模拟功能。

## 打开方式

直接在浏览器中打开 `index.html` 即可，无需服务器或安装任何依赖。

```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

## 功能列表

### 主页 (`index.html`)

- **倒计时** — 2026 世界杯开幕倒计时
- **小组赛** — 48 支球队分 A-H 组，含球队资料、FIFA 排名、核心球员
- **比赛模拟器** — 基于 ELO 评分的比赛模拟，支持任意两队对战
- **赛程生成器** — 自动生成小组赛赛程
- **淘汰赛对阵图** — 完整的淘汰赛 bracket
- **历史数据** — 22 届世界杯冠军、金靴、金球数据
- **球队对比** — 两支球队多维度对比
- **最佳阵容** — 4-3-3 阵型评选
- **比赛动画** — Canvas 2D 比赛实况动画
- **点球小游戏** — 互动点球体验
- **比赛解说** — Web Audio API 音效合成

### 小游戏

| 游戏 | 文件 | 说明 |
|------|------|------|
| Football Legends | `football-legends.html` | 大头卡通风格 2D 足球对战，支持 AI 对手 |
| 点球大战 | `penalty-shootout.html` | 点球决胜，16 支球队可选，3 档难度 |
| 足球知识问答 | `football-quiz.html` | 30+ 道题目，4 个分类，计时挑战 |
| 记忆翻牌 | `memory-game.html` | 国旗配对记忆游戏，4 种棋盘尺寸 |
| 世界杯预测器 | `predictor.html` | 预测 48 队小组赛和淘汰赛结果 |

## 技术栈

- 纯 HTML + CSS + JavaScript，零依赖
- HTML5 Canvas 2D 渲染
- Web Audio API 音效
- LocalStorage 数据持久化
- 响应式设计

## 项目结构

```
world-cup-2026/
├── index.html              # 主页（倒计时、小组赛、模拟器、历史等）
├── football-legends.html   # Football Legends 2D 对战游戏
├── penalty-shootout.html   # 点球大战
├── football-quiz.html      # 足球知识问答
├── memory-game.html        # 记忆翻牌游戏
├── predictor.html          # 世界杯预测器
└── README.md
```
# World Cup 2026
