# Fonti's website

Here are some notes to myself for creating and maintain this website. This website was developed using blogdown and Hugo

1.  Load blogdown
2.  `blogdown::install_theme("cboettig/hugo-material")`\*

\*Note at this point, R will throw an error about not being able to download the theme. Not matter what method you try to create a website, (e.g. vis RStudio IDE \> New Project \> New site with blogdown) the download will always fail.

3.  The function will have downloaded the .tar.gaz file in the themes folder but will not have successfully decompress it. So I did this manually
4. Once unzipped `blogdown::serve_site()`, the site should build and be in Viewer window
