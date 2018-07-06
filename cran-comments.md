
Maintenance release: remove use of inappropriate use isFALSE() with  versions of R prior to R 3.5.0 (causing errors on r-oldrel-windows-ix86+x86_64 test environment).

## Test environments

    * OSX (local machine using --as-cran from the command line)
    * using R version 3.5.0 (2018-04-23)
    * using platform: x86_64-apple-darwin15.6.0 (64-bit)

    * Windows ( win-builder.r-project.org uses --as-cran )
    * using R Under development (unstable) (2018-06-26 r74934)
    * using platform: x86_64-w64-mingw32 (64-bit)

## R CMD check results

    R CMD check --as-cran rqdatatable_0.1.1.tar.gz 
    
    * using option ‘--as-cran’
    * checking for file ‘rqdatatable/DESCRIPTION’ ... OK
    * checking extension type ... Package
    * this is package ‘rqdatatable’ version ‘0.1.1’
    * package encoding: UTF-8
    * checking CRAN incoming feasibility ... Note_to_CRAN_maintainers
    Maintainer: ‘John Mount <jmount@win-vector.com>’
    Status: OK
 

## Reverse dependencies

    All reverse dependencies check okay.
    
    devtools::revdep_check()
    Checking 1 packages: vtreat
    Checked vtreat: 0 errors | 0 warnings | 0 notes

Note: Codd is spelled correctly.
