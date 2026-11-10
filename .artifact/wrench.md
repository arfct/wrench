---
title: Wrench
date: 2021-05
category: product
tags:
  - browser-extension
links:
  chrome_web_store: https://chromewebstore.google.com/detail/a-wrench-menu/npngmeachnajkiekngpdhmnhkcgieccf
  source: https://github.com/arfct/wrench
icon_shape: none
media:
  - src: menu-wikipedia.png
    caption: The menu open over a Wikipedia article, with three tab commands and four window commands
    alt: A popup menu headed Tab - Grace Hopper - Wikipedia, with commands Copy Title with Link, Move Tab to Pop-up and Picture in Picture Video, then Window commands Merge All Windows, Clear Duplicate Tabs, Group Tabs by Website and Sleep Background Tabs, floating over the Grace Hopper article
  - src: menu.png
    caption: The menu open from the toolbar, with the Shortcuts group shown and a keyboard shortcut beside each command
    alt: A Chrome toolbar popup menu with the sections Tab, Window and Shortcuts, listing commands such as Copy Title with Link, Merge All Windows and Switch to Prior Tab, each with a keyboard shortcut
unconfirmed:
  - date
---

Wrench is a Chrome extension, published in the Chrome Web Store as A Wrench Menu. Its toolbar button opens a menu of seven tab and window commands, among them Copy Title with Link, Picture in Picture Video, Merge All Windows and Sleep Background Tabs. Six more commands, including Pin Tab and Switch to Prior Tab, are off by default and can be turned on with Show All Menu Items. Every command can be assigned a keyboard shortcut.

Most commands are a few lines each in a background script of 449 lines. The extension makes no network requests and contains no tracking or advertising code.

The first commit is from May 2021. The current version is 1.2.1, from August 2022.

JavaScript, Mithril, Chrome Manifest V3. 2021.
