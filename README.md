bomhog
=======

## Download

To download entire BOM for a language:

```shell
node download xyz
```

Where `xyz` is the 3-character language code.

This works like crap on wifi.  Use only on a wired connection.

This will download each page (chapter) and save as a HTML files in `./html/xyz/...`.


## Process

Aftering downloading, process the entire BOM for a language:

```shell
node process xyz
```

Where `xyz` is the 3-character language code, and the downloaded HTML files
are in the default location (`./html/xyz/...`).

Processed data are saved in JSON files in `./json/xyz/...`.


## Verify

After processing, verify the BOM JSON data for a language:

```shell
node verify xyz
```

Where `xyz` is the 3-character language code, and the processed JSON files
are in the default location (`./json/xyz/...`).

