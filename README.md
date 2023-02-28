# php-googlesheets-api

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@1,300&display=swap" rel="stylesheet">

<body>
    <h3>HOW TO USE THE GOOGLE SPREADSHEET API</h3>
    <div>
        <p>
            Config your google credentials on your app at <a href='https://console.cloud.google.com'>https://console.cloud.google.com</a> and save as 'credentials.json'
        </p>
        <p>
            Run 'composer require google/apiclient' on console
        </p>
        <p>
            If you don't have the 'token.json'
        </p>
        <ul>
            <li>
                Exec index.php the console using 'php index.php' and follow the path given
            </li>
            <li>
                After authorize the app, it will redirect to a page, on the URL get de code='VALUE' and insert into the console input
            </li>
            <li>
                It will generate a file named token.json
            </li>
        </ul>
        <p>
            Then insert the ID of your spreadsheet and the name of the page
        </p>
    </div>
</body>
