---
layout: page
title: title: 'Dream of AI\'s Dream'
description:
category:
related_publications:
redirect:
---

TO BE UPDATED

1. **修复 Lexer 警告**：
   - 检查所有配置文件和代码，尤其是 YAML、Markdown 等文本文件，确保所有标点符号使用的是英文格式，而不是中文格式。特别注意日志中提到的第 72 行附近。

2. **修复 Uglifier 错误**：
   - 修改 `title: 'Dream of AI's Dream'` 中的引号问题。可以使用双引号来包含字符串，避免冲突：
     ```yaml
     title: "Dream of AI's Dream"
     ```
   - 或者将内部的单引号改为转义字符（使用 `\'`）：
     ```yaml
     title: 'Dream of AI\'s Dream'
     ```