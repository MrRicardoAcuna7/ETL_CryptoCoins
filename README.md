# ETL_CryptoCoins
Calling a public API and transforming it to kdb table to analyze

## Call Public API
Utilize .j.k and to parse json format to kdb dictionary, .q.hg which is get command of the api endpoint

## Parse dictionary and transforming it to table kdb
Use of some element (iterators, flip command,etc) to select element in the dictionary and transform it into a dictionary

## Create a simple visualization of prices
Get list of columns field to graphic using embedpy
