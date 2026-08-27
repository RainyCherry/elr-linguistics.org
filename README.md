ELRLatex
Files needed for the ELR style in Latex:

elr-style.sty: the document style package file. Put this in a location where latex can find it (eg. the same folder as main.tex or ~/Library/texmf/tex/latex)
main.tex: an example of an article in the ELR style
logo-header.png: the header logo image file. Put this in the same folder as main.tex
ELR-Author-Template-Sample.pdf: the sample compiled article for reference

Open main.tex to start drafting your manuscript. Before compiling, please specify the target section/series code for your submission:\ELRSeries{xxxx}

ELR: Regular issue (Explorations in Linguistic Review)
HCLT: The History of Chinese and Linguistic Theory
RCTL: A Review of Cutting-Edge Theories in Linguistics
CPP: Contemporary Phonetics and Phonology

The Charis SIL font has recently changed its name to Charis. As of Jan 2026, the template incorporates this change. For the template to work with this font, Charis needs to be installed on your system (download it from https://software.sil.org/charis/). Compiling with XeLaTeX  is strongly recommended.


ELRLatex
Explorations in Linguistic Review (ELR) LaTeX 模板所需文件：

elr-style.sty：期刊宏包样式文件。请放置在 LaTeX 可识别路径（如与 main.tex 同级目录或 ~/Library/texmf/tex/latex）。
main.tex：ELR 样式投稿模板主文件。
logo-header.png：页眉 Logo 图片文件，请与 main.tex 放置在同一目录下。
ELR-Author-Template-Sample.pdf：编译效果参考示例。

打开 main.tex 进行写作，编译前请在代码中选择您所投稿的样式代码：\ELRSeries{xxxx}

ELR：主刊正刊（Explorations in Linguistic Review）
HCLT：汉语史与语言学理论（The History of Chinese and Linguistic Theory）
RCTL：语言学前沿理论评述（A Review of Cutting-Edge Theories in Linguistics）
CPP：当代语音与音系学（Contemporary Phonetics and Phonology）

Charis SIL 字体已更名为 Charis，模板已同步更新。为保证正常编译与音标显示，系统需安装 Charis 字体（下载地址：https://software.sil.org/charis/）。推荐使用 XeLaTeX引擎编译。
