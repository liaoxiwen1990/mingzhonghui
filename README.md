# English Tutor - 英语私教

一个基于 Claude API 的简单英语私教问答应用。

## 功能特点

- 中英文双语对话
- 语法问题解答
- 词汇解释
- 写作改进建议
- 口语练习
- 学习策略指导

## 安装步骤

1. 安装依赖:
```bash
pip install -r requirements.txt
```

2. 配置 API Key:
复制 `.env.example` 为 `.env`，然后填入你的 Anthropic API Key:
```bash
cp .env.example .env
```

编辑 `.env` 文件，填入你的 API Key:
```
ANTHROPIC_API_KEY=sk-ant-xxxxxxxxxxxxxx
```

3. 运行应用:
```bash
streamlit run app.py
```

4. 在浏览器中打开显示的地址 (通常是 `http://localhost:8501`)

## 使用说明

- 直接在输入框中输入你的问题（支持中文或英文）
- 使用侧边栏的快捷按钮快速开始对话
- 点击 "Clear Conversation" 清除聊天历史

## 系统要求

- Python 3.8+
- Anthropic API Key (从 https://console.anthropic.com 获取)
