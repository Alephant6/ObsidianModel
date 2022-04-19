# Introduction

## 描述
Obsidian自用仓库的几个模板

## 目的
1. 根据现有模版快速建立新仓库
2. 避免icloud错乱导致原有仓库崩坏

## 原则
1. 混乱与秩序同在
2. **效率为王**，效率大于一切，拒绝all in one
3. 开源，加强交流

## Tips

1. 不建议在windows下使用icloud同步——太卡了

## 未来开发计划

### 学术仓库模版

后面[^后面]再做一个全英学术的仓库，
目前我能想到的：

1. 把zotero，excalidraw等联动做进去；
2. 全英文[^全英文]，方便pandoc直接导出成LaTex的pdf——更官方专业些（中文会乱码）;
3. LaTex的插件，Quick Latex for Obsidian
4. 图片保存为**相对位置**，且保存在当地文件夹**figure**[^figure]文件夹下

[^后面]: 当需要的时候，不要创造需求

[^全英文]: 不必如此，只要在开头加一行`\usepackage[UTF8]{ctex}` 即可

[^figure]: **Figure** is to solve a mathematical problem while **image** is to represent symbolically and **picture** is to represent in or with a picture.




## 模版介绍
### AlephantNote
- 创建时间最早
- 用来承接OneNote
- icloud同步
- 内部结构，图片混乱
- 日记板块

### YaSi 
- readme文档比较详细
- 雅思学习
- 目前最全面方便的模板

### NewChannel
- 从YaSi割离出来的一个简化版
- 适应icloud
- 去掉核心组件”快照“功能
- 全文档配合使用PicBed图床

### Note
- NewChannel同模
- 旨在脱离icloud，利用git做的一个全新文字仓库
- 处理探索计划、出境学习
