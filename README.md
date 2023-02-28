# mexwtf

Inspirational quotes from Mex.

### Add New Quote

modify `/docs/_data/inspirational-quotes.json` and add a new line, like so:

```json
[
  "This is an existing quote.",
  "This is a new quote." <-- do not leave a trailing comma.
]
```

### Development

Modify the files you wish and then run :

```bash
docker run -it -p 4000:4000 -v $(pwd)/docs:/site itzg/jekyll-github-pages
```

Application should be available on `localhost:4000`