polyglot
========

Service and storage for Likeastore localization

## Localization files

All locales are stored into `/locales` folder. Filename should consist of local [two-letter ISO language code](http://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) with `.json` extension.

## REST API

Read all localized strings,

```
GET /api/texts/:lang_id
```

Read localized string by prefix,

```
GET /api/texts/:lang_id?pref=SITE
```

or by few prefixes, separated by comma,

```
GET /api/texts/:lang_id?pref=SITE,APP_DASHBOARD,APP_SETTINGS
```

# License

MIT
