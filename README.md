# Gitbook theme for CERN Analysis Preservation Docs

![Image](https://github.com/cernanalysispreservation/gitbook-plugin-theme-cap/blob/master/preview.png)

## Usage

Add the theme to your book's configuration `book.json` or `book.js`:

```js
{
    "plugins": [
        "theme-cap"
    ],
    "variables": {
        "themeCAP":{
            "nav":[
                {
                    "url":"http://...",
                    "target":"_blank",
                    "name": "Link to my site"
                }
            ]
        },
    },
    "pluginsConfig": {
        "theme-cap":{
            "search-placeholder":"Search in the docs",
            "logo":"./logo.png", //logo
            "favicon": "./favicon.ico" //ico
        }
    }
},
```

Install by command:

``` bash
gitbook install
```

## Recommand plugins

```js
plugins: [
    '-sharing',
    "-fontsettings",
    'back-to-top-button',
    "copy-code-button",
    "heading-anchors",
    "theme-cap"
    //...
]
```


Enjoy!