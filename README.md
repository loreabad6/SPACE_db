# SPACE_db

Setting up a database for SPACE related curricula

For now, we pull the data in MyFiles to create a database in a localhost. Until we have an external server where to host this, I have documented in three scripts how to set-up the database locally. 

Here are the steps for setup:

0. Install RStudio and clone this repo. Also install PostgreSQL and pgadmin (see 1 for more info).

1. [Database configuration](scripts/database_config.md)

2. [Data import](scripts/data_import.md)

3. [Plots for report](scripts/data_static_plot.md)
   - This is a bit of a messy file since many tweaks needed to happen to generate the plots. I put it in this repo for documentation but feel free to ask any confusing points or if any plot needs to be generated again and you really don't manage with the script :)
