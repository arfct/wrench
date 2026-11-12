---
title: Wrench
date: 2021-05
status: released
category: product
tags:
  - browser-extension
url: https://chromewebstore.google.com/detail/a-wrench-menu/npngmeachnajkiekngpdhmnhkcgieccf
links:
  chrome_web_store: https://chromewebstore.google.com/detail/a-wrench-menu/npngmeachnajkiekngpdhmnhkcgieccf
  source: https://github.com/arfct/wrench
icon_shape: none
media:
  - src: menu-wikipedia.png
    caption: The menu over a Wikipedia article, with the page's title beside the Tab heading
    alt: A popup menu headed Tab - Grace Hopper - Wikipedia, with commands Copy Title with Link, Move Tab to Pop-up and Picture in Picture Video, then Window commands Merge All Windows, Clear Duplicate Tabs, Group Tabs by Website and Sleep Background Tabs, floating over the Grace Hopper article
  - src: menu-all.png
    caption: The menu after Show All Menu Items is chosen, with a checkbox beside each of the thirteen commands and the six optional ones unchecked
    alt: A white popup menu on a pale grey ground with the sections Tab, Window and Shortcuts, thirteen commands each with a checkbox, seven of them ticked, key combinations beside three of the Tab commands, and at the bottom Keyboard shortcuts... and Hide Unchecked Items
unconfirmed: [date, status]
---

The wrench in Chrome's toolbar opens a menu in two groups, Tab and Window, with seven commands between them. The extension behind it is Wrench, published in the Chrome Web Store as A Wrench Menu and last updated there in August 2022. Six further commands, Pin Tab and Switch to Prior Tab among them, are left out of the menu until Show All Menu Items is chosen, and any of the thirteen can be given a keyboard shortcut.

The README gives the aim as the lightest version of each feature, many of them a couple of lines of code. Copy Title with Link puts a plain-text copy and a linked one on the clipboard, and uses the selected text in place of the title when some is selected. Sleep Background Tabs discards every tab but the active one in each window. Close Downloads Bar works by turning the bar off and on again. The extension contains no tracking or advertising code.

JavaScript, Mithril, Chrome Manifest V3. 2021.
