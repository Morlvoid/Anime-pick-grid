# 你好请吃我的番剧安利-番剧收集器-Anime-pick-grid
[![在线演示](https://img.shields.io/badge/在线演示-点击体验-blue)](http://acg-anime.morlvoid.pro)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML](https://img.shields.io/badge/语言-HTML/CSS/JS-orange)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 项目简介

你好请吃我的番剧安利-番剧收集器（Anime-pick-grid）是一个基于网页的番剧推荐表生成工具，用户可以通过搜索和选择番剧，创建自己的番剧推荐九宫格或更多格子的推荐表。

<img width="800" height="600" alt="番剧安利" src="https://github.com/user-attachments/assets/f57ac085-c890-4c36-b5a3-43f7ff356ccf" />


## 项目功能

1. **番剧搜索**：集成了AniList和Bangumi两个API，支持模糊搜索番剧，搜索结果数量默认20个
2. **自定义布局**：支持多种布局方式，包括3x3、2x2、4x3、5x2布局，可根据需要选择
3. **新增番剧**：可以根据需要添加更多番剧卡片，不受限于初始的9个位置
4. **删除番剧**：可以删除不需要的番剧卡片，保持推荐表的整洁
5. **拖拽排序**：支持通过长按拖拽来调整番剧卡片的顺序
6. **自定义标题**：可以为番剧推荐表设置自定义标题，标题会显示在截图中
7. **截图保存**：使用html2canvas库实现截图功能，可将番剧推荐表保存为图片
8. **本地存储**：使用localStorage保存数据，刷新页面后数据不丢失
9. **响应式设计**：适配不同屏幕尺寸，在手机端也能良好显示

## 搜索数据源
目前集成了 AniList 和 Bangumi，如需添加其他源，可修改 performSearch 函数。

## 技术栈

- **前端框架**：纯HTML5 + CSS3 + JavaScript
- **数据存储**：localStorage
- **API集成**：
  - AniList GraphQL API
  - Bangumi REST API
- **截图功能**：html2canvas 1.4.1

## 如何使用

1. **设置标题**：在顶部输入框中设置推荐表标题，标题会显示在截图中
2. **添加番剧**：点击任意番剧卡片，在搜索框中输入番剧名称，从搜索结果中选择想要添加的番剧
3. **新增卡片**：点击"添加番剧"按钮可以添加更多番剧卡片，不受限于初始的9个位置
4. **删除番剧**：鼠标悬停在番剧卡片上，点击右上角的红色删除按钮可以删除卡片
5. **拖拽排序**：长按番剧卡片3秒启动拖拽，拖动到目标位置后松开鼠标，即可调整番剧顺序
6. **选择布局**：在"截图保存"按钮右侧的下拉菜单中选择想要的布局方式
7. **截图保存**：点击"截图保存"按钮，系统会自动将推荐表转换为图片并下载到本地
8. **数据持久化**：刷新页面后，所有数据会保持不变，因为数据存储在本地浏览器中

## 部署说明

### 本地部署

1. 克隆项目到本地
2. 直接打开`index.html`文件即可使用

## 版权信息

制作：Morlvoid / fulie <br>
本项目由 [Morlvoid](https://github.com/Morlvoid) 和 [fulie](https://github.com/bili-fule) 共同完成，纯本地工具，不收集任何用户信息，放心使用。如果你喜欢，欢迎 Star ⭐ 或转发给更多同好。

## 许可证
MIT License

## 贡献
欢迎提交 Issue 或 Pull Request。如果你想添加新功能或修复 bug，请先开 Issue 讨论。


