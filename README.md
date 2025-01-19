# Homework-4
Final homework for DAS 

APIS се хостирани на
 - https://dasapiinfo.azurewebsites.net
 - http://dasapidata.azurewebsites.net/
 - http://api1.azurewebsites.net/
 - https://dashomework.azurewebsites.net/

За правилно и целосно фунцкионирање на веб апликацијата треба:
- Да се инсталираат сите зависности. 
- за правилно функционирање на data_visualization и analyze_stock views, треба да бидат поставени коректно get requests на коректните urls и порти кон django rest framework apis.

Django apis се:
-  stock_info (враќа шифрите на компаниите на македонската берза)
-  signals_api (враќа json одговор за сигнали за купување,продавање или неутрално според индикаторите и осцилаторите вратени од stock_api2)
-  stock_api2 (враќа json одговор со податоци за осцилаторите и индикаторите на македонската берза)
