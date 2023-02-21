# php-googlesheets-api
A quick-start for Google API (Sheets) using php

HOW TO USE THE GOOGLE SPREADSHEET API 

Config your google credentials on your app at 'https://console.cloud.google.com' and save as 'credentials.json'
Run 'composer require google/apiclient' on console
If you don't have the 'token.json'
    Exec this piece of code on the console and follow the path given
    After authorize the app, it will redirect to a page, on the URL get de code='VALUE' and insert into the console input
    It will generate a file named token.json
Then insert the ID of your spreadsheet and the name of the page