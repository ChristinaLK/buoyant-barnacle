---
title: "Real test"
teaching: 10
exercises: 2
---

:::::::::::::::::::::::::::::::::::::: questions 

- How do you know which packages you used? 

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Print out the packages used in a session. 

::::::::::::::::::::::::::::::::::::::::::::::::

## Conclusion

Reproducibility!!

::::::::::::::::::::::::::::::::::::: challenge 

## Challenge 1: Can you do it?

What is the output of this command?


```r
sessionInfo()
```

:::::::::::::::::::::::: solution 

## Output
 

```{.output}
R version 4.0.5 (2021-03-31)
Platform: x86_64-apple-darwin17.0 (64-bit)
Running under: macOS Catalina 10.15.7

Matrix products: default
BLAS:   /Library/Frameworks/R.framework/Versions/4.0/Resources/lib/libRblas.dylib
LAPACK: /Library/Frameworks/R.framework/Versions/4.0/Resources/lib/libRlapack.dylib

locale:
[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

loaded via a namespace (and not attached):
 [1] compiler_4.0.5       magrittr_2.0.1       assertthat_0.2.1    
 [4] tools_4.0.5          stringi_1.6.1        knitr_1.33          
 [7] stringr_1.4.0        xfun_0.22            evaluate_0.14       
[10] sandpaper_0.0.0.9023
```

:::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::::::::::::


This tells you everything you need!!

::::::::::::::::::::::::::::::::::::: keypoints 

- Use `.Rmd` files for lessons even if you don't need to generate any code
- Run `sandpaper::check_lesson()` to identify any issues with your lesson
- Run `sandpaper::build_lesson()` to preview your lesson locally

::::::::::::::::::::::::::::::::::::::::::::::::

<!-- Please do not delete anything below this line -->


[cc-by-human]: https://creativecommons.org/licenses/by/4.0/
[cc-by-legal]: https://creativecommons.org/licenses/by/4.0/legalcode
[ci]: https://communityin.org/
[coc-reporting]: https://docs.carpentries.org/topic_folders/policies/incident-reporting.html
[coc]: https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html
[concept-maps]: https://carpentries.github.io/instructor-training/05-memory/
[contrib-covenant]: https://contributor-covenant.org/
[contributing]: {{ repo_url }}/blob/{{ source_branch }}/CONTRIBUTING.md
[cran-checkpoint]: https://cran.r-project.org/package=checkpoint
[cran-knitr]: https://cran.r-project.org/package=knitr
[cran-stringr]: https://cran.r-project.org/package=stringr
[dc-lessons]: https://datacarpentry.org/lessons/
[email]: mailto:team@carpentries.org
[github-importer]: https://github.com/new/import
[jekyll-collection]: https://jekyllrb.com/docs/collections/
[jekyll-install]: https://jekyllrb.com/docs/installation/
[jekyll-windows]: https://jekyll-windows.juthilo.com/
[jekyll]: https://jekyllrb.com/
[jupyter]: https://jupyter.org/
[kramdown]: https://kramdown.gettalong.org/
[lc-lessons]: https://librarycarpentry.org/lessons/
[lesson-aio]: {{ relative_root_path }}{% link aio.md %}
[lesson-coc]: {{ relative_root_path }}{% link CODE_OF_CONDUCT.md %}
[lesson-example]: https://carpentries.github.io/lesson-example/
[lesson-license]: {{ relative_root_path }}{% link LICENSE.md %}
[lesson-mainpage]: {{ relative_root_path }}{% link index.md %}
[lesson-reference]: {{ relative_root_path }}{% link reference.md %}
[lesson-setup]: {{ relative_root_path }}{% link setup.md %}
[mit-license]: https://opensource.org/licenses/mit-license.html
[morea]: https://morea-framework.github.io/
[numfocus]: https://numfocus.org/
[osi]: https://opensource.org
[pandoc]: https://pandoc.org/
[paper-now]: https://github.com/PeerJ/paper-now
[python-gapminder]: https://swcarpentry.github.io/python-novice-gapminder/
[pyyaml]: https://pypi.python.org/pypi/PyYAML
[r-markdown]: https://rmarkdown.rstudio.com/
[rstudio]: https://www.rstudio.com/
[ruby-install-guide]: https://www.ruby-lang.org/en/downloads/
[ruby-installer]: https://rubyinstaller.org/
[rubygems]: https://rubygems.org/pages/download/
[styles]: https://github.com/carpentries/styles/
[swc-lessons]: https://software-carpentry.org/lessons/
[swc-releases]: https://github.com/swcarpentry/swc-releases
[training]: https://carpentries.github.io/instructor-training/
[workshop-repo]: {{ site.workshop_repo }}
[yaml]: https://yaml.org/
