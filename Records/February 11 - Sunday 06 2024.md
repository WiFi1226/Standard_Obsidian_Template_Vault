## TODO
- [ ] 搜索obsidian隐藏文件夹加上预览模式以固定
- [x] 绑定导入设置，zotero的 ✅ 2024-02-11
- [x] Longform的设置 ✅ 2024-02-12
- [x] zotilit的设置 ✅ 2024-02-11
- [ ] 两个推荐的Ob库以及一个照片的引入结合
- [ ] 右键功能以及控制台功能的设置
- [ ] 调整具体的 CSS 代码
- [ ] 继续完成语法页代码提示
- [ ] 开发页面功能 Mathpha
- [ ] Homepage 页面的设置
- [ ] 进度条插件联动 dataview
- [ ] 编写时预览 Callout 的功能
- [x] Tasks&Calendar 测试 2024-02-11 ✅ 2024-02-11


## Tracking
- 00:38 完成Memos的记录设置
- 00:48 对于两个推荐库以及图片，推荐库见B站收藏，图片为![列表框计数](https://raw.githubusercontent.com/mdelobelle/obsidian_supercharged_links/master/images/overview-screenshot.png) 与https://forum-zh.obsidian.md/t/topic/3059/11和https://forum.obsidian.md/t/progress-bar-for-notes-easy-and-powerful-with-dataview/33144
- 00:49 Canvas白板的学习网址(UI设置)https://zhuanlan.zhihu.com/p/597131166


## DraftList
<!--此处显示今日新增或修改的草稿或其它非文献笔记文件-->

```dataview
TABLE file.tags AS Tags, status AS Status, destination AS Destination
FROM ("02_记录/01_Assignment_Week")
WHERE date(file.mtime) >= date("2024-02-10") AND date(file.mtime) < date("2024-02-11") 
WHERE date(file.ctime) >= date("2024-02-10") AND date(file.ctime) < date("2024-02-11") 
SORT file.mtime desc
```