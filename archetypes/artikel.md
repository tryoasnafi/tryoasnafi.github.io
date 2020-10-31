---
title: "{{ replace .Name "-" " " | title }}"
slug: {{ .BaseFileName }}
publishdate: {{ now.Format "2006-01-02" }}
lastmod: {{ now.Format "2006-01-02" }}
draft: true

type: post

tags:
    - tag

image: ""
description: ""
---