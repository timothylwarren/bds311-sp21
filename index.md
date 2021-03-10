---
layout: page
title: BDS 311
---


|Date                                  | Topic                             |  Relevant Reading                     | Assignment                                 |
|:-----------------------------        |:--------------------------------- |:------------------------------------  |:----------------------                      |
| Week 1 <br />03/30, 04/01&nbsp; &nbsp; &nbsp;&nbsp;&nbsp;| Course Goals and Philosophy <br />Using Python on the Jupyter Notebook &nbsp; &nbsp; &nbsp;| Software Carpentry review&nbsp; &nbsp; &nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  | Homework 1 <br/> Due Tue 04/06 &nbsp; &nbsp; &nbsp; |
|        |                |         |            |
| Week 2 <br /> 04/06, 04/08    | Analyzing Tabular Data with Pandas  |                                       | Homework 2 <br/> Due Tue 04/13 |
|     |    |     |      |
| Week 3 <br /> 04/13, 04/15    | Visualizing Biological Data |                                                   | Homework 3 <br/> Due Tue 04/20|
|     |    |     |      |
| Week 4 <br /> 04/20, 04/22    | Random processes: Description and simulation  |                                                   | Homework 4 <br/> Due Tue 04/27|
|     |    |     |      |
|  Week 5 <br /> 04/27, 04/29   | Resampling methods for hypothesis testing   |                                                   | Homework 5 <br/> Due Tue 05/04|
|     |    |     |      |
| Week 6 <br /> 05/04, 05/06    | Estimating data set parameters via the bootstrap   |                                                   | Homework 6 <br/> Due Tue 05/11|
|     |    |     |      |
| Week 7 <br /> 05/11, 05/13    | Testing and predicting relationships in data: <br />regression and correlation  |              | Homework 7<br/> Due Tue 05/18|
|     |    |     |      |
| Week 8 <br /> 05/18, 05/20    | Version control and reproducibility with Git |                                                   | Homework 7<br/> Due Tue 05/25|
|     |    |     |      |
| Week 9 <br /> 05/25, 05/27    | Analysis of the Covid-19 pandemic|                                                   | Final Project <br/> Week 1|
|     |    |     |      |
| Week 10 <br /> 06/01, 06/03    | Final projects|                                                   | Final Project<br/> Week 2|





[Github Pages](https://pages.github.com) provide a simple way to make a
website using
[Markdown](https://daringfireball.net/projects/markdown/) and
[git](https://git-scm.com).

For me, the painful aspects of making a website are

- Working with html and css
- Finding a hosting site
- Transferring stuff to the hosting site

With [GitHub Pages](https://pages.github.com), you just write things in
[Markdown](https://daringfireball.net/projects/markdown/),
[GitHub](https://github.com) hosts the site for you, and you just push
material to your GitHub repository with `git add`, `git commit`, and
`git push`.

If you love [git](https://git-scm.com/) and
[GitHub](https://github.com), you'll love
[GitHub Pages](https://pages.github.com), too.

The sites use [Jekyll](https://jekyllrb.com/), a
[ruby](https://www.ruby-lang.org/en/) [gem](https://rubygems.org/), to
convert Markdown files to html, and this part is done
automatically when you push the materials to the `gh-pages` branch
of a GitHub repository.

The [GitHub](https://pages.github.com) and
[Jekyll](https://jekyllrb.com) documentation is great, but I thought it
would be useful to have a minimal tutorial, for those who just want to
get going immediately with a simple site. To some readers, what GitHub
has might be simpler and more direct.  But if you just want to create
a site like the one you're looking at now, read on.

Start by reading the [Overview page](pages/overview.html), which
explains the basic structure of these sites. Then read
[how to make an independent website](pages/independent_site.html). Then
read any of the other things, such as
[how to test your site locally](pages/local_test.html).

- [Overview](pages/overview.html)
- [Making an independent website](pages/independent_site.html)
- [Making a personal site](pages/user_site.html)
- [Making a site for a project](pages/project_site.html)
- [Making a jekyll-free site](pages/nojekyll.html)
- [Testing your site locally](pages/local_test.html)
- [Resources](pages/resources.html)

If anything here is confusing (or _wrong_!), or if I've missed
important details, please
[submit an issue](https://github.com/kbroman/simple_site/issues), or (even
better) fork [the GitHub repository for this website](https://github.com/kbroman/simple_site),
make modifications, and submit a pull request.

---

The source for this minimal tutorial is [on github](https://github.com/kbroman/simple_site).

Also see my [tutorials](https://kbroman.org/tutorials) on
[git/github](https://kbroman.org/github_tutorial),
[GNU make](https://kbroman.org/minimal_make),
[knitr](https://kbroman.org/knitr_knutshell),
[R packages](https://kbroman.org/pkg_primer),
[data organization](https://kbroman.org/dataorg),
and [reproducible research](https://kbroman.org/steps2rr).
