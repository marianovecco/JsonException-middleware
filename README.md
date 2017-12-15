# JsonException-middleware
Middleware that parses Django http 404 responses exceptions from html to json

To use this middleware you first need to install [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/):
```
pip install beautifulsoup4
```

Then add the code to your middelware.py file (create one in your app folder if you don't have one). And finally, add the middleware in your settings.py file:
```
MIDDLEWARE = [
    ...
    ...
    'your_app.middleware.JsonException'
]
```
