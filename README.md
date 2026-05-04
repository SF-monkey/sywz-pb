# 神印王座 · 随机旁白生成器 - AI配音版

> 🎭 输入你的名字，生成专属歌颂文案，支持 AI 配音朗读

## ✨ 功能特性

- 📝 **专属文案生成** - 输入名字，自动生成带有你名字的歌颂旁白
- 🎤 **AI 配音朗读** - 基于微软 Edge 神经网络语音，支持 6 种音色选择
- 📏 **文案长度可选** - 短句精简版(6句)、标准适中版(9句)、长篇史诗版(14句)
- 🎚️ **语速可调** - 从缓慢深情到铿锵有力，满足不同风格需求
- 📋 **一键复制** - 生成的文案可快速复制使用
- 🔀 **风格多样** - 120 句精选文案，涵盖悲壮深情、龙傲天等多种风格

## 🚀 使用方法

### 在线访问（推荐）

直接访问 GitHub Pages：
```
https://sf-monkey.github.io/sywz-pb/sywz-pb.html
```

### 本地使用

1. **下载文件**
   ```bash
   git clone https://github.com/SF-monkey/sywz-pb.git
   cd sywz-pb
   ```

2. **启动本地服务器**（解决跨域问题）

   **方法一：Python（推荐）**
   ```bash
   python -m http.server 8000
   # 然后访问 http://localhost:8000/sywz-pb.html
   ```

   **方法二：Node.js**
   ```bash
   npx serve .
   # 然后访问 http://localhost:3000/sywz-pb.html
   ```

   **方法三：VS Code**
   - 安装 "Live Server" 插件
   - 右键 `sywz-pb.html` → "Open with Live Server"

3. **使用步骤**
   - 打开页面后，输入你的名字
   - 选择文案长度（短句/标准/长篇）
   - 选择配音音色（男声/女声）
   - 选择朗读语速
   - 点击「随机生成文案」
   - 点击「一键AI配音朗读」播放
   - 或点击「复制文案」复制到剪贴板

## ⚠️ 常见问题

### AI 配音播放失败？

**原因**：浏览器跨域限制（CORS）

**解决方案**：
1. 使用本地服务器（见上方教程）
2. 或直接访问 GitHub Pages 在线版本

### 浏览器无法播放音频？

1. 检查浏览器是否允许自动播放音频
2. 点击页面任意位置后再点击播放按钮
3. 尝试刷新页面重新生成

## 📁 项目结构

```
sywz-pb/
├── sywz-pb.html      # 主页面（单文件，无需构建）
└── README.md         # 项目说明文档
```

## 🛠️ 技术栈

- **前端**: 纯 HTML + CSS + JavaScript（无框架依赖）
- **AI 配音**: 微软 Edge TTS (tts.wangwangit.com API)
- **降级方案**: 浏览器原生 SpeechSynthesis API

## 📜 License

MIT License - 欢迎自由使用、修改和分发

## 🙏 致谢

- 文案素材来源：动画《神印王座》
- AI 配音技术支持：微软 Azure Neural Voices
