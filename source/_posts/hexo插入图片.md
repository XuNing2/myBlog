---
title: hexo插入图片
date: 2022-04-05 15:56:50
tags: hexo
description: 在hexo 中插入图片的尝试
---

安装

```bash
npm install hexo-asset-image-for-hexo5 --save
```

然后在 _config.yml 中设置 post_asset_folder为true
这样的后果是 _posts 文件夹下面乱糟糟的

![image-20220405160330232](hexo插入图片/image-20220405160330232.png)

要怎么将全部图片都放在同一个文件夹 images 下呢？

如果图片文件夹的名字有空格的话，就不能正常显示

![image-20220720210629683](word 狗都不用/image-20220720210629683.png)

需要进行缩放，自动生成这种形式才可以

![image-20220720210938125](hexo插入图片/image-20220720210938125.png)
