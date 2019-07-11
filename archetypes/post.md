---
title: {{ .Name | humanize }}
date: {{ .Date }}
publishdate: {{ .Date }}
description: "INSERT NICE DESCRIPTION"
draft: true
toc: false
author: 
categories:
 - ""
tags:
- ""
url: /{{ .Name | urlize }}/
resources:
- src: images/{{ .Name | urlize }}-header.png
  name: header
---

**Interest arousing introduction.**

<!--more-->
* This is a link: [Summary Split](https://gohugo.io/content-management/summaries/).
* this is a figure: {{< figure src="images/command_prompt-1.png" caption="Now what? I can't recall." >}}

> Blockquote

{{< highlight bash >}}
git config greenbase.provider travisci
{{</ highlight >}}

{{< youtube CODE >}}

{{< table-of-contents >}}

## Point I

### Subpoint ii

**Conclusion**
