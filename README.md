Simple shell scripting pipeline for applying fred's textcleaner script on
scanned PDFs. Tweak the params of 2_clean_images directly to change the cleaner
params.

Usage:

```
./pipeline <input PDF> [<resume from step>]
```

TODO:

- Environment variables for textcleaner args and book dimensions.