# skypoints-loyalty-pipeline.
This project loads an airline loyalty program's daily member file and mileage redemption file, splits the members into one table per country, and flattens the redemptions so they can be joined back to the members. It also checks the data for problems like missing required fields and bad dates, and sets aside any rows it can't safely load.
