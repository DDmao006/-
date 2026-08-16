# 自指、对角化与形式系统的边界

一份从直觉到技术骨架的中文逻辑学讲义，讨论：

- 罗素悖论
- 图灵机与停机不可判定性
- 哥德尔句的直觉构造
- 第一、第二不完备性定理
- 三者共有的“编号／内化—自我作用—反转”结构

## 在线文件

- [阅读编译后的 PDF](self_reference_handout.pdf)
- [查看 LaTeX 源码](self_reference_handout.tex)

## 编译方法

源码可以直接上传至 Overleaf，并将编译器设置为 **XeLaTeX**。在标准 TeX Live 环境中，也可以运行：

```bash
xelatex self_reference_handout.tex
xelatex self_reference_handout.tex
```

第二次编译用于更新目录页码。

## 讲义的核心观点

问题并不出在自我指涉本身，而在于一个系统同时：

1. 声称覆盖所有相关对象；
2. 能把自身描述重新作为内部输入；
3. 允许在自我作用的位置上实行否定或反转。

这时，对角化可以构造出一个专门逃离系统总体判断的对象。

## 字体说明

如果目录中存在 `fonts/NotoSansSC-Subset.ttf`，源码会优先使用该字体；否则会自动使用 `ctex` 的 Fandol 字体配置。因此，只上传主文件到 Overleaf 也可以编译。
