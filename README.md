# IMHO

Expanding worldviews through balanced discussions. | Get out of your echo chamber!

### Quick Start - Local Development

- For system setup instructions, see [Install Doc](./docs/install.md)

```
(imho) $ rvm use
(imho) $ yarn
(imho) $ bundle install
(imho) $ jekyll serve
```

### Quick Deploy - Staging

- Run the command `surge _site/ imho.surge.sh`.

### Quick Deploy - Production

- Run the command `surge _site/ imho.press`.

For more detailed deploy notes, see [Deploy Doc](./docs/deploy.md).

### Tests

Travis CI runs `scripts/cibuild`.

[HTML Proofer](https://github.com/gjtorikian/html-proofer) lints the html files.

To ignore an HTML tag from a check, add `data-proofer-ignore` as an attribute.
