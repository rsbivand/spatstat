# spatstat (experimental, 'umbrella' package)

## Are you looking for the `spatstat` package to download?

It's not here!
The current release of the `spatstat` package is available on 
the [CRAN page](https://cran.r-project.org/web/packages/spatstat).
The current development version of `spatstat` is at 
the [GitHub repository spatstat/spatstat](https://github.com/spatstat/spatstat).

## This is the EXPERIMENTAL 'umbrella' package

This is an EXPERIMENTAL package UNDER DEVELOPMENT.

This package contains almost no code from the original `spatstat` package.
It contains only the documentation, vignettes, and introductory
code for beginners.

## The new structure of the 'spatstat' family

This package is part of the new structure of the `spatstat` family of
packages.

![Spatstat pieces](RepoStuff/newspatstat.jpg)

The new `spatstat` package *depends* on the sub-packages `spatstat.utils`,
`spatstat.data`, `spatstat.sparse`, `spatstat.geom`, `spatstat.core`
and `spatstat.linnet`. After installing all these packages, you can just
type `library(spatstat)` and the entire suite of packages will be loaded.


### Rollout sequence

The sub-packages will be submitted to CRAN in the following sequence.
Each submission step requires that the previous submissions have been
accepted and propagated across the CRAN network.

1. `spatstat.utils 1.20-2` is now on CRAN. 
It is also available at the GitHub repository
[spatstat/spatstat.utils](https://github.com/spatstat/spatstat.utils).

2. `spatstat.sparse 1.2-0` is now on CRAN.
It is also available at the GitHub repository
[spatstat/spatstat.sparse](https://github.com/spatstat/spatstat.sparse).

3. `spatstat.geom 1.65-5` is now on CRAN.
It is also available at the GitHub repository
[spatstat/spatstat.geom](https://github.com/spatstat/spatstat.geom),

4. `spatstat.core 1.65-0` is now on CRAN.
It is also available at the GitHub repository
[spatstat/spatstat.core](https://github.com/spatstat/spatstat.core)

5. `spatstat.linnet 1.65-2` was submitted to CRAN on 24 January 2021
and is being processed.
It is available now at the GitHub repository
[baddstats/spatstat.linnet](https://github.com/baddstats/spatstat.linnet).

6. `spatstat.local 4.0-0` was submitted to CRAN on 24 january 2021
and is being processed.
It is available now at the GitHub repository
[baddstats/spatstat.local](https://github.com/baddstats/spatstat.local).

7. `spatstat.Knet`, `spatstat.gui`.
Estimated submission date: 29 January 2021.
Available now at the GitHub repositories
[spatstat/spatstat.Knet](https://github.com/spatstat/spatstat.Knet) and
[spatstat/spatstat.gui](https://github.com/spatstat/spatstat.gui).

8. The umbrella package `spatstat 2.0-0`, available at this repository.
Estimated submission date: 04 February 2021.

9. `spatstat.utils 2.0-0`.
Estimated submission date: 10 February 2021.
This will be a minor revision of the current
[spatstat/spatstat.utils](https://github.com/spatstat/spatstat.utils)
which Suggests the umbrella package `spatstat 2.0-0`
rather than the big old `spatstat`.
   
10. `spatstat.data 2.0-0`.
Estimated submission date: 12 February 2021.
This will be a minor revision of the current
[spatstat/spatstat.utils](https://github.com/spatstat/spatstat.utils)
which Suggests the umbrella package `spatstat 2.0-0`
rather than the big old `spatstat`.

11. `spatstat.geom 2.0-0`, `spatstat.core 2.0-0`, `spatstat.linnet 2.0-0`.
Estimated submission date: 19 February 2021.
These will be updates of the current 
[spatstat/spatstat.geom](https://github.com/spatstat/spatstat.geom),
[spatstat/spatstat.core](https://github.com/spatstat/spatstat.core) and
[baddstats/spatstat.linnet](https://github.com/baddstats/spatstat.linnet)
which will Suggest the umbrella package `spatstat 2.0-0`
rather than the big old `spatstat`. They will also include further
performance improvements.

