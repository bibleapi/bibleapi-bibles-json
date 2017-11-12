# Bible API JSON Bibles

[![Build Status](https://travis-ci.org/bibleapi/bibleapi-bibles-json.svg?branch=master)](https://travis-ci.org/bibleapi/bibleapi-bibles-json)

Bible translations in JSON format. All Bible translations are ready to import into `MongoDB`.

## Import

Import Bible traslation into `MongoDB` using `mongoimport` tool:

```bash
mongoimport --host localhost:27017 -u admin -p 'password' --db bibleapi --collection bible --drop --file asv.json
```

## Translations

### English

- American Standard Version (ASV)
- King James Version (KJV)

### Russian

- Contemporary Russian Translation of the Bible (CRTB)
- The New Russian Translation (NRT)
- Russian Synodal Translation (RST)
