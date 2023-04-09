# scrape_vacancies

Those blocknotes are two parts of parser:
1. Habr.ipynb - script to parse data from https://career.habr.com/vacancies. Result of this script - the Excel file "data.xlsx" with raw data

2. Clear data.ipynb - script from clear data from the file "data.xlsx". Base functions of this script:
* splitting data in fields 'Location', 'Salary' etc.
* loading actual exchange currency rate from https://www.cbr-xml-daily.ru/daily_json.js' and parse json response
* converting all salaries from different currency on US dollars use actual currency rate
* saving information in the 'cleardata.xlsx' file

The Dashboard example: https://public.tableau.com/views/SalaryanalysisinITfromthehabr_com/MainDB?:language=en-US&:display_count=n&:origin=viz_share_link
