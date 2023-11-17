## Collecting Newspaper Data Programmatically

This introductory workshop shows how to access historical and current newspaper data via web APIs using the programming language R. Code examples demonstrate queries for the Library of Congress's Chronicling America and the New York Times Article Search APIs. We will transform JSON responses into dataframes and create some simple data visualizations from downloaded data.

There is a web version of the handout [here](https://htmlpreview.github.io/?https://github.com/giannetti/newspaper-data/blob/master/newspaper-data.html).

## Note on Software

To run the code chunks interactively in the cloud, do the following steps. I recommend this route if you do not want to install software on your laptop/desktop computer.

1. Go to <https://posit.cloud> and create a free account (use Google credentials to simplify login).
2. In the workspace area, click the down arrow next to "New Project" in the upper right. Select "New Project from Git Repository." In the URL field, copy/paste <https://github.com/giannetti/newspaper-data> and click "OK."
3. When "newspaper-data" deploys as a new project, have a look at the "Files" pane in the lower right. Click to open newspaper-data.Rmd. This is an R Markdown file with interactive code chunks and commentary. It will open in the scripts pane in the upper left.
4. You can run each code chunk by clicking the little green arrow ("Run Current Chunk") in the upper right. The first chunk has all the required third-party libraries and needs to be run in order for subsequent code chunks to work. Pro tip: you can also run code line by line, rather than all at once, to see how it behaves by placing your cursor on the line and clicking Ctrl + Enter (Windows) or command + return (Mac).
5. Subsequent code chunks should be fairly self-explanatory. A warning that the for loop at line 344 will take a while (ca. 30 minutes) to run to completion because of the pauses in between API requests.

If you prefer to install the software on your computer, download and install R (programming language) for your operating system at <https://cloud.r-project.org/>. Next, install RStudio desktop (IDE) at <https://posit.co/download/rstudio-desktop/>. Both the programming language and the integrated development environment are free.
