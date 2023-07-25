# nim_example1

## 環境
```
> nim --version
Nim Compiler Version 1.6.14 [Windows: amd64]
```

## インストール
https://nim-lang.org/install_windows.html

## 実行
```
nim c -r hello.nim
```

## WebUI
https://github.com/webui-dev
https://github.com/webui-dev/nim-webui

```
nimble install webui
nim c -r webui_example1.nim
nim c -d:release -d:strip --opt:size --app:gui webui_example1.nim
```

## NiGui
https://github.com/simonkrauter/NiGui
```
nimble install nigui
nim c -r nigui_example1.nim
nim c -d:release -d:strip --opt:size --app:gui nigui_example1.nim
```
```
nimble install nigui
nim c -r nigui_example2.nim
nim c -d:release -d:strip --opt:size --app:gui nigui_example2.nim
```

## wNim
https://github.com/khchen/wNim
```
nimble install wNim
nim c -r wnim_example1.nim
nim c -d:release -d:strip --opt:size --app:gui wnim_example1.nim
```