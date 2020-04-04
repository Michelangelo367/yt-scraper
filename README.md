fetch-yt.py

`-q --query STRING` 
Text that is used for the search on YouTube. Needed

`-o --output`
Specifies the output file.
**Default:** ``data/result.sql``

`-n --number INTEGER (ARRAY)`
Number of videos fetched per level. 
If an array is provided, the i-th element equals 
the number of videos fetched on the i-th level.
**Default**: 10

`-l --levels INTEGER`
Number of recursion steps per video.
**Default**: 1

`-r --requests-per-minute INTEGER`
Defines the number of requests per minute.

`-v --verbose`
Print more information to output.
