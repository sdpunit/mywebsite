+++
date = '{{ .Date }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
+++

<!-- --- hugo theme archetype:
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
author:
tags:
image:
description:
toc:
--- -->