---
title: "Quick Notepad++ Setup for Python"
seoTitle: "Quick Notepad++ setup to compile Python code"
seoDescription: "How to quickly setup Notepad++ to run Python code"
datePublished: Sat Dec 31 2022 12:33:30 GMT+0000 (Coordinated Universal Time)
cuid: cllqr2drm00wzfxnvakjl5dv0
slug: quick-notepad-setup-for-python
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/UGqVvbRfAgI/upload/4f8acdbb659c1928431570f73618acc9.jpeg

---

Sometimes using built-in Python IDLE isn't so quick after all for testing code blocks.

Using online compilers such as [Programmiz](https://www.programiz.com/python-programming/online-compiler/) is limited by the library available. Need to use import os? Sorry NO-GO.

Luckily, Notepad++ comes to the rescue with a very concise setup:

1. Go to the Run tab in Notepad++
    
2. Click Run...
    
3. Enter the following command and save it as "Run Python" or whatever you like:
    

```bash
 python -i "$(FULL_CURRENT_PATH)"
```

1. Set a hotkey for that. I set `ctrl+F5` for that.
    
2. Now simply test any code you want in Notepad++, save it and hit `ctrl+F5` to run the Python code. Done.