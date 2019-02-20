---
title: Home
---

[<img src="https://simpleicons.org/icons/github.svg" style="max-width:15%;min-width:40px;float:right;" alt="Github repo" />](https://github.com/yihui/hugo-xmin)

# ARJUN JAYAPRAKASH

## _PhD Candidate, NC State University_

**XMin** is a Hugo theme written by [Yihui Xie](https://yihui.name) in about four hours: half an hour was spent on the Hugo templates, and 3.5 hours were spent on styling. The main motivation for writing this theme was to provide a really minimal example to beginners of Hugo templates. This XMin theme contains about 130 lines of code in total, including the code in HTML templates and CSS (also counting empty lines).


```bash
find . -not -path '*/exampleSite/*' \( -name '*.html' -o -name '*.css' \) | xargs wc -l
```

```
      49 ./Version4/content/post/2015-07-23-r-rmarkdown.html
      64 ./Version4/public/note/index.html
      61 ./Version4/public/note/2017/06/13/a-quick-note/index.html
      56 ./Version4/public/note/2017/06/14/another-note/index.html
     139 ./Version4/public/index.html
      64 ./Version4/public/post/2015/07/23/lorem-ipsum/index.html
      95 ./Version4/public/post/2015/07/23/hello-r-markdown/index.html
      69 ./Version4/public/post/index.html
     198 ./Version4/public/post/2016/02/14/a-plain-markdown-post/index.html
      51 ./Version4/public/css/style.css
       7 ./Version4/public/css/fonts.css
      46 ./Version4/public/404.html
     151 ./Version4/public/about/index.html
      59 ./Version4/public/tags/tutorial/index.html
      59 ./Version4/public/tags/pandoc/index.html
     113 ./Version4/public/tags/index.html
      59 ./Version4/public/tags/plot/index.html
      59 ./Version4/public/tags/blogdown/index.html
      64 ./Version4/public/tags/markdown/index.html
      59 ./Version4/public/tags/rstudio/index.html
      59 ./Version4/public/tags/r-markdown/index.html
      59 ./Version4/public/tags/mathjax/index.html
      59 ./Version4/public/tags/regression/index.html
      71 ./Version4/public/categories/index.html
      59 ./Version4/public/categories/hugo/index.html
      74 ./Version4/public/categories/example/index.html
      59 ./Version4/public/categories/r/index.html
       4 ./Version4/layouts/partials/foot_custom.html
       5 ./Version4/themes/hugo-xmin/layouts/404.html
      12 ./Version4/themes/hugo-xmin/layouts/_default/single.html
      18 ./Version4/themes/hugo-xmin/layouts/_default/list.html
      16 ./Version4/themes/hugo-xmin/layouts/_default/terms.html
       0 ./Version4/themes/hugo-xmin/layouts/partials/foot_custom.html
       0 ./Version4/themes/hugo-xmin/layouts/partials/head_custom.html
       9 ./Version4/themes/hugo-xmin/layouts/partials/footer.html
      20 ./Version4/themes/hugo-xmin/layouts/partials/header.html
      51 ./Version4/themes/hugo-xmin/static/css/style.css
       7 ./Version4/themes/hugo-xmin/static/css/fonts.css
    2104 total
```

I can certainly further reduce the code, for example, by eliminating the CSS, but I believe a tiny bit of CSS can greatly improve readability. You cannot really find many CSS frameworks that only contain 50 lines of code.

Although it is a minimal theme, it is actually fully functional. It supports pages (including the home page), blog posts, a navigation menu, categories, tags, and RSS. With [a little bit customization](https://github.com/yihui/hugo-xmin/blob/master/exampleSite/layouts/partials/foot_custom.html), it can easily support LaTeX math expressions, e.g.,

`$${\sqrt {n}}\left(\left({\frac {1}{n}}\sum _{i=1}^{n}X_{i}\right)-\mu \right)\ {\xrightarrow {d}}\ N\left(0,\sigma ^{2}\right)$$`

All pages not under the root directory of the website are listed below. You can also visit the list page of a single section, e.g., [posts](/post/), or [notes](/note/). See the [About](/about/) page for the usage of this theme.
