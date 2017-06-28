# R_PKG_Install_Code
Automatically Install and Require R packages.

Put the code in front of any R script.

Replace the pkg1, pkg2, pkg3 as the real names of the packages you need.

Hit run.

Enjoy.

# Why this code / what problem does it solve
Every R programmer has their favorate R Packages.
As a consequence, you may encounter many unfamiliar R Packages when learning the template code.

For those packages already installed on the machine, we can simply use
``` require(package_name) ```
to load.

For those packages not installed yet, we have to identify them first and use 
``` install.packages(c("package_name_1", "package_name_2")) ```
```require (package_name_1)```
```require (package_name_2)```
to load.

What happened on me is that I don't want to wait in front of the machine to type the require command after installation.
Also it is not always a easy job to identify those packages not installed.

This is why I am trying to make it automatically.

Automatically identify those not installed.

Automatically install.

Automatically require.
