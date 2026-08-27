ELR LaTeX Author Template Guide

Explorations in Linguistic Review (ELR)

English

The official LaTeX author template for Explorations in Linguistic Review (ELR).

This template is designed for manuscript preparation and publication in Explorations in Linguistic Review, an open-access journal covering theoretical, formal, comparative, and interdisciplinary research in linguistics.

The template provides a consistent ELR article layout, including title and author information, affiliations, abstract and keywords, numbered sections, linguistic examples, tables and figures, syntactic trees, footnotes, article metadata, and end-matter sections. It also includes the ELR bibliography style (elr-unified.bst) for author–year citations and linguistics-style reference formatting.

The template supports the ELR Main Journal and the HCLT, RCTL, and PCP special-issue series, as well as anonymous manuscript preparation for peer review.

Required Files

main.tex — The main manuscript file. Open this file to begin drafting your article.

elr-style.sty — The ELR document style package. Keep this file in the same directory as main.tex, or install it in a directory where LaTeX can find it, such as ~/Library/texmf/tex/latex/.

elr-unified.bst — The ELR BibTeX bibliography style. This file controls the formatting of the reference list.

references.bib — The BibTeX bibliography database. Add your references to this file.

logo-header.png — The ELR header logo. Keep this file in the same directory as main.tex.

ELR-Author-Template-Sample.pdf — A compiled sample article showing the intended ELR layout and formatting.

Selecting the Journal Series

Before compiling your manuscript, specify the appropriate ELR journal or special-issue series in main.tex:

\ELRSeries{ELR}

ELR — ELR Main Journal (Explorations in Linguistic Review)

HCLT — The History of Chinese and Linguistic Theory

RCTL — A Review of Cutting-Edge Theories in Linguistics

PCP — Contemporary Phonetics and Phonology

References

ELR uses BibTeX with the included elr-unified.bst bibliography style. At the end of main.tex, use:

\bibliography{references}

For testing purposes, all entries in references.bib may be displayed with:

\nocite{*}
\bibliography{references}

In a submitted manuscript, \nocite{*} should normally be removed so that only references cited in the article are included.

Compilation

XeLaTeX is recommended for the ELR template. For manuscripts containing references, compile in the following order:

XeLaTeX → BibTeX → XeLaTeX → XeLaTeX

Font Requirement

The template is configured to use the Charis font family for linguistic text and IPA support. If Charis is not already installed on your system, it can be obtained from the SIL website:

https://software.sil.org/charis/

Installing Charis is recommended for consistent typography and reliable display of IPA and other linguistic symbols.

——————————————————————

中文说明

《Explorations in Linguistic Review》（ELR）官方 LaTeX 作者投稿模板。

本模板用于 ELR 稿件撰写与出版排版，适用于理论语言学、形式语言学、比较语言学及相关跨学科研究。模板统一控制题名、作者与单位信息、摘要与关键词、章节编号、语言学例句、表格与插图、句法树、脚注、文章元数据以及文末信息，并附带 ELR 专用参考文献样式 elr-unified.bst。

模板支持 ELR 主刊及 HCLT、RCTL、PCP 三个专刊系列，并支持匿名审稿稿件。

模板文件

main.tex — 论文主文件。作者通常只需打开此文件开始撰写稿件。

elr-style.sty — ELR 期刊样式宏包。建议与 main.tex 放置在同一目录，也可以安装到 LaTeX 可识别目录，例如 ~/Library/texmf/tex/latex/。

elr-unified.bst — ELR 专用 BibTeX 参考文献样式文件，用于统一参考文献格式。

references.bib — BibTeX 参考文献数据库。请将稿件引用的文献录入此文件。

logo-header.png — ELR 页眉 Logo 文件，请与 main.tex 放置在同一目录。

ELR-Author-Template-Sample.pdf — 模板编译示例，用于查看 ELR 论文的标准版式与排版效果。

选择期刊或专刊系列

编译稿件前，请在 main.tex 中指定稿件所属的期刊或专刊代码：

\ELRSeries{ELR}

ELR — ELR 主刊（Explorations in Linguistic Review）

HCLT — 汉语史与语言学理论（The History of Chinese and Linguistic Theory）

RCTL — 语言学前沿理论评述（A Review of Cutting-Edge Theories in Linguistics）

PCP — 当代语音学与音系学（Contemporary Phonetics and Phonology）

参考文献

ELR 模板采用 BibTeX，并使用模板自带的 elr-unified.bst 控制参考文献格式。

\bibliography{references}

如仅用于测试，希望显示 references.bib 中的全部参考文献，可使用：

\nocite{*}
\bibliography{references}

正式投稿时通常应删除 \nocite{*}，以便参考文献表只列出正文实际引用的文献。

编译方式

ELR 模板建议使用 XeLaTeX。包含参考文献的稿件请按照以下顺序编译：

XeLaTeX → BibTeX → XeLaTeX → XeLaTeX

字体要求

ELR 模板使用 Charis 字体系列，以保证语言学文本、国际音标（IPA）及相关特殊字符能够稳定显示。

如果系统尚未安装 Charis，可从 SIL 官方网站获取：

https://software.sil.org/charis/

建议安装该字体，以获得与 ELR 模板示例一致的排版效果。

Explorations in Linguistic Review (ELR)
