# 网络工程师笔记（eNSP）

基于 **华为 eNSP** 的网络工程师学习笔记。内容整理自 Notion，导出为**自包含 HTML**，用浏览器直接打开即可阅读，无需联网或额外软件。

> 建议从入口页 [`网工基础与实验 .html`](%E7%BD%91%E5%B7%A5%E5%9F%BA%E7%A1%80%E4%B8%8E%E5%AE%9E%E9%AA%8C%20.html) 开始浏览。

## 内容大纲

| 页面 | 说明 |
| --- | --- |
| [网工基础与实验](%E7%BD%91%E5%B7%A5%E5%9F%BA%E7%A1%80%E4%B8%8E%E5%AE%9E%E9%AA%8C%20.html) | 一级索引页，汇总全部笔记入口 |
| [网络架构一](%E7%BD%91%E5%B7%A5%E5%9F%BA%E7%A1%80%E4%B8%8E%E5%AE%9E%E9%AA%8C/%E7%BD%91%E7%BB%9C%E6%9E%B6%E6%9E%84%E4%B8%80%2022bc41a40511806ba69ec7267d316065.html) | 网络架构基础 |
| [链路聚合](%E7%BD%91%E5%B7%A5%E5%9F%BA%E7%A1%80%E4%B8%8E%E5%AE%9E%E9%AA%8C/%E9%93%BE%E8%B7%AF%E8%81%9A%E5%90%88%203a5c41a4051180a19a17eaaca184ba10.html) | 链路聚合（Link Aggregation） |
| [OSPF V2](%E7%BD%91%E5%B7%A5%E5%9F%BA%E7%A1%80%E4%B8%8E%E5%AE%9E%E9%AA%8C/OSPF%20V2%203a5c41a40511800a82c4dd9d8b1bb500.html) | OSPF 原理、LSA、邻居与实验 |
| [OSPF V3](%E7%BD%91%E5%B7%A5%E5%9F%BA%E7%A1%80%E4%B8%8E%E5%AE%9E%E9%AA%8C/OSPF%20V3%203b7c41a40511807ca2a6f3430d40ba6b.html) | OSPF IPv6 版本 |
| [IPV6与双栈技术](%E7%BD%91%E5%B7%A5%E5%9F%BA%E7%A1%80%E4%B8%8E%E5%AE%9E%E9%AA%8C/IPV6%E4%B8%8E%E5%8F%8C%E6%A0%88%E6%8A%80%E6%9C%AF%203b7c41a40511805aa6a4e61bea4c4b54.html) | IPv6 与双栈技术 |
| [vlan隔离技术](%E7%BD%91%E5%B7%A5%E5%9F%BA%E7%A1%80%E4%B8%8E%E5%AE%9E%E9%AA%8C/vlan%E9%9A%94%E7%A6%BB%E6%8A%80%E6%9C%AF%203bec41a4051180f3a517d129b7a5531d.html) | VLAN 划分与隔离 |
| [WLAN无线局域网](%E7%BD%91%E5%B7%A5%E5%9F%BA%E7%A1%80%E4%B8%8E%E5%AE%9E%E9%AA%8C/WLAN%E6%97%A0%E7%BA%BF%E5%B1%80%E5%9F%9F%E7%BD%91%203bac41a405118002b5f3e851cc660b79.html) | 无线局域网 |
| [中型网络构建](%E7%BD%91%E5%B7%A5%E5%9F%BA%E7%A1%80%E4%B8%8E%E5%AE%9E%E9%AA%8C/%E4%B8%AD%E5%9E%8B%E7%BD%91%E7%BB%9C%E6%9E%84%E5%BB%BA%203b2c41a405118064923bc580af16afc3.html) | 中型网络综合构建 |
| [实验报告](%E7%BD%91%E5%B7%A5%E5%9F%BA%E7%A1%80%E4%B8%8E%E5%AE%9E%E9%AA%8C/%E5%AE%9E%E9%AA%8C%E6%8A%A5%E5%91%8A%203a8c41a40511800e8e2bc5c80412329a.html) | 实验报告汇总 |
| [项目实战](%E7%BD%91%E5%B7%A5%E5%9F%BA%E7%A1%80%E4%B8%8E%E5%AE%9E%E9%AA%8C/OSPF%20V2/%E9%A1%B9%E7%9B%AE%E5%AE%9E%E6%88%98%203b5c41a40511801e8953caf000ea1e1c.html) | OSPF V2 项目实战 |

## 页面使用说明

每张 HTML 页面都内置了两个便捷功能（纯前端实现，正文未改动）：

- **右下角「≡ 目录」按钮**：打开本页章节目录，点击条目可平滑跳转到对应小节，随滚动高亮当前所在章节。
- **左上角返回按钮**（除一级索引页外）：点击可跳回一级页面「网工基础与实验」。

## 目录结构

```
网络工程师笔记/
├─ README.md
├─ 网工基础与实验 .html            ← 一级索引入口
└─ 网工基础与实验/
   ├─ 网络架构一 ….html
   ├─ 链路聚合 ….html
   ├─ OSPF V2 ….html
   ├─ OSPF V3 ….html
   ├─ IPV6与双栈技术 ….html
   ├─ vlan隔离技术 ….html
   ├─ WLAN无线局域网 ….html
   ├─ 中型网络构建 ….html
   ├─ 实验报告 ….html
   └─ OSPF V2/                     ← 含图片资源与「项目实战」页
```

## 说明

- 笔记包含较多截图，各页面与 `OSPF V2` 等同名子目录中的图片是配套资源，**请保持整体目录结构不变**，否则页面内图片与页面间跳转可能失效。
- 仓库仅用于个人学习记录与分享。
