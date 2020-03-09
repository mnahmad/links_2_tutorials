
# Pandoc








Generate markdown toc form markdown document

```
pandoc -s -t gfm --toc -o example-with-toc.md example.md

```

Reference:[https://github.com/jgm/pandoc/wiki/Pandoc-Tricks](https://github.com/jgm/pandoc/wiki/Pandoc-Tricks)

### Some tips

#### Generate toc on a new page

Use the header below to generate toc on a new page

```

---
title: Title of report
author:
- [author1]
- [author2]
date: 2020-03-06
toc: true
geometry: margin=2cm
output: pdf_document
urlcolor: blue
header-includes:
    \usepackage{fancyhdr}
    \pagestyle{fancy}
    \lfoot{Draft Prepared: 15 August 2018}
    \rfoot{Page \thepage}
---

\newpage{}


```

__I am still working on it as now title is not appearing on the main page__


### Nice templates
- [https://github.com/ryangrose/easy-pandoc-templates](https://github.com/ryangrose/easy-pandoc-templates)
- [https://github.com/jgm/pandoc/wiki/Pandoc-Tricks](https://github.com/jgm/pandoc/wiki/Pandoc-Tricks)
