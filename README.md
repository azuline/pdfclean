Simple shell scripting pipeline for applying fred's textcleaner script on
scanned PDFs. Tweak the params of 2_clean_images directly to change the cleaner
params.

Usage:

```
TEXTCLEANER="-g -e stretch" RESOLUTION="1533x2525" ./pipeline <input PDF> [<resume from step>]
```
