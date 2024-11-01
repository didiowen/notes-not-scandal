---
title: 誰是戀愛腦！- 海鷗、凡尼亞舅舅
date:
  created: 2024-10-29T17:11:35
  updated: 2024-10-29T17:54:08
tags:
  - share
  - theatre
  - Chekhov
share: true
categories:
  - theatre
  - reading
aliases: Chekhov
---
# 誰是戀愛腦！- 海鷗、凡尼亞舅舅  
  
## 課前預習  
  
[1975電影版](https://www.youtube.com/watch?v=qiPfPzt8azc)  
[2018電影版](https://www.youtube.com/watch?v=ynGnOf0scl8)  
[national theater](https://www.youtube.com/watch?v=Z-Yn1ayTIJw)  
[zero point theater](https://www.youtube.com/watch?v=bWHnLuUivVQ)  
[臺南人](https://www.youtube.com/watch?v=fyWQknFB8nw&t=3078s)  
  
[《大學生》劇本](https://drive.google.com/file/d/1OLIHeVzjeWpmYRAjb-XlEkT1mLDZtzGC/view?usp=drive_link)  
[《海鷗》劇本](https://drive.google.com/file/d/11l49WC2P-mBmpJFceGyR-Wiu_P5zSlLz/view?usp=drive_link)  
  
<!-- more -->  
  
## 課後複習  
  
  
## Related  
  
- [x] Vanya  
- [ ] Vanya  
  
  
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