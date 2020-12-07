## I dont really know what im doing on github

option_history.db can be downloaded and then examined with the following code through terminal

##USING SQLITE3 ON MAC SHOULD ALREADY BE INSTALLED

> sqlite3 option_history.db
> select * from option_history; #show all data
> select * from option_history where volume > 5 order by description # show relevant data that is then ordered by the contract itself first, and the chronologically
