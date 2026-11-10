# Central Guoshu

A static website introducing the Central Guoshu Institute (中央国术馆), the martial-arts school founded in Nanjing in 1928.

## Run

From this directory:

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080.

You can also open `index.html` in a browser. Links and the stylesheet are relative, so a server is optional.

## Pages

- `index.html` — entrance, with the opening paragraph and three facts
- `history.html` — founding, the 1928 examination, wartime end
- `training.html` — the two departments and what students practiced
- `css/styles.css` — all visual design

There is no build step and no JavaScript. The header and footer are copied on each page. Change them in all three HTML files together.

The history pages are a public sketch. Check names and dates against sources before treating them as a finished account.
