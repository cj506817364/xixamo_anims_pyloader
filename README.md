# Mixamo Characters Downloader

## Pyload All

`payload_all.py` script makes use of mixamo2 API to download all anims for a single character that you choose.
The animations are saved with descriptive long names instead of the short ones used by default by mixamo UI.

How to use this script

1. Browse mixamo.com
2. Log in
3. Open JS console (F12 on chrome)
4. Download an animation and get the character ID from the Network tab
5. Then past the character id in the "character" variable at beginning of this script `character = '2591eddd-...'`
6. Then past the Authorization id in the "Authorization" variable at beginning of this script `Authorization = 'Bearer eyJhbGciO...'`
7. run `pip install -r requirements.txt`
8. keep the blank page opened and keep on pressing "Allow multiple downlaods"

Demo:

<img width="485" alt="success download all" src="https://github.com/user-attachments/assets/104302a1-80cd-4c69-bf93-da65a81131d7">

[![Demo on youtube](https://img.youtube.com/vi/EuAjnKAehGI/0.jpg)](https://www.youtube.com/watch?v=EuAjnKAehGI)

## Last

Thank's `https://github.com/gnuton/mixamo_anims_downloader` for the inspiration.
