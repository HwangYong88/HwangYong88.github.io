---
date: 2021-09-06 13:00:00
layout: post
title: economic Test
subtitle:
description:
category: economic
tags:
author:
paginate: true
---

.prettierrc설치법

1. 확장프로그램 다운로드
2. 프로젝트 내에 .prettierrc 파일 생성
3. 이하 붙여넣기
   {
   "singleQuote": true,
   "semi": true,
   "useTabs": false,
   "tabWidth": 2,
   "trailingComma": "all",
   "printWidth": 80
   }

4. 컨트롤 + , 로 설정으로이동
5. 우상단의 종이 접기 + 화살표 버튼을 클릭
6. 이하 붙여넣기
   {
   "terminal.explorerKind": "external",
   "terminal.external.windowsExec": "C:\\Program Files\\Git",
   "editor.formatOnSave": true,
   "explorer.confirmDelete": false,
   "prettier.javascriptEnable": ["javascript", "javascriptreact"],
   "emmet.includeLanguages": {
   "javascript": "javascriptreact"
   },
   "editor.defaultFormatter": "esbenp.prettier-vscode",
   "[javascript]": {
   "editor.defaultFormatter": "esbenp.prettier-vscode"
   },
   "prettier.endOfLine": "auto"
   }
