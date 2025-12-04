[![MacOS Build for GNU Emacs](https://github.com/jaspervincent/emacs-build/actions/workflows/build.yml/badge.svg)](https://github.com/jaspervincent/emacs-build/actions/workflows/build.yml)

本仓库每天 UTC 时间 0:00 直接从上游 Git 源自动构建适用于 Darwin 的 GNU Emacs（带内存池系统）。
此版本专为希望测试最新版本的 Emacs 开发者而设计。由于此处不会修改源代码，请将任何错误报告直接发送至 Emacs 邮件列表。

构建过程中未使用任何包管理器，所有外部依赖项均从上游获取并从源代码编译。
生成的 Emacs 是静态链接的（系统组件除外），因此可以进行链接时优化。

> [!Note]
> Emacs 使用了 GNU MP Bignum 库、GnuTLS、Tree Sitter、XML2 和 Zlib。
> 由于编译 libgccjit 被认为资源消耗过大，因此可能不支持本地编译，而且在 temacs 启动后生成本地组件可能需要数小时。
>
> [来自 Emacs China](https://emacs-china.org/t/github-actions-macos-emacs/30528)