# 易经算卦 - AI智能解卦应用

一个现代简约风格的HTML5易经算卦网页应用，集成了SiliconFlow AI大模型（Qwen/Qwen3-8B）进行智能解卦。

## ✨ 功能特性

### 🎯 核心功能
- **智能提问**：支持文字输入和语音输入
- **随机占卜**：基于易经64卦进行随机占卜
- **AI解卦**：使用Qwen3-8B大模型根据卦象和问题进行智能分析
- **动画效果**：卦象闪烁动画，营造神秘氛围

### 🎨 设计特色
- **现代简约**：干净的界面设计，毛玻璃效果
- **64卦背景**：卦象随机铺满背景，每次刷新都不同
- **响应式设计**：支持手机、平板、电脑等各种设备

### 🤖 AI功能
- 基于SiliconFlow API调用Qwen/Qwen3-8B模型
- 专业的易经解读和人生建议
- 温和、智慧的解答风格

## 🚀 使用方法

### 1. 配置API Key

首先需要获取SiliconFlow的API Key：

1. 访问 [SiliconFlow官网](https://cloud.siliconflow.cn/)
2. 注册并登录账号
3. 在控制台获取API Key
4. 点击页面右上角的⚙️图标
5. 输入API Key并保存

> 注：如果不配置API Key，应用仍可正常使用，但不会有AI解卦功能

### 2. 开始算卦

1. 在输入框中输入您的问题（或点击语音输入按钮）
2. 点击"开始算卦"按钮
3. 观看背景卦象闪烁5秒
4. 查看随机选中的卦象
5. 如果配置了API Key，会自动显示AI解卦结果

## 📖 技术说明

### 使用的技术
- **纯HTML5**：无需任何框架或构建工具
- **Web Speech API**：实现语音输入功能
- **SiliconFlow API**：AI大模型服务
- **LocalStorage**：本地保存API Key

### API调用详情
- **端点**：`https://api.siliconflow.cn/v1/chat/completions`
- **模型**：`Qwen/Qwen3-8B`
- **温度**：0.7
- **最大令牌数**：800

### 64卦数据
应用包含完整的易经64卦信息，严格按照[周易六十四卦列表](https://zh.wikipedia.org/wiki/%E5%91%A8%E6%98%93%E5%85%AD%E5%8D%81%E5%9B%9B%E5%8D%A6%E5%88%97%E8%A1%A8)整理：
- 卦名（简称）
- 完整卦名（如"乾为天"、"水雷屯"等）
- 六爻卦象符号（使用Unicode易经卦象字符 ䷀-䷿）
- 八卦符号组合（☰乾天、☷坤地、☵坎水、☲离火、☳震雷、☴巽风、☶艮山、☱兑泽）
- 卦辞（《周易》原文）

每个卦由上卦（外卦）和下卦（内卦）组成，共六爻。

## 🔒 隐私与安全

- API Key仅保存在浏览器本地存储（LocalStorage）
- 不会上传到任何服务器
- 所有数据均在客户端处理
- AI解卦通过HTTPS安全连接

## 📱 浏览器兼容性

- **推荐浏览器**：Chrome、Edge、Safari（最新版本）
- **语音输入**：需要浏览器支持Web Speech API
- **毛玻璃效果**：需要浏览器支持backdrop-filter

## 🎯 使用场景

- 日常决策参考
- 心理疏导和思考
- 传统文化学习
- 创意灵感获取

## 📝 注意事项

1. AI解卦仅供参考和娱乐，不应作为重大决策的唯一依据
2. 语音输入功能需要浏览器权限
3. API调用可能产生费用，请查看SiliconFlow的收费标准
4. 建议使用HTTPS访问以确保安全性

## 🔗 参考链接

- [SiliconFlow API文档](https://docs.siliconflow.cn/cn/api-reference/chat-completions/chat-completions)
- [周易六十四卦列表](https://zh.wikipedia.org/wiki/%E5%91%A8%E6%98%93%E5%85%AD%E5%8D%81%E5%9B%9B%E5%8D%A6%E5%88%97%E8%A1%A8)
- [Web Speech API](https://developer.mozilla.org/zh-CN/docs/Web/API/Web_Speech_API)

## 📄 许可证

MIT License

---

**愿易经的智慧为您指引方向！** 🔮

