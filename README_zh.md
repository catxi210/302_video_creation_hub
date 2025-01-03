# <p align="center"> 🔍 AI 视频素材创意站 🚀✨</p>

<p align="center">AI视频素材创意站通过用户提供的主题信息，结合AI大语言模型生成高质量的文案和关键词，并根据这些信息将各种视频素材进行组合拼接，还可以附带字幕和背景音乐。</p>

<p align="center"><a href="https://302.ai/tools/video/" target="blank"><img src="https://file.302.ai/gpt/imgs/github/20250102/72a57c4263944b73bf521830878ae39a.png" /></a></p >

<p align="center"><a href="README_zh.md">中文</a> | <a href="README.md">English</a> | <a href="README_ja.md">日本語</a></p>

![](docs/302_Video_Creation_Hub_cn.png)

来自[302.AI](https://302.ai)的[AI视频素材创意站](https://302.ai/tools/video/)的开源版本。你可以直接登录302.AI，零代码零配置使用在线版本。或者对本项目根据自己的需求进行修改，传入302.AI的API KEY，自行部署。


## 界面预览
输入视频的主题，设置视频内容的语言，可选择自己输入编辑视频中的文案内容以及自行设置视频关键词，也可以选择AI根据主题自动生成文案和关键词。最后可以根据指定的主题、文案和关键词生成创意视频。
![](docs/302_AI_Video_Creation_Hub_screenshot_01.png)

可以在高级参数中针对视频生成再做一些设置，例如视频片段来源、比例、每个片段接入的最大时长。
![](docs/302_AI_Video_Creation_Hub_screenshot_02.png)     

可以设置字幕样式，例如大小、位置、描边粗细、字体和颜色等。
![](docs/302_AI_Video_Creation_Hub_screenshot_03.png)     

还可以设置视频中的配音设置，选择不同语音包并可以试听，还可以选择添加随机的背景音乐。
![](docs/302_AI_Video_Creation_Hub_screenshot_04.png)   


## 项目特性
### ✒️ AI一键生成视频文案和关键词
  设置视频主题和语言后即可一键生成，用户可以在此基础上修改。
### 🎧 自定义视频配音
  用户可选择不同语音模型为视频字幕配音，还可以随机生成背景音乐。
### 📹 自定义视频和字幕生成
  自主选择视频片段来源和长宽比例，还可以自定义字幕设置。
### 📎 视频下载
  可将生成的创意视频下载到本地。
### 🌓 暗色模式
  支持暗色模式，保护您的眼睛。
### 🌍 多语言支持
  - 中文界面
  - English Interface
  - 日本語インターフェース

## 🚩 未来更新计划
- [ ] 新增更多音色选择
- [ ] 背景音乐支持上传音频文件


## 🛠️ 技术栈

- **框架**: Next.js 14
- **语言**: TypeScript
- **样式**: TailwindCSS
- **UI组件**: Radix UI
- **状态管理**: Jotai
- **表单处理**: React Hook Form
- **HTTP客户端**: ky
- **国际化**: next-intl
- **主题**: next-themes
- **代码规范**: ESLint, Prettier
- **提交规范**: Husky, Commitlint


## 开发&部署
1. 克隆项目
```bash
git clone https://github.com/302ai/302_video_creation_hub
cd 302_video_creation_hub
```

2. 安装依赖
```bash
pnpm install
```

3. 环境配置
```bash
cp .env.example .env.local
```
根据需要修改 `.env.local` 中的环境变量。

4. 启动开发服务器
```bash
pnpm dev
```

5. 构建生产版本
```bash
pnpm build
pnpm start
```


## ✨ 302.AI介绍 ✨
[302.AI](https://302.ai)是一个面向企业的AI应用平台，按需付费，开箱即用，开源生态。✨
1. 🧠 集合了最新最全的AI能力和品牌，包括但不限于语言模型、图像模型、声音模型、视频模型。
2. 🚀 在基础模型上进行深度应用开发，我们开发真正的AI产品，而不是简单的对话机器人
3. 💰 零月费，所有功能按需付费，全面开放，做到真正的门槛低，上限高。
4. 🛠 功能强大的管理后台，面向团队和中小企业，一人管理，多人使用。
5. 🔗 所有AI能力均提供API接入，所有工具开源可自行定制（进行中）。
6. 💡 强大的开发团队，每周推出2-3个新应用，产品每日更新。有兴趣加入的开发者也欢迎联系我们
