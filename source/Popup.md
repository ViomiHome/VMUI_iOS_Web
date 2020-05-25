---
title: Popup
date: 2019-11-25 17:12:28
tags:
---

#### 使用示例

```
    VMUIBasePopupViewConfig *config = [VMUIBasePopupViewConfig defaultConfig];
    config.fPopupViewHeight = 300;
    config.bShowCloseBtn = YES;
    VMUIPopupView *view_popup = [[VMUIPopupView alloc]initWithConfig:config];
    [view_popup show:nil];
```



####预览

![Popup](images/Popup.png)