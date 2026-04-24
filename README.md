# 🃏 Tarot — 韦特塔罗在线占卜网页

> 挥手洗牌，握拳抽牌，用身体感受命运的指引

![Version](https://img.shields.io/badge/version-0.1.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![GitHub stars](https://img.shields.io/github/stars/yuxinLi2007/tarot)
![GitHub forks](https://img.shields.io/github/forks/yuxinLi2007/tarot)

## ✨ 创新点

| 创新方向 | 实现方式 |
|---------|---------|
| **体感交互抽牌** | 使用摄像头 + MediaPipe Hands 识别手势，挥手洗牌、握拳抽牌，无需触碰屏幕 |
| **密码学安全随机** | 使用 `crypto.getRandomValues()` CSPRNG，保证抽牌公正性，不可预测、不可重现 |
| **讲清楚牌面故事** | 每张牌配有详细的牌面故事描述，而非简单的关键词罗列，深度还原韦特牌面场景 |
| **LLM 智能解读** | 大语言模型根据问题语境生成个性化解读，结合牌阵位置语义 |
| **暗黑沉浸风格** | 深紫星空背景 + 金色光芒 + 星盘旋转，营造神秘仪式感 |

## 🎯 核心功能

- ✋ **体感手势抽牌** — 无需触碰屏幕，用手势完成整个占卜过程
- 🃏 **78 张完整塔罗牌** — 大阿卡纳 22 张 + 小阿卡纳 56 张
- 🔮 **多种牌阵选择** — 单牌阵、三牌阵（过去/现在/未来）、五牌阵
- 📖 **正逆位解读** — 每张牌的正位和逆位含义
- 🤖 **AI 个性化解读** — 结合问题语境生成专属解读

## 🛠️ 技术栈

| 层级 | 技术 |
|-----|------|
| 前端框架 | HTML5 + CSS3 + JavaScript (TypeScript) |
| 手势识别 | MediaPipe Hands |
| 随机数 | Web Crypto API (CSPRNG) |
| AI 解读 | OpenAI GPT / DeepSeek API |
| 部署 | 静态托管 |

## 🚀 快速开始

```bash
# 克隆仓库
git clone https://github.com/yuxinLi2007/tarot.git
cd tarot

# 直接打开（无需安装）
open src/index.html
```

## 📁 项目结构

```
tarot/
├── README.md              # 项目主页
├── LICENSE               # MIT 开源许可证
│
├── docs/                 # 项目文档
│   ├── 项目计划书.md      # 详细开发规划
│   └── 开发日志.md        # 开发进度记录
│
├── src/                  # 源代码
│   └── index.html        # 主页面
│
└── assets/               # 资源文件
    ├── images/           # 设计图、截图
    └── data/             # 卡牌数据
```

## 📅 开发进度

- [x] 项目规划与设计
- [x] 暗黑风格背景设计
- [x] 体感手势识别框架
- [x] 挥手洗牌功能
- [x] 抓取抽牌功能
- [ ] 78 张塔罗牌数据整理
- [ ] 多种牌阵系统
- [ ] 正逆位逻辑完善
- [ ] LLM 解读功能接入
- [ ] 移动端适配优化
- [ ] 部署上线

## 📸 效果预览

> 点击上方链接体验在线演示

### 背景效果
- 深邃紫黑星空背景
- 金色星盘三层旋转环
- 神秘符文装饰
- 紫色星云呼吸动画

### 手势交互
- 手部骨架实时可视化
- 挥手触发洗牌动画
- 握拳抽出命运之牌

## 🤝 参与贡献

欢迎提交 Issue 和 Pull Request！

## 📄 许可证

本项目采用 [MIT License](LICENSE)
