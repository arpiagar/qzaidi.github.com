---
layout: post
style: text
title: Emulating Javas PBEWithMD5AndDES encryption in node.js
---

Recently, we needed to do an interop between node.js and some legacy java code, and I was tasked with emulating Java's insecure PBEWithMD5AndDES encryption in node.js. Since I found quite a few questions on stackoverflow on the subject unanswered, I am posting the code here. It might someday save someone a little time.

{% gist 5401800 %}
