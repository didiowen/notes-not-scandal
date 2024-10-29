---
title: 戲劇發生的場所 - 玩偶之家
date:
  created: 2024-10-29T17:04:01
  updated: 2024-10-29T17:58:17
tags:
  - theatre
  - Ibsen
  - Nordic
  - share
status: in progress
share: true
categories:
  - theatre
  - reading
aliases: doll
---
# 戲劇發生的場所 - 玩偶之家  
  
[中文劇本](https://drive.google.com/file/d/1ipUnuNF70G7YxiUlDkjbvPxImaWLOwMF/view?usp=drive_link)  
  
<!-- more -->  
  
## 補充影音資料  
  
不用從頭到尾看完，可以抓一些片段看看感覺，  
也可以觀察不同版本的演出選擇，  
請特別注意開頭、中間、結尾。  
  
[版本一](https://www.youtube.com/watch?v=sr3nw7CZvO8&t=872s)    
[版本二](https://www.youtube.com/watch?v=ZJDnHQT2BDk)    
[版本三](https://www.youtube.com/watch?v=9jxemLaLyHo)  
  
另外對於《玩偶之家》的延伸觀影，可以看Kramer vs. Kramer。  
  
```meta-bind-button  
label: "In Progress"  
style: default  
id: "progress"  
hidden: true  
actions:  
  - type: updateMetadata  
    bindTarget: status  
    evaluate: false  
    value: "in progress"  
  - type: updateMetadata  
    bindTarget: date.updated  
    evaluate: true  
    value: moment().format("YYYY-MM-DDTHH:mm:ss")  
```  
```meta-bind-button  
label: "Finished"  
style: default  
id: "finished"  
hidden: true  
actions:  
  - type: updateMetadata  
    bindTarget: status  
    evaluate: false  
    value: "finished"  
  - type: updateMetadata  
    bindTarget: date.finished  
    evaluate: true  
    value: moment().format("YYYY-MM-DDTHH:mm:ss")  
```  
`BUTTON[progress, finished]`  
```meta-bind-button  
label: "Upload"  
style: default  
id: "upload"  
actions:  
  - type: updateMetadata  
    bindTarget: date.updated  
    evaluate: true  
    value: moment().format("YYYY-MM-DDTHH:mm:ss")  
  - type: command  
    command: obsidian-mkdocs-publisher:share-one  
```  
