Installing Software for 431
================
Thomas E. Love
Version: 2018-08-08

-   [R, R Studio and R packages](#r-r-studio-and-r-packages)
-   [Step-by-Step Installation of R, R Studio and R Packages](#step-by-step-installation-of-r-r-studio-and-r-packages)
    -   [Instructions for Windows Machines](#instructions-for-windows-machines)
        -   [Windows: Installing R](#windows-installing-r)
        -   [Windows: Installing R Studio](#windows-installing-r-studio)
        -   [Windows: Installing R Packages](#windows-installing-r-packages)
        -   [Windows: Install Data and Code for 431](#windows-install-data-and-code-for-431)
    -   [Instructions for Apple / Macintosh Machines](#instructions-for-apple-macintosh-machines)
        -   [Mac: Installing R](#mac-installing-r)
        -   [Mac: Installing R Studio](#mac-installing-r-studio)
        -   [Mac: Installing R Packages](#mac-installing-r-packages)
        -   [Mac: Install Data and Code for 431](#mac-install-data-and-code-for-431)

R, R Studio and R packages
==========================

The steps here involve

1.  Installing R
2.  Installing R Studio
3.  Installing a series of R packages so we can more successfully use R.
4.  Install data and code for 431

You'll need to install these programs on either a Windows PC, or Macintosh PC (or, if you are adventurous and self-supporting, a Linux box). They cannot be run in the way we need them on an iPad or Android tablet or on a Chromebook.

**Note** If you have a pre-existing installation of R and/or RStudio, we highly recommend that you reinstall both and get as current as possible. It can be considerably harder to run old software than new.

R is a freely available computer language and environment for statistical computing and graphics, available for Windows PCs and for Macintosh. At <https://cran.r-project.org/faqs.html>, you'll find the R Project's Frequently Asked Questions page, though it's a very dry read.

R Studio is an integrated development environment for R, that includes a number of useful tools that will help us develop our R code and produce useful results. We'll use the free Desktop version of R Studio, specifically the preview version.

An R package is a collection of functions, data, and documentation that extends the capabilities of base R. Using packages is key to the successful use of R.

There will be many people in the course for whom R is a new experience. We assume no prior R work in the course. You will know a fair amount of R (and some other things, too) after taking the course, though.

Step-by-Step Installation of R, R Studio and R Packages
=======================================================

Instructions for Windows Machines
---------------------------------

### Windows: Installing R

1.  Close all other programs and point your Internet browser to <http://cran.case.edu/>
    -   Try <http://cran.us.r-project.org/> if the Case site is busy.
2.  In the **Download and Install R** box of precompiled binary distributions, click on **Download R for Windows**.

3.  Select the **base** subdirectory on the next screen, to install R for the first time.

4.  You will then see a link to **Download R 3.x.x for Windows**. (As I write, we're on version `3.5.1` but you may see a later version number.) Select this link, and, if given the option, **save** the resulting file.

5.  Once R has downloaded, close all other programs (including your browser), then double-click the downloaded file and follow the instructions to start the setup process.

6.  During the setup, click **Yes** when asked if you want a **customized startup** and select **SDI** (separate windows) instead of MDI (one big window.) Otherwise, select all of the default options.

7.  This will (eventually) produce an icon labeled R on your desktop that says something like **R i386 3.x.x** (32-bit R) or **R x64 3.x.x** (64-bit R) or (and this is most common) both icons. It doesn't matter to me whether you use 32-bit or 64-bit R, and the setup program should automatically identify the better choice for your machine.

8.  Once you see the R icon on your desktop, you are ready to install **R Studio**.

### Windows: Installing R Studio

1.  Close all other programs and point your browser to the download page for the desktop version of R Studio, at https://www.rstudio.com/products/rstudio/download/#download
    - If you prefer, you can instead [download the preview version](https://www.rstudio.com/products/rstudio/download/preview/) so as to be able to take advantage of the latest and greatest things available from R Studio. This isn't necessary for our course, though.

2.  R Studio will display a link to **Desktop Version Installers**. Select the version of R Studio (likely to be `1.1` followed by some additional numbers, at the moment it is `1.1.456` but you may see a later number) which is recommended for your operating system (most probably this is **Windows Vista/7/8/10** and is listed at the top. Click to download.

2.  Once the package has been downloaded to your desktop, close all other programs (including your browser), then double-click the package, and follow the instructions to start the setup process.

3.  Accept all default settings, and when your machine is done, you should now have an icon on your desktop (and an available program) labeled R Studio.

4.  Double-click on the R Studio icon to open it. This will connect your newly installed R to R Studio, and you will be ready to install some **R packages**.

### Windows: Installing R Packages

1.  Now, you're ready to install some of the packages you will need. Visit our [Packages page](https://github.com/THOMASELOVE/431-2018/blob/master/software/packages.md) for an up-to-date list of the R packages we are using in this course, and complete installation instructions. 

### Windows: Install Data and Code for 431

1.  Exit R Studio, being sure to agree that the workspace should be saved if you are asked, and then open a browser to <https://github.com/THOMASELOVE/431-2018-data>

2.  Click on the green **Clone or download** button.

3.  Select Download ZIP on the bottom right, and this will download a zip file of relevant data and code for the course. Put this in a directory you can find later.

4.  You should now be all set! Our discussion of R, R Studio, working with data, scripts and Markdown files continues elsewhere.

Instructions for Apple / Macintosh Machines
-------------------------------------------

### Mac: Installing R

1.  Close all other programs and point your Internet browser to <http://cran.case.edu/>
    -   Try <http://cran.us.r-project.org/> if the Case site is busy.
2.  In the **Download and Install R** box of precompiled binary distributions, click on **Download R for (Mac) OS X**.

3.  Click on the package containing the latest version (most likely **R-3.x.x.pkg**, where the version as of `Sys.Date()` is `3.5.1`, but you may see a later number) on the next screen. Download the package, to install R for the first time.

4.  Follow the installation instructions, and select all of the default options.

5.  Eventually, your Mac will tell you that the installation was successful. Hit **Close**.

6.  You can check to see that the installation worked, if you like, by looking for the R (and, likely, R64) programs under the Launchpad. But you shouldn't have a problem. You should now be ready to install **R Studio**.

### Mac: Installing R Studio

1.  Close all other programs and point your browser to the download page for the desktop version of R Studio, at https://www.rstudio.com/products/rstudio/download/#download
    - If you prefer, you can instead [download the preview version](https://www.rstudio.com/products/rstudio/download/preview/) so as to be able to take advantage of the latest and greatest things available from R Studio. This isn't necessary for our course, though.

2.  R Studio will display a link to **Desktop Version Installers**. Select the version of R Studio (likely to be `1.1` followed by some additional numbers, at the moment it is `1.1.456` but you may see a later number) which is recommended for your operating system (most probably this is **Mac OS X 10.6+ (64-bit)** and is listed near the top. Click to download.

3.  Once the package has been downloaded to your desktop, double-click on the download to show the folder where the `.dmg` file was placed. Then double-click it to install R Studio.

4.  Click on the R Studio icon (when it appears) to open it. This will connect your newly installed R to R Studio, and you will be ready to install some **R packages**.

### Mac: Installing R Packages

1.  Now, you're ready to install some of the packages you will need. Visit our [Packages page](https://github.com/THOMASELOVE/431-2018/blob/master/software/packages.md) for an up-to-date list of the R packages we are using in this course, and complete installation instructions. 

### Mac: Install Data and Code for 431

1.  Exit R Studio, being sure to agree that the workspace should be saved if you are asked, and then open a browser to <https://github.com/THOMASELOVE/431-2018-data>

2.  Click on the green **Clone or download** button.

3.  Select Download ZIP on the bottom right, and this will download a zip file of relevant data and code for the course. Put this in a directory you can find later.

4.  You should now be all set! Our discussion of R, R Studio, working with data, scripts and Markdown files continues elsewhere.
