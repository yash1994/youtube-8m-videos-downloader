# YouTube-8M Video Downloader
This module is Python port of [Youtube-8m Videos and Frames Generator](https://github.com/gsssrao/youtube-8m-videos-frames) with few improvements ((1) Time consuming `grep` commands (2) Access Denied in fetching some javascripts.). 
Purpose of this module is to download some categorized videos for video classification task (if you dont want to use InceptionV3 features which are available for free to download at [here](https://research.google.com/youtube8m/)).

## Requirements
- Python 3.6+
- [youtube-dl](https://github.com/ytdl-org/youtube-dl)

## Usage
```python3 -u downloader.py -sc selectedcategories.txt -o /tmp/yt8m_videos/```

Where `-sc` is path to file containing categories from which you want to donwload videos and `-o` is path of output directory where videos will be stored. Run `python3 downloader.py --help` for additional help.
