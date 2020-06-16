# e-Rum2020 Workshop Prerequisites

Package prerequisites for Mirai's workshop at e-Rum2020 can be fulfilled using this repo as follows:

- Create a new RStudio project from the repo (https://github.com/miraisolutions/eRum2020Workshop-prereqs)
  ```
  File > New Project... > Version Control > Git
  ```
- Once in the new project, run at the R console
  ``` r
  install.packages(c("remotes", "renv"))
  remotes::install_deps()
  renv::activate()
  renv::restore() # you can ignore warnings about a different R version
  ```
