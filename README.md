# ETL_CryptoCoins
Use the GET method from public API and transform it to KDB+/Q table to get analyzed.

## Make a call to Public API
Utilize .j.k and to parse JSON format to KDB+ dictionary, .q.hg which is getting command of the API endpoint.

## Parse dictionary and transform it to a KDB+ table
Use of some functions (iterators, flip command, etc) to select element in the dictionary and transform it into a table.

## Create a simple visualization for prices
Get a list of columns fields to graphic using embedpy.
