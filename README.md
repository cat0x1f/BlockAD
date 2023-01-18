# 小火箭拦截广告

森月自用小火箭规则，来自互联网，侵删。

## 说明

这里的东西都应该不会更新，因为其他人维护的删库跑路的太多了。如果某条过期，那么森会在自己用的时候发现并且修改的。

根目录下的`conf`都应该要导入，然后模块里应该要导入`sgmodule`文件。

配置选择`森森配置*.conf`，安装 Https 证书，然后就应该能过滤广告了。

## 模块名

### ad-mitm

利用 mitm 重写来去广告。

```text
https://raw.githubusercontent.com/cat0x1f/BlockAD/main/script/ad-mitm/ad-mitm.sgmodule
```

### bilibili

去除 B 站广告。

```text
https://raw.githubusercontent.com/cat0x1f/BlockAD/main/script/bilibili/bilibili_plus.sgmodule
```

### famijia

米家自动签到。

```text
https://raw.githubusercontent.com/cat0x1f/BlockAD/main/script/famijia/famijia_checkin.sgmodule
```

### noad

广告屏蔽。

```text
https://raw.githubusercontent.com/cat0x1f/BlockAD/master/script/noad/noad.sgmodule
```

### startup

去除开屏广告。

```text
https://raw.githubusercontent.com/cat0x1f/BlockAD/master/script/startup/startup.sgmodule
```

### youtube-noad

去除 Youtube 广告。

```text
https://raw.githubusercontent.com/cat0x1f/BlockAD/master/script/youtube-noad/youtube-noad.sgmodule
```

### youtube-video-ad

去除 Youtube 视频广告

```text
https://raw.githubusercontent.com/cat0x1f/BlockAD/master/script/youtube-video-ad/youtube-video-ad.sgmodule
```

### zhihu

去除知乎广告。

```text
https://raw.githubusercontent.com/cat0x1f/BlockAD/master/script/zhihu/zhihu_plus.sgmodule
```

### startup2

去开屏广告。

```text
https://raw.githubusercontent.com/cat0x1f/BlockAD/master/script/startup2/startup2.sgmodule
```
