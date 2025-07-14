1 \documentclass{report} 通常用于比较长的内容
	在HUSTtex中，
		开题报告（thesis proposal）使用[11pt,a4paper]{article}
		开题答辩（thesis opening report）使用{beamer}
		论文（thesis）使用[a4paper]{article}
2 \tableofcontents 生成目录
  \listoffigures 生成图片目录
3 \appendix 开始字母枚举
4 .bib stands for bibliography
5 \usepackage{geometry}定义页边距
	在HUSTtex中，thesis页边距参数为
	\usepackage[a4paper,top=2.5cm,bottom=2.5cm,left=3cm,right=3cm,% margins
		headheight=1.5cm,headsep=1.5em,
		footskip=2em,
	]{geometry}