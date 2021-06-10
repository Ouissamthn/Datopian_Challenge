# Datopian_Challenge

__Goal__ : write a script to get a nice CSV file of natural gas prices.
I m working with Python 3.7 on windows.

1. Work Environment 
------
Windows 10

Python 3.9.4

Anaconda 2.0.1

2. Virtual environment 
------
You can choose to work on virtual environment, Some helpful commands:

* Creating an environment from an environment.yml file:

  `conda env create -f venv.yml` 

* To activate the virtual environment:

  `conda activate venv`
  
* Viewing a list of your environment:

  `conda env list`

* Viewing a list of the packages in an environment

  `conda list -n venv`

* Updating the virtual envuronment

  `conda env update --prefix .\Anaconda3\envs\venv --file venv.yml  --prune`

3. Export the EIA API key to the environment
------
Register here https://www.eia.gov/opendata/register.php, fill an email and a key would be sent to your email address.

__Why ?__ : Users of the EIA API are required to obtain an API Key via this registration form.

Only a valid email address is required. 

The reason for requiring an API key are to provide a means to notify users of changes in EIA's APIs.

4. Running the script  
------   
By default, the script [gas_prices.ipynb](https://github.com/Ouissamthn/Datopian_Challenge/blob/master/gas_prices.ipynb)  will give  you the daily prices of the natural gas, you can change it with weekly,monthly or annually data by editing the function parameter :

`get_eia_data(time_granularity = 'Daily')` 

`#time_granularity values in ["Daily", "Weekly", "Monthly","Annually"]`

You find the daily prices of natural gas here : [Daily_prices.csv](https://github.com/Ouissamthn/Datopian_Challenge/blob/master/GasPrices/Daily_prices.csv).


;)
