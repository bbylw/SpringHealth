# 🧧 春节健康指南 - 循证医学

> 基于WHO、AHA、ADA、ESC、NICE等国际权威机构循证医学证据编制

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Evidence-Based](https://img.shields.io/badge/evidence-A%2FB%20grade-brightgreen.svg)](https://www.who.int)
[![Chinese-New-Year](https://img.shields.io/badge/theme-春节-red.svg)](https://en.wikipedia.org/wiki/Chinese_New_Year)

## 📋 项目简介

本项目是一个基于循证医学的春节健康指南网页应用，旨在帮助用户在欢庆中国传统春节的同时，保持科学健康的生活方式。所有健康建议均来源于国际权威医学机构的最新指南和系统评价。

### ✨ 核心特色

- **🎋 传统与现代结合**：中国春节元素与现代医学专业感完美融合
- **📊 循证医学**：所有建议均标注证据等级（A/B级）和权威来源
- **🏥 国际指南**：引用WHO、AHA、ADA、ESC、NICE、FDA等权威指南
- **📱 响应式设计**：完美适配桌面端和移动端设备
- **🎨 视觉优化**：祥云动画、梅花装饰、中国结等传统元素

---

## 🎯 功能模块

### 1. 饮食调养 (饮食建议)
- **热量控制与份量管理**：餐盘法则、七分饱原则
- **地中海饮食与DASH饮食**：蔬果为本、全谷粗粮、优质油脂
- **减盐降压**：钠摄入限制、健康调味
- **饮酒与用餐时机**：餐间间隔、晚餐时间

**循证来源**：WHO膳食指南2023、AHA膳食指南2021、WHO钠摄入指南2022

### 2. 饮酒有度 (饮酒安全)
- **标准饮酒限量**：男女不同标准、各类酒换算
- **绝对禁酒人群**：孕妇、未成年人、肝病患者等
- **药物相互作用**：抗生素、镇静剂、止痛药等配伍禁忌
- **安全饮酒之道**：不空腹、缓节奏、水酒交替

**循证来源**：NIAAA饮酒指南2023、CDC饮酒指南、WHO酒精情况说明书2024

### 3. 用药安全
- **慢性病药物坚持**：降压药、降糖药、抗凝药等管理
- **食物与药物相互作用**：华法林、他汀类、ACE抑制剂等
- **出行用药准备**：备量、文证、保存、整理、时差调整
- **急救药物配备**：硝酸甘油、肾上腺素、急救吸入器等

**循证来源**：FDA药物指南、ISMP高警示药物清单、WHO旅行健康指南

### 4. 血压调控 (高血压管理)
- **居家血压监测**：频次、姿势、方法、目标值
- **DASH饮食实施**：蔬果、低脂乳品、全谷物、瘦肉蛋白
- **生活方式干预**：减重、运动、限盐、补钾、限酒、减压
- **春节特别注意事项**：高钠食物、酒精、睡眠、情绪、寒冷

**循证来源**：AHA家庭血压监测指南、NHLBI DASH饮食计划、ACC/AHA高血压指南

### 5. 血糖管理 (糖尿病管理)
- **血糖监测规范**：监测频率、目标范围、糖化血红蛋白
- **血糖指数与碳水计数**：低/中/高GI食物分类、餐盘法
- **胰岛素与药物调整**：基础胰岛素、餐前注射、生病日规则
- **低血糖预防与处理**：WHO分类、15-15法则、胰高血糖素

**循证来源**：ADA护理标准2026、EASD糖尿病与营养研究组、ADA低血糖指南

### 6. 急症识别
- **急性心肌梗死**：典型/非典型表现、立即行动、时间关键
- **卒中识别(FAST)**：面部、手臂、言语、时间
- **严重过敏反应**：呼吸、循环、皮肤、胃肠症状、肾上腺素使用
- **急性胰腺炎**：诱因、症状、处理、重症识别

**循证来源**：AHA/ACC胸痛指南2022、ESO指南2021、WAO过敏性休克指南

---

## 🛠️ 技术栈

### 前端技术
- **HTML5**：语义化标签、结构清晰
- **CSS3**：
  - CSS Variables（CSS变量）主题系统
  - Flexbox & Grid 布局
  - CSS Animations & Transitions
  - Gradient backgrounds
  - Backdrop-filter blur效果
- **JavaScript (ES6+)**：
  - Intersection Observer API（滚动动画）
  - DOM Manipulation
  - Event Handling

### 设计特点
- **字体**：
  - 标题：马善政楷体（Ma Shan Zheng）- 传统书法韵味
  - 正文：思源宋体（Noto Serif SC）- 优雅可读
  - 界面：思源黑体（Noto Sans SC）- 现代简洁
- **配色方案**：
  - 中国红（#C41E3A）- 主色调
  - 富贵金（#D4AF37）- 强调色
  - 健康绿（#1B4D3E）- 医学专业
  - 宣纸色（#FAF0E6）- 背景色

---

## 📦 项目结构

```
.
├── index.html          # 主页面文件（单页面应用）
├── README.md           # 项目说明文档
└── LICENSE             # 开源许可证
```

### 文件说明

**index.html**
- 包含完整的HTML结构、CSS样式和JavaScript逻辑
- 单文件架构，无需外部依赖（除Google Fonts CDN）
- 模块化CSS设计，易于维护和扩展

---

## 🚀 快速开始

### 本地运行

1. **克隆仓库**
```bash
git clone https://github.com/yourusername/spring-festival-health-guide.git
cd spring-festival-health-guide
```

2. **直接打开**
```bash
# 方式1：直接在浏览器中打开
open index.html

# 方式2：使用本地服务器（推荐）
# Python 3
python -m http.server 8000

# Node.js
npx serve

# PHP
php -S localhost:8000
```

3. **访问**
```
http://localhost:8000
```

### 部署到生产环境

#### GitHub Pages
1. Fork 本仓库
2. 进入 Settings > Pages
3. Source 选择 "Deploy from a branch"
4. Branch 选择 "main"，文件夹选择 "/ (root)"
5. 等待部署完成，访问 `https://yourusername.github.io/spring-festival-health-guide`

#### Netlify
1. 注册/登录 [Netlify](https://www.netlify.com/)
2. 点击 "Add new site" > "Deploy manually"
3. 拖拽项目文件夹上传
4. 自动获得 HTTPS 网址

#### Vercel
1. 注册/登录 [Vercel](https://vercel.com/)
2. 导入 GitHub 仓库
3. 框架预设选择 "Other"
4. 部署完成

---

## 🎨 自定义主题

### 修改配色
在 `index.html` 的 `<style>` 部分修改 CSS 变量：

```css
:root {
  --cny-red: #C41E3A;        /* 中国红 */
  --cny-red-dark: #8B0000;   /* 深红 */
  --cny-gold: #D4AF37;       /* 金色 */
  --cny-gold-light: #FFD700; /* 亮金 */
  --cny-green: #1B4D3E;      /* 健康绿 */
  --cny-cream: #FDF6E3;      /* 米黄 */
  --cny-paper: #FAF0E6;      /* 宣纸色 */
}
```

### 修改内容
每个功能模块包含在 `.section` 容器中：

```html
<div class="section">
  <div class="section-header" onclick="toggleSection(this)">
    <!-- 标题和图标 -->
  </div>
  <div class="section-content">
    <div class="section-inner">
      <div class="content-grid">
        <!-- 内容卡片 -->
      </div>
    </div>
  </div>
</div>
```

---

## 📚 循证医学来源

本指南引用的国际权威医学机构：

| 机构 | 全称 | 国家/地区 | 引用指南 |
|------|------|-----------|----------|
| **WHO** | 世界卫生组织 | 瑞士日内瓦 | 膳食指南、钠摄入指南 |
| **AHA** | 美国心脏协会 | 美国 | 膳食指南、胸痛指南、高血压指南 |
| **ACC** | 美国心脏病学会 | 美国 | 高血压指南、胸痛指南 |
| **ADA** | 美国糖尿病协会 | 美国 | 护理标准、低血糖指南 |
| **ESC** | 欧洲心脏病学会 | 欧洲 | 高血压指南 |
| **ESH** | 欧洲高血压学会 | 欧洲 | 高血压指南 |
| **EASD** | 欧洲糖尿病研究协会 | 欧洲 | 糖尿病与营养指南 |
| **NICE** | 英国国家健康与临床优化研究所 | 英国 | 临床指南 |
| **FDA** | 美国食品药品监督管理局 | 美国 | 药物安全通讯 |
| **NIAAA** | 美国国家酒精滥用与酒精中毒研究所 | 美国 | 饮酒指南 |
| **CDC** | 美国疾病控制与预防中心 | 美国 | 饮酒指南 |
| **ISMP** | 用药安全研究所 | 美国 | 高警示药物清单 |
| **NHLBI** | 美国国家心肺血液研究所 | 美国 | DASH饮食计划 |
| **WAO** | 世界过敏组织 | 国际 | 过敏性休克指南 |
| **ESO** | 欧洲卒中组织 | 欧洲 | 卒中指南 |
| **ACG** | 美国胃肠病学会 | 美国 | 胰腺炎指南 |
| **USPSTF** | 美国预防服务工作组 | 美国 | 预防医学建议 |
| **AAAAI** | 美国过敏、哮喘和免疫学会 | 美国 | 应急方案 |

---

## 🌏 浏览器兼容性

| 浏览器 | 版本 | 支持状态 |
|--------|------|----------|
| Chrome | 80+ | ✅ 完全支持 |
| Firefox | 75+ | ✅ 完全支持 |
| Safari | 13+ | ✅ 完全支持 |
| Edge | 80+ | ✅ 完全支持 |
| Opera | 67+ | ✅ 完全支持 |
| IE 11 | - | ❌ 不支持 |

---

## 📱 响应式断点

```css
/* 桌面端 */
@media (min-width: 1200px) { ... }

/* 平板端 */
@media (min-width: 768px) and (max-width: 1199px) { ... }

/* 移动端 */
@media (max-width: 767px) { ... }
```

---

## ⚠️ 免责声明

本指南仅供健康教育参考，**不能替代专业医疗建议**。所有健康信息均来源于国际权威医学机构的循证医学指南，但：

1. 个体差异存在，具体治疗方案请咨询执业医师
2. 急症情况请立即拨打急救电话（中国：120）
3. 用药调整必须在医生指导下进行
4. 本指南不对因使用信息而产生的后果承担责任

---

## 🤝 贡献指南

欢迎提交Issue和Pull Request！

### 贡献流程
1. Fork 本仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开 Pull Request

### 代码规范
- 使用语义化HTML标签
- CSS类名采用 kebab-case
- JavaScript使用ES6+语法
- 保持代码注释清晰

---

## 📄 许可证

本项目采用 [MIT 许可证](LICENSE) 开源。

```
MIT License

Copyright (c) 2026 Spring Festival Health Guide

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

## 🙏 致谢

- **Google Fonts** - 提供中文字体支持
- **各大医学机构** - 提供循证医学指南
- **开源社区** - 提供技术支持和灵感

---

## 📮 联系方式

如有问题或建议，欢迎通过以下方式联系：

- 📧 邮箱：your.email@example.com
- 🐙 GitHub Issues：[提交Issue](https://github.com/yourusername/spring-festival-health-guide/issues)
- 💬 讨论区：[GitHub Discussions](https://github.com/yourusername/spring-festival-health-guide/discussions)

---

<p align="center">
  <strong>祝您新春快乐，身体健康，阖家幸福！</strong><br>
  <em>🐎 2026 丙午马年 🐎</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/春节-安康-red?style=for-the-badge" alt="春节安康">
  <img src="https://img.shields.io/badge/龙马-精神-gold?style=for-the-badge" alt="龙马精神">
</p>
