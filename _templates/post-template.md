<%*
let inputTitle = await tp.system.prompt("제목 입력")
let date = tp.date.now("YYYY-MM-DD")
let datetime = tp.date.now("YYYY-MM-DD HH:mm:ss Z")

await tp.file.rename(`${date}-${inputTitle.replaceAll(" ", "-")}`)
-%>
---
title: "<% inputTitle %>"
date: <% datetime %>
categories: 없음
tags:
description:
comments: false
pin: false
---
# 대제목

## 소제목

내용 입력

## 📥 다운로드

<!-- [파일 다운로드](/assets/files/파일이름) -->