# OpenInWezTerm

用 Shell 脚本的方式在 ~/Applications 里创建一个叫作 OpenInWezTerm.app 的、只干一件事的小 app，作用是替代 Go2Shell 这个 app，因为它不支持 WezTerm（OpenInTerminal 对 WezTerm 的支持也有问题）。

## 注意
只适用于用官网安装包安装的 WezTerm，用 Homebrew 安装的暂不支持。

## 用法
运行 build_OpenInWezTerm 之后，会在 ~/Applications 下创建 OpenInWezTerm.app。按住 Command 键把这个 app 拖动到 Finder 的工具栏上即可使用。
