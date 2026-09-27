# 更新日志 / Changelog

## 1.0.6 — 2026-09-27

### 中文

- 创造物品分类栏支持循环翻页，并新增分类选择弹窗：每行四个分类，左键切换，右键置顶/取消置顶；置顶顺序会影响分类显示顺序。
- 新增页码显示开关，以及配方多候选物品目录功能开关。
- 修复分类弹窗被底层物品贴图、高亮轮廓和 tooltip 遮挡的问题；弹窗打开时阻止选择底层物品。
- 打开容器中的物品现在会参与配方树库存计算，并按配方树需求高亮。
- 缓存配方快照和配方状态，减少多候选配方页面渲染时的重复扫描。
- Forge 1.20.1 与 NeoForge 1.21.1 版本号均更新至 1.0.6。

### English

- Creative item tabs now wrap when paging and include a category picker with four entries per row. Left-click selects a category; right-click pins or unpins it, and pin order determines display order.
- Added separate toggles for the page indicator and the multi-candidate recipe ingredient directory.
- Fixed the category picker being obscured by underlying item sprites, highlight outlines, and tooltips. Underlying items can no longer be selected while the picker is open.
- Items in an open container now count toward recipe-tree inventory and are highlighted according to recipe-tree requirements.
- Cached recipe snapshots and recipe status to reduce repeated scans while rendering recipe pages with many candidates.
- Updated both Forge 1.20.1 and NeoForge 1.21.1 builds to version 1.0.6.
