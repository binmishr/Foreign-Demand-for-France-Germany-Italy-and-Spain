# Foreign-Demand-for-France-Germany-Italy-and-Spain

The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

DataSet : 
=========
1.https://cran.r-project.org/web/packages/rdbnomics/index.html

2.https://db.nomics.world

A Brief Introduction
====================

Our purpose is to build the quarterly foreign demand for France, Germany, Italy and Spain. To construct these series we use data from DBnomics, through the rdbnomics package. All the code is written in R, thanks to the RCoreTeam (2016) and RStudioTeam (2016).

For each country, we proceed in three steps:

    1.we calculate the growth of imports in volume of main trading partners;
    2.we calculate the relative importance of each trading partner in French exports;
    3.we sum over the growth rates of imports weighted by the relative importance of each trading partner.


