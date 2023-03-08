# A package to test R CMD check

We are reading R Packages (2e) Appendix on R CMD Check and needed a package with a lot of errors. 

This package does nothing except having plenty of errors. 

First one a package can't have `_`in its name use `.` instead! 

Errors: 

- binary: `a.out` (cf print_hello.c)
- dotfile: `.my_secret`. 
- greek named filed (not sure it will works as I just copy pasted) -> testing Checking for portable file names
- `R/nopermission.R` : been set to `chmode 000` I am still the owner let see if it enough (it blocks `devtools::document()` and git at least) 
- `R/big.R` is 2MB
- A directory `I_should_not_be_here` with a file (remove it to see what happen)
- `inst/CiTaTiOn`   
- `inst/zzz/` and `R/zzz/`

- Γ in DESCRIPTION

- no licence

- Default author

- depends on a package that I do not have (but looks cool!) 








