base64 Implemented in Bash
==========================

Pure bash implementation of the base64 algorithm

Usage
----

```
# encode
./base64 file.txt
./base64 < file.txt

# decode
./base64 -d file.b64
./base64 -d < file.b64

# encode for URLs
./base64 -u file.txt
./base64 -u < file.txt

# encode without padding
./base64 -p file.txt
./base64 -p < file.txt
```

YouTube
-------

Watch me build this live on YouTube.

<a href="https://www.youtube.com/watch?v=yICvuBin6Mg"><img
alt="Bash base64 YouTube Thumbnail"
src="https://i.ytimg.com/vi/yICvuBin6Mg/maxresdefault.jpg"
/></a>

License
-------

MIT License
