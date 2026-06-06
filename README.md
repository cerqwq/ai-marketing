# 📣 AI Marketing

AI营销工具，支持营销策略、内容营销、社交媒体。

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

## ✨ 特性

- 📋 营销策略生成
- 📅 内容日历生成
- 📢 广告文案生成
- 📊 活动效果分析
- 📧 邮件营销生成
- 📝 SEO内容生成

## 🚀 快速开始

```bash
pip install openai

python tools.py
```

## 📖 使用

```python
from ai_marketing import create_tools

tools = create_tools()

# 营销策略
strategy = tools.generate_marketing_strategy("AI助手", "开发者", 10000)

# 内容日历
calendar = tools.generate_content_calendar("MyBrand", ["微博", "抖音"], "1个月")

# 广告文案
ad = tools.generate_ad_copy("智能手表", "抖音", "年轻人")

# 效果分析
analysis = tools.analyze_campaign_performance(metrics)

# 邮件营销
email = tools.generate_email_campaign("新产品", "欢迎")

# SEO内容
seo = tools.generate_seo_content("Python教程", ["Python", "编程"])
```

## 📁 项目结构

```
ai-marketing/
├── tools.py       # 营销工具核心
└── README.md
```

## 📄 许可证

MIT License
