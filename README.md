# AgriSky 农业气象监测平台

## 📊 在线面板
**GitHub Pages**: https://lonionlee.github.io/agrisky/

## 📋 专题简报
| 简报 | 链接 | 日期 |
|------|------|------|
| 2026超强厄尔尼诺专题简报 | [查看](https://lonionlee.github.io/agrisky/briefings/2026-el-nino-briefing.html) | 2026-07-14 |

## 📁 仓库结构
```
├── index.html                    ← 面板（GitHub Pages入口）
├── AgriSky_蓝白面板_v9.html      ← 面板源文件
├── briefings/                    ← 专题简报目录
│   └── 2026-el-nino-briefing.html
└── images/                       ← 面板图片资源
```

## 🤝 协作说明
- **面板修改**：编辑 `AgriSky_蓝白面板_v9.html`，同步更新 `index.html`
- **新增简报**：放入 `briefings/` 目录，更新本文件中的简报索引表
- **自动化脚本**：由 Coze Agent 维护，通过 CodeAct 定时执行

## 🔧 自动化能力
- 驾驶舱数据周更（期货/气候指数/台风）
- 天气展望板块更新（CPC/NMC/WorldAgWeather）
- 农业气象板块更新（QWeather + Open-Meteo）
- 气候数据周更（IMD季风/USDM干旱/ENSO诊断）
- 知识科普板块周更
- GitHub Pages 自动部署
