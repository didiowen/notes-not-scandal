---
title: Lung ultrasound
date:
  created: 2025-03-06T14:10:46
  updated: 2025-03-06T14:12:38
tags:
  - share
  - medicine
share: true
categories:
  - medicine
alias: lung
status: finished
---
# Lung ultrasound  
  
| **LUS Finding**   | **Description** | **Clinical Significance** |  
|-------------------|---------------|--------------------------|  
| **A-lines** | Horizontal, repetitive lines | Normal lung aeration or pneumothorax |  
| **B-lines** | Vertical, hyperechoic laser-like artifacts | Pulmonary edema, pneumonia, ILD, ARDS |  
| **Consolidation** | Tissue-like hypoechoic region | Pneumonia, atelectasis, infarction |  
| **Pleural Effusion** | Anechoic or echogenic fluid collection | Heart failure, infection, malignancy |  
| **Lung Sliding** | Pleural shimmering movement | Absent in pneumothorax or adhesions |  
| **Shred Sign** | Irregular lung border | Pneumonia-related consolidation |  
| **Lung Point** | Transition between sliding and no sliding | Pneumothorax |  
  
```meta-bind-button  
label: "Share"  
style: default  
id: "share"  
actions:  
  - type: updateMetadata  
    bindTarget: share  
    evaluate: false  
    value: true  
  - type: replaceSelf  
    replacement: "<!-- more -->"  
```  
  
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