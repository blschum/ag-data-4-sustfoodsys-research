# Cleaning USDA NASS Census and Survey Data, Formatted in Quick Stats

USDA NASS Quick Stats data exploration, a companion product for 'Implications of U.S. agricultural data practices for sustainable food systems research' published in *Nature Food*, Feb. 2023. doi forthcoming.

**Note**: In this exploration, we utilize manual data query and download from the Quick Stats database to represent the most accessible option. We note that NASSs API provides data users with software-mediated access to the NASS servers, it effectively gatekeeps knowledge to researchers and data users with the coding expertise to query the interface. Over the past decade, four R packages have been built: [rnassqs (2022)](https://cran.r-project.org/web/packages/rnassqs/index.html), [usdarnass (2019)](https://cran.r-project.org/package=usdarnass), [rnass (2015)](https://github.com/emraher/rnass), and [tidyUSDA (2019)](https://cran.r-project.org/web/packages/tidyUSDA/tidyUSDA.pdf) to assist users in accessing the API. Of these, none are endorsed or certified by NASS, and none arrive with use-vignettes (e.g., [rnassqs](https://cran.r-project.org/web/packages/rnassqs/vignettes/rnassqs.html), [usdarnass](https://cran.r-project.org/web/packages/usdarnass/vignettes/usdarnass.html), [tidyUSDA](https://cran.r-project.org/web/packages/tidyUSDA/vignettes/using_tidyusda.html)) that assume their users are coding novices. For resources that take a user from the basics to full access, they must seek out more detailed materials (e.g., [NC State Extension, 2021](https://content.ces.ncsu.edu/getting-data-from-the-national-agricultural-statistics-service-nass-using-r)) from resources outside the USDA. Thus, we do not explore API-mediated data query and download in this document.

### Data ethics statement
We believe in open data science and in making research more reproducible; if you run into issues with any of our code, or criticisms, please reach out to blschum on GitHub to fix/discuss them.
