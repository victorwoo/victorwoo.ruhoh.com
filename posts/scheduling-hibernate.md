---
title:定时休眠的命令
date: '2013-08-16'
description:
tags: [hack]
---
例如2个小时以后休眠：

    timeout /t 7200 /nobreak & shutdown /h
注意 `shutdown /h /t xxx` 这样的组合是没用的。