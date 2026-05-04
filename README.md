# 复印王座旁白生成器 - AI配音版

>他踏着命运的剧本走来，  
每一道光都是编剧亲手镀的，  
世界为他低头，魔族为他谢幕，  
龙浩晨打个哈欠，  
世界就自动下跪。  
他一剑劈开黑夜，  
天地便集体高潮，  
旁白颤抖着高呼——  
“啊，这圣洁的光啊，这无敌的少年啊！”


这尴尬到脚趾抠地的叠buff旁白，要是送给所有人，是不是很大胆 :sweat_smile:  


## 🚀 使用方法
🎭 输入一个名字，随机生成龙浩晨同款歌颂旁白，支持 AI 配音朗读  

### 在线访问（推荐）

直接访问 GitHub Pages：
```
https://sf-monkey.github.io/sywz-pb/
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
   # 然后访问 http://localhost:8000/
   ```

   **方法二：Node.js**
   ```bash
   npx serve .
   # 然后访问 http://localhost:3000/
   ```

   **方法三：VS Code**
   - 安装 "Live Server" 插件
   - 右键 `index.html` → "Open with Live Server"

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
├── index.html       # 主页面（单文件，无需构建）
├── README.md        # 项目说明文档
└── LICENSE          # MIT 许可证
```

## 🛠️ 技术栈

- **100% Vibe Coding**
- **前端**: 纯 HTML + CSS + JavaScript（无框架依赖）
- **AI 配音**: 微软 Edge TTS (tts.wangwangit.com API)
- **降级方案**: 浏览器原生 SpeechSynthesis API

## 📜 License

MIT License - 欢迎自由使用、修改和分发

## 🙏 致谢

- AI 配音技术支持：微软 Azure Neural Voices
