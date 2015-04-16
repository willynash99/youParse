# youParse
This is a forked (and fixed) version of [youParse.py by pantuts](https://sourceforge.net/projects/youparse) on SourceForge. The original version did not preserve the order of videos in provided playlists. I fixed this bug by using an ```OrderedDict``` instead of a plain old ```set```. I couldn't get in touch with pantuts, so I forked the project here. This version of youParse returns a properly ordered list of YouTube videos when passed a playlist URL.
