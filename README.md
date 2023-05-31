# pneuro-onc-browsers

[![Netlify Status](https://api.netlify.com/api/v1/badges/697ec00f-e36f-4d4f-a3ac-218d14409d3b/deploy-status)](https://app.netlify.com/sites/pneuroonccellbrowsers/deploys)

## build process

Use [blogdown](https://pkgs.rstudio.com/blogdown/) r package to build site locally ( or use hugo directly on command line). 


```r
# install.packages('blogdown')
library(blogdown)
# start a server to see current site
serve_site()
```

To add a new project, make a new directory under `content/project` and generate a 
`index.md` markdown file using markdown syntax. A header in yaml format customizes the content and various fields. A featured image can be added that will display on the main and project pages (`featured.png` in same directory as `index.md`). 


To add a new publication:

Download new bibtex and paste into publications.bib. I run searches on TexMed, check new publications, and copy the tex output.

Use [Academic cli](https://github.com/wowchemy/hugo-academic-cli) to add publications from publications.bib file to the content/publications directory. Note proceeds in chronological order (newest first) and often complains about formatting of the Month field, which must be text (Jan, not 01).

academic import --bibtex publications.bib

The site is uses the academic template from wowchemy. Documentation is available https://wowchemy.com/docs/. 

The site is rebuilt by netlify automatically when a new commit is pushed to github (https://app.netlify.com/sites/pneuroonccellbrowsers/deploys).

