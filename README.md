#EXCHANGE-RATES

##What is EXCHANGE-RATES?
This project is used to send the current exchange rate multiplied by the required percentage in Bitrix.

##How to use it
####All commands should start with :
./fixer 

####To call for help :
./fixer help

####To access help for all available commands:
./fixer list

 ####Exchange rate command:
./fixer set:rates https://manezh.bitrix.uno/rest 1 l7c37x1gcju8t1cq currency factor
 
*currency - required currency (USA, EUR)
*factor - official rate percentage factor

###Example :
./fixer set:rates https://manezh.bitrix.uno/rest 1 l7c37x1gcju8t1cq EUR 5




