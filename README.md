# OneLook Thesaurus App Promotional Website

## Developing
```bash
npx browser-sync start --server 'src' --files "src/*.html,src/*.css"
```

```bash
npx tailwindcss -i ./tailwindconfig.css -o ./src/index.css --watch
```

## Deployment

### Webserver
- Static webpage so just serve everything inside the `src` folder.
- Test this out by opening `index.html` in the browser

### On Github
- Copy everything inside the `src` folder into the `docs` folder
