---
layout: post
title:  "Atom에서 emmet 패키지 설치 후 마크다운 프리뷰 단축키 동작 안할때"
date:   2016-11-21 23:44:49 +0900
categories: jekyll update
---
# Atom에서 emmet 설치 후 마크다운 프리뷰 단축키 동작 안할때
간단요약: emmet.cson 파일에서 ctrl-shift-m 키바인딩 제거.

Preference - Open config folder - package - emmet - keymaps - emmet.cson

'ctrl-shift-m': 'emmet:merge-lines'
항목을 제거/주석처리 한다.
