# Delta Force Asala Card Tracker / 三角洲阿萨拉牌盒记牌器

**Version / 版本：v1.0.0**  
**Author / 作者：BertYin**

A local-first tracker for **Delta Force Asala card collection**.  
一个用于记录 **三角洲行动阿萨拉牌盒 / 阿萨拉扑克牌收集进度** 的本地网页工具。

---

## Keywords / 搜索关键词

Delta Force, Delta Force Asala Card Tracker, Asala Card Tracker, Asala Card Case, Delta Force card collection, card collection tracker, collection tracker, localStorage tracker, HTML tracker, JavaScript tracker.

三角洲行动、三角洲、阿萨拉牌盒、阿萨拉扑克牌、三角洲记牌器、三角洲牌盒收集、三角洲扑克牌收集、牌盒记牌器、扑克牌收集工具、缺卡清单、重复牌统计、本地网页工具。

---

## 中文说明

这是一个用于记录《三角洲行动》阿萨拉牌盒收集进度的本地网页工具。

它是一个纯前端单文件应用，不需要登录，不需要服务器，也不会上传任何数据。所有收集进度都会保存在当前浏览器的 `localStorage` 中。

### 功能

- 记录 55 个阿萨拉牌盒收集项
- 支持数量记录
- 自动统计重复牌
- 自动生成缺卡清单
- 支持搜索和筛选
- 支持中文 / English 界面切换
- 支持多种点数排序方式
- 支持 JSON 备份与导入
- 支持 CSV 导出，方便用 Excel 打开
- 响应式布局，适配不同浏览器宽度
- 可直接部署到 GitHub Pages

### 使用方法

直接用浏览器打开 `index.html` 即可使用。

如果部署到 GitHub Pages，访问 GitHub Pages 生成的网址即可。

### 数据保存说明

本工具的数据只保存在当前浏览器本地：

```text
localStorage
```

换浏览器、清理缓存、换设备后，原数据不会自动同步。建议定期使用 **导出 JSON** 功能备份进度。

---

## English

A local-first web tracker for Delta Force Asala card collection progress.

This is a fully client-side single-file web app. It does not require login, does not require a server, and does not upload any data. All progress is saved in the current browser's `localStorage`.

### Features

- Tracks all 55 Asala collection items
- Quantity-based progress tracking
- Automatic duplicate card detection
- Automatic missing card list
- Search and filters
- Chinese / English UI switch
- Multiple rank order modes
- JSON backup and import
- CSV export for Excel or spreadsheets
- Responsive layout
- GitHub Pages ready

### Usage

Open `index.html` directly in a browser.

If deployed to GitHub Pages, open the generated GitHub Pages URL.

### Data Storage

All data is saved locally in the current browser:

```text
localStorage
```

Progress will not automatically sync across browsers, devices, or after browser cache cleanup. Use **Export JSON** regularly to back up your progress.

---

## Project Files / 项目文件

```text
index.html   Main tracker app / 主程序
README.md    Project documentation / 项目说明
.gitignore   Ignore rules / 忽略规则
```

---

## Disclaimer / 免责声明

This is a fan-made utility for personal collection tracking. It does not use official game APIs and does not include copyrighted game images.

本项目是个人自用/玩家向收集记录工具，不使用官方游戏 API，也不包含游戏版权图片素材。
