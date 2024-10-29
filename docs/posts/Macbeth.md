---
title: 因果關係與業力引爆 - 馬克白
date:
  created: 2024-10-29T17:06:46
  updated: 2024-10-29T17:58:25
tags:
  - share
  - theatre
  - Shakespear
share: true
categories:
  - theatre
  - reading
aliases: Macbeth
---
# 因果關係與業力引爆 - 馬克白  
  
## 課前預習  
  
[中文劇本](https://www.haodoo.net/?M=u&P=H1534:0&L=book&F=-1)  
  
<!-- more -->  
  
完整影片：  
[影片一](https://www.youtube.com/watch?v=ms5wRzOmqG8)  
[影片二](https://www.youtube.com/watch?v=1OU0cuGuPSk)  
[影片三](https://www.youtube.com/watch?v=IgEshHhnLqU)  
  
## 課後複習  
  
延伸影片：  
[The Sandman summon the Fates Scene](https://www.youtube.com/watch?v=BmA4fkUrgVA)  
[The Morality of Murder | Barry 1x05](https://www.youtube.com/watch?v=o8RBXQJ2czA)  
[My Lord, the Queen is Dead | Barry 1x07](https://www.youtube.com/watch?v=PSWcEn89qOY)  
  
## Thoughts  
  
  
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
