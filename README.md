start Windows Docker

run command:
```
powershell >
docker run --rm --label=jekyll --volume=D:\dev\spytify-web\:/srv/jekyll -it -p 4000:4000 jekyll/jekyll jekyll serve --trace --force_polling -w
```

copy paste the `_site` directory to root

visit `http://localhost:4000/web/overview.html`
