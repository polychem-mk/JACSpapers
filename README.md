## JACS Papers database

This project contains an exploratory analysis of the **JACS Papers 1996–2016** database from ***kaggle***.

The database includes three tables and contains information about publications and authors in the Journal of the American Chemical Society (JACS) for the period from 1996 to 2016.

------------------------------------------------------------------------

This project has the following form:

• A ***question*** related to journal format and citations.

• ***SQL query*** to find the answer.\
⚬ R packages, *DBI* and *RSQLite*, were used to make SQL queries;\
⚬ the queries are written on SQLite, version 3.46.1.

• ***R tools*** for visualizing results:\
⚬ all graphs were built using *ggplot2*, *ggrepel* and *ggwordcloud*, and\
⚬ the *ggpubr* and *gt* packages were used to create tables.

• To generate the HTML report from *JACSpapers_1996_2016.Rmd* file, you need to download the ***database.sqlite*** file from <https://www.kaggle.com/datasets/mathewsavage/jacs/data> and save it in the projects folder.
