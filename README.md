# WDLM
A programming language to make word list more easier.

[Download JAR file](https://github.com/KRonaeGit/WDLM/releases/latest)

## Example Source Code
common-lib.wdlm
```wdlm
>>profile

>common

-*
-*.
-*.*
-~*

-*.png
-*.svg
-*.gif
-*.webp
-*.jpg
-*.jpeg
-*.bmp
-*.ico

-*.mp3
-*.wav

-*.mp4
-*.mov

-*.js
-*.wasm

-*.css

-*.html
-*.jsp
-*.php
```

example.wdlm
```wdlm
>>include|common-lib.wdlm

>>content
common|index
common|style
common|~
common|home
```

```bash
java -jar wdlm.jar web-dirNcon.wdlm ../wordlist/web-dirNcon.txt
```
