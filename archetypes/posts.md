---
title: "{{ replace .Name "-" " " | title }}"
description: "{{ replace .Name "-" " " | title }}"  # 留空则自动提取首段文字作为摘要
date: {{ .Date }}
lastmod: {{ .Date }}
categories: ["分类"]
collections: ["合集"]
draft: true   # 发布前需改为false
---

<!--more-->  # 此符号前的内容将作为摘要显示