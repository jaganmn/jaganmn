<a rel="me" href="https://fosstodon.org/@jaganmn"></a>
Hey, I'm Mikael! :-)

I live in Toronto, Ontario, Canada and I work as a research software developer in the Department of Mathematics and Statistics at
McMaster University, where my main research interests are statistical computing and statistical inference for ecological models.

I'm an active contributor to the [R programming language](https://www.r-project.org/) and to the R package ecosystem maintained by
[CRAN](https://cran.r-project.org/) and [Bioconductor](https://bioconductor.org/).

* [Since 2021](https://bugs.r-project.org/buglist.cgi?email3=jaganmn%40mcmaster.ca&emaillongdesc3=1&emailtype3=substring&list_id=44997&order=bug_id%20DESC&query_format=advanced),
  I've been reporting, diagnosing, and providing patches for bugs in R with a focus on statistical models, numerical linear algebra,
  and object orientation (generic functions, classes, methods, and method dispatch).
* I maintain R package [**Matrix**](https://CRAN.R-project.org/package=Matrix) alongside R Core Team member (and principal maintainer)
  Martin Mächler.  **Matrix** extends R with classes for representation of dense and sparse structured matrices and methods for efficient
  operations on such matrices.  **Matrix** is a "recommended" package, meaning that it is bundled with standard distributions of R and
  therefore available "out of the box" to almost all R users.  More than 2000 packages distributed by CRAN or Bioconductor list **Matrix**
  as a direct dependency.
* I maintain R package [**flint**](https://CRAN.R-project.org/package=flint), an R interface to [FLINT](https://github.com/flintlib/flint),
  a C library for number theory.  **flint** extends R with arbitrary precision implementations of operations natively performed in double
  precision.  It supports arithmetic, numerical linear algebra, special mathematical functions, and ODE system solution.  Numerical error
  is propagated rigorously using so-called [midpoint-radius interval arithmetic](https://doi.org/10.1109/TC.2017.2690633), also known as
  ball arithmetic.
* Collaborating with Ben Bolker, I contribute to a stack of R packages widely used for estimation of
  [generalized linear mixed effects models](https://en.wikipedia.org/wiki/Mixed_model), including
  [**lme4**](https://CRAN.R-project.org/package=lme4) and [**glmmTMB**](https://CRAN.R-project.org/package=glmmTMB).
* I maintain two R packages devoted to simulation and estimation of nonlinear models of epidemics, namely
  [**epigrowthfit**](https://CRAN.R-project.org/package=epigrowthfit) and [**fastbeta**](https://CRAN.R-project.org/package=fastbeta).

Most of my projects can be viewed as providing an R API for internal or system C and C++ libraries.  *Maintaining* such software
(testing that it works correctly across toolchains, platforms, environments, ...), one becomes familiar with all sorts of non-R stuff
(programming languages, libraries, tools, ...), but I don't enumerate these here.

[**Send me an e-mail**](mailto:jaganmn@mcmaster.ca) if you are looking for a competent research software person, scientific programmer,
or similar!  Funding for my current position at McMaster University may be running out, so I am looking for new and ideally full-time
contract work.
