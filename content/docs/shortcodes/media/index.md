+++
title = "Media Shortcodes"
date = "2020-10-22"
description = "A detailed description of media shortcodes"
featured = false
categories = [
  "Shortcode"
]
tags = [
  "Bilibili",
  "Tencent",
  "Youku",
  "iQiyi",
  "Netease Music",
  "asciinema",
]
series = [
  "Docs"
]
images = [
]
aliases = [
  "/en/posts/shortcodes/media"
]
authors = ["syncriix"]
+++

A detailed description of media shortcodes, such as Bilibili, Tencent, Youku, iQiyi and Netease Music.
<!--more-->

## Bilibili

```toml
{{</* bilibili "video id" */>}}
```

{{< bilibili "BV11s411c7ZU" >}}

## Tencent

```markdown
{{</* tencentvideo "vid" */>}}
```

{{< tencentvideo "p0015bl11hy" >}}

## Youku

```markdown
{{</* youku "XNTQwMTgxMTE2" */>}}
```

{{< youku "XNTQwMTgxMTE2" >}}

## iQiyi

```markdown
{{</* iqiyi "vid" "tvid" */>}}
```

{{< iqiyi "e2ad67ca24d1e205fb0b87eb243f467d" "567349400" >}}

## Netease Music

```markdown
{{</* neteasemusic "id" [auto [type]] */>}}
```

| Parameter | Description |
|---|---|
| `auto` | The `auto` controls whether to autoplay. Boolean and optional, default to `false`.
| `type` | The `type` parameter is optional. Default to `2`.

{{< neteasemusic "24953439" false >}}

## asciinema

```markdown
{{</* asciinema id */>}}
```

{{< asciinema 514468 >}}
