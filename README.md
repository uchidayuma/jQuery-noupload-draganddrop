Name
# jQuery_drag-and-drop_select

## Overview
アップロードを伴わないドラッグ&ドロップでファイルを選択できるライブラリです（選択のみ）

Library that allows you to select files by drag and drop without uploading (selection only)

## Description
ドラッグ&ドロップでアップロードまでできるライブラリはたくさんありますが、ドラッグ&ドロップでファイル選択と画像のプレビューのみできるライブラリがなかったので、開発して共有しました。

入力フォームでは選択だけしておいて、サーバーサイド言語で同期的にアップロードしたい人向けのライブラリです。


There are many libraries that can be uploaded by drag and drop, but there was no library that could only select files and preview images by drag and drop, so develop and share it.
   
   This is a library for people who want to upload in a server-side language by selecting only the input form.


## Demo
[demo](https://www.youtube.com/watch?v=eODAC0Vm6Es)

## Requirement
jQuery > 2.0

## Install
```
<link href="/path/to/yourcss/drag-and-drop.css" rel="stylesheet">
<script src="/path/to/yourjs/drag-and-drop.js" type="text/javascript"></script>

<div class="uploader js-uploader">
  <p class='uploader__description'>Upload Description</p>
  <img src="">
  <input type="file" name="" class='js-dad-file'>
</div>
```

## Licence

MIT

## Author

[uchidayuma](https://github.com/uchidayuma)
