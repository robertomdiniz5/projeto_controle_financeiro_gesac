![Mardown Logo](https://www.nexojornal.com.br/incoming/imagens/wifibrasil.png/alternates/LANDSCAPE_640/wifibrasil.png)

## General description


* Project made by me to integrate spreadsheets from different sectors linked to GESAC Financial Control (WIFI-BRAZIL that aims to bring the connection to public schools).
  
### Final gol: 

* Pass the data to the PowerBI. To create a model that can integrate  different sectors linked to GESAC Financial Control.

>[PowerBI](https://github.com/s33ding/financial_control_wifi-BR/blob/main/bi_financeiro.pbix)

### Spreadsheets: 

* Control of Parliamentary Amendments

>[Emendas2021_resumo.xlsx](https://github.com/s33ding/financial_control_wifi-BR/blob/main/Data_Source/Emendas2021_resumo.xlsx)

* Control of Credit Note and Commitment

>[Controle de Empenhos e NC 2022.xlsm](https://github.com/s33ding/financial_control_wifi-BR/blob/main/Data_Source/Controle%20de%20Empenhos%20e%20NC%202022.xlsm)
---
### Challenges:

* Business Understanding: preparation of formal documents for understanding the data based on the initial stages of CRISP-DM management. Data dictionary creation.

* Advanced data ingestion for reading excel files with different formats.
>[controle_financeiro_gesac.ipynb](https://github.com/s33ding/financial_control_wifi-BR/blob/main/controle_financeiro_gesac.ipynb)
>
-Create a primary key for the worksheets with the names of Deputies, and Senators to circumvent the inconsistency of the data entered by different professionals from the Ministry of Communications. To then do the modeling of Financial Control within PowerBI.

-Create an algorithm that would make a comparison of entities to fill in the civil name of all Parliamentarians. This filling was done based on a control of all the different parliamentary names given in a dataset with the civil name of each one (Spreadsheet: Proponents), a bank created by me from an extraction of the Open Government Data.

-Make recommendations, so that future data could be inserted atomically following database normalizations.