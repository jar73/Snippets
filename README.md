#### Play shuffeled songs MAC cmdline
`ls *.mp3 | sort -R |while read file; do afplay $file; done`

### Ultrastar 

    http://usdb.animux.de
    iconv -f cp1252 -t UTF-8 in.txt > out.txt

    yt-dlp --format 'bestvideo[height<=1080]' "https://youtu.be/aFkcAH-m9W0" --recode mp4
    yt-dlp "https://youtu.be/pFzv1ihK254" -f "bestaudio" --extract-audio --audio-format mp3
