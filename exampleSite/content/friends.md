+++
title = "Friends"
description = "Friends"
date = "2023-10-14"
author = "Yorusaka Miyabi"
layout = "friends"

[menu.main]
weight = 10
params = { icon = "ph:planet-duotone" }
+++

Friends demo using shortcode:

**NOTE**: It's also possible to use YAML instead to write this shortcode.

## Fixed

This section will be fixed no matter what.

{{< links >}}
[
  {
    "title": "Yorusaka Miyabi",
    "link": "https://shadowrz.github.io/blog/",
    "img": "https://www.libravatar.org/avatar/c08fdd039b5c7a2da68b65c046356120d55f0704d876180e74bba90a54462ec3?s=400"
  },
  {
    "title": "Hugo",
    "link": "https://gohugo.io",
    "img": "https://gohugo.io/android-chrome-256x256.png",
    "des": "The world’s fastest framework for building websites."
  }
]
{{< /links >}}

### Shortcode

```
{{</* links */>}}
[
  {
    "title": "Yorusaka Miyabi",
    "link": "https://shadowrz.github.io/blog/",
    "img": "https://www.libravatar.org/avatar/c08fdd039b5c7a2da68b65c046356120d55f0704d876180e74bba90a54462ec3?s=400"
  },
  {
    "title": "Hugo",
    "link": "https://gohugo.io",
    "img": "https://gohugo.io/android-chrome-256x256.png",
    "des": "The world's fastest framework for building websites."
  }
]
{{</* /links */>}}
```

## Shuffled

This section will be shuffled randomly each time the site is successfully rebuilt.

<a href="https://github.com/ShadowRZ/hugo-theme-nexmoe/actions/workflows/github-pages.yml"><img style="border-radius: 0" src="https://img.shields.io/github/actions/workflow/status/ShadowRZ/hugo-theme-nexmoe/github-pages.yml" alt="Build status"></a>

{{< links shuffle >}}
[
  {
    "title": "喵's StackHarbor",
    "link": "https://sh.alynx.one",
    "img": "https://sh.alynx.one/images/Mikoto_Karon_White.webp"
  },
  {
    "title": "依云's Blog",
    "link": "https://blog.lilydjwg.me",
    "img": "https://blog.lilydjwg.me/user_files/lilydjwg/config/avatar.png"
  },
  {
    "title": "Vifly 的博客",
    "link": "https://viflythink.com",
    "img": "https://viflythink.com/img/avatar.png"
  },
  {
    "title": "Sukka's Blog",
    "link": "https://blog.skk.moe",
    "img": "https://cdn.jsdelivr.net/npm/skx@0.2.3/avatar/96x96.png"
  }
]
{{< /links >}}

### Shortcode

```
{{</* links shuffle */>}}
[
  {
    "title": "喵's StackHarbor",
    "link": "https://sh.alynx.one",
    "img": "https://sh.alynx.one/images/Mikoto_Karon_White.webp"
  },
  {
    "title": "依云's Blog",
    "link": "https://blog.lilydjwg.me",
    "img": "https://blog.lilydjwg.me/user_files/lilydjwg/config/avatar.png"
  },
  {
    "title": "Vifly 的博客",
    "link": "https://viflythink.com",
    "img": "https://viflythink.com/img/avatar.png"
  },
  {
    "title": "Sukka's Blog",
    "link": "https://blog.skk.moe",
    "img": "https://cdn.jsdelivr.net/npm/skx@0.2.3/avatar/96x96.png"
  }
]
{{</* /links */>}}
```