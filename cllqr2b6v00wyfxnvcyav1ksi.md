---
title: "Full Notepad++ Setup for Python"
seoTitle: "Full Notepad++ setup for Python compiling"
seoDescription: "How to fully setup Notepad++ to be used as Python compiler"
datePublished: Sat Dec 31 2022 12:51:48 GMT+0000 (Coordinated Universal Time)
cuid: cllqr2b6v00wyfxnvcyav1ksi
slug: full-notepad-setup-for-python
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/LkaMZj64KAM/upload/e9b7cc424c7feefde1e65d246aa56c2a.jpeg

---

If the [Quick Notepad++ Setup for Python](https://dev.to/pizofreude/quick-notepad-setup-for-python-4l5o) isn't your cup of tea, here's a full-blown setup you can try to make it world whole again as a Python dev.

### Step 1

Verify Python installation on the system. Open cmd and type:

```bash
python --version
```

If you haven't installed Python yet, get it [here](https://www.python.org/downloads/).

### Step 2

Install the "NppExec" plugin inside Notepad++. (Skip this if you have already done it)

### Step 3

Go to "plugins" --&gt; "NppExec" --&gt; click on "Execute"

When the command window pops up, add the following script and save it with a new name.

```bash
NPP_SAVE
cd $(CURRENT_DIRECTORY)
python $(FILE_NAME)
```

### Step 4

Create a menu item and hotkey to run the Python program:

Go to "plugins" --&gt; "NppExec" --&gt; click on "Advanced options"

Then, go to "settings" --&gt; "shortcutmapper" and follow the instructions to create a shortcut.

### Step 5

Test run any Python program and voila!