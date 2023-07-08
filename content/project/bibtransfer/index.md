---
title: Bibtransfer
summary: A Python code to convert a BibLaTeX file for Overleaf usage.
tags:
  - bibtransfer
date: '2020-08-02T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: 'https://github.com/Jianjun-yu/bibtransfer/tree/main'


---

When utilizing Overleaf, the \printbibliography command may not consistently generate the bibliography correctly. This issue primarily arises due to the presence of bibliographic entries in the biblatex file with incorrect formats. Such problems often occur when researchers directly generate a biblatex file from various reference management software, such as Zotero. This python code help to convert biblatex file generate from different reference management softwares into a format suitable for use with Overleaf. 

The original code was written by astrobel found here: https://forums.zotero.org/discussion/22629/bibtex-export-request-option-to-omit-certain-fields-for-less-cluttered-bibliographies

Jake Chanenson made the code more robust by modifying it to run from the command line, automatic outputfile creation, giving options on what to strip and taking in multiple fields to strip. The code can be found here: https://github.com/JakeC007/Biblatex-Field-Stripper

I moderate the code to fit political science's journals and add a new function to moderate date format. I also change a lopp to make the code more efficient and fix a small problem that lead to failure of removing abstract.

