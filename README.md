# 一百万针的等待

一个关于 1954 年索尔克脊髓灰质炎疫苗现场试验的中文互动叙事网页。

玩家会依次检查候选疫苗、两套对照设计、随机试验的真实病例数据，以及 1955 年发生在疫苗获批后的 Cutter 制造事故。作品的重点不是记住结论，而是练习区分随机误差、选择偏差、有效性证据和批次安全证据。

## 在线体验

https://lovles0.github.io/salk-polio-story/

## 特点

- 32 幅分镜、4 个证据判断点
- 使用 1954 年现场试验的真实人数和病例数
- 自动保存阅读进度、答题记录和结案成绩
- 桌面端与移动端响应式布局
- 单文件实现，无构建步骤

## 本地运行

直接打开 `index.html` 即可。为了得到与线上环境一致的资源加载行为，也可以在仓库目录启动任意静态文件服务器。

## 主要史料

- [University of Michigan：1955 Polio Vaccine Trial Announcement](https://sph.umich.edu/polio/)
- [“A calculated risk”: the Salk polio vaccine field trials of 1954](https://pmc.ncbi.nlm.nih.gov/articles/PMC1114166/)
- [CDC：Historical Vaccine Concerns — Cutter Incident](https://www.cdc.gov/vaccine-safety/historical-concerns/index.html)
- [1956 年 Cutter 事故流行病学报告](https://stacks.cdc.gov/view/cdc/43902/cdc_43902_DS1.pdf)

页面中的历史照片来自 Wikimedia Commons 公开档案，署名显示在相应图片右上角。部分照片为同年代示意图，并非所述事件的现场照片。

## 部署

站点由 GitHub Pages 从 `main` 分支发布。推送 `index.html` 后，线上页面通常会在几分钟内更新。
